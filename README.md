java c1
HOME ASSIGNMENT 1
Given: Fri 7 Feb 2025
Due: Fri 21 Feb 2025
INSTRUCTIONS
1. This assignment has 1 question and 2 parts, on pages 1-2.
2. Submit a hardcopy of your handwritten answers to Dr JJ Sit’s office: S2-B2a-31.
3. Submit a single ZIP file to the NTUlearn Assignment Tab containing:
a. A scanned softcopy of your handwritten answers
b. All LTspice files required to run your solution (*.asc, *.asy) and any *.log files
1 (a) Design and size a Miller-compensated 2-stage op-amp in the TSMC18 process that 
matches the Reid amplifier (2003) specifications with passband gain = 100 (i.e. 
40dB), bandwidth = 7kHz and UGBW = 700kHz (all within 10% margin).
The first stage input Gm required will be based on your Matriculation number.
If the Last digit of your Matriculation Number is Odd, design for Gm = 1 mA/V. 
If the Last Digit is Even, design for Gm = 0.1 mA/V.
For example:
G2212345J Gm = 1 mA/V
G2212346J Gm = 0.1 mA/V
The choice of input transistors will depend on the last Letter of your 
Matriculation Number. Letters A-F must use NMOS inputs, and Letters G-Z
must use PMOS inputs.
For example:
U2212345{A-F} Use NMOS inputs
U2212346{G-Z} Use PMOS inputs
(i) A template for the Reid amplifier is given, with only the first stage of the 
opamp subcircuit provided, that you need to complete with a second stage.
EE6307
2
(ii) Use the TSMC18 curves provided to size all NMOS transistors set to have the 
same Wn, Ln values and all PMOS transistors set to have the same Wp, Lp 
values as parameters specified in the top-level simulation. All unknown 
parameter values are initially set to 1u by default as shown below.
Do not modify the following:
• PMOS pseudo-resistors provide the DC biasing on V+ and V- with 
Lr=4um and Wr=1um to provide very high resist代 写EE6307、Java/Python
代做程序编程语言ance > 1G.
• Supply voltage VDD = 2V, DC ground reference Vref = 1V (equivalent to 
a 1V low-voltage dual-supply)
• Output load capacitance CL = 10pF
• Capacitor divider {C1} = 20pF and {C2} = 0.2pF for {C1}/{C2} = 100
(iii) Show all calculations how you derive the final Ibias parameter value (note ID
for each input transistor will be Ibias/2) along with any Miller compensation 
component values (Rz, Cc) if required.
(iv) Explain all the design requirements you used to achieve closed loop stability.
(v) Show a screenshot or a drawing of your final op-amp configuration, with all 
the component values labelled clearly.
EE6307
3
(b) Simulate your design in LTspice17 to verify if your hand calculations are correct.
Note you cannot use LTspice24, as it does not record the AC small signal 
parameters in the .log file. So you must install LTspice17 instead, highlighted below.
For more details about the bug in LTspice24, please visit this link.
Attach screenshots of the following:
(i) .AC simulation of Vo from 0.1 Hz to 100MHz
(ii) .NOISE simulation from 0.1Hz to 50kHz as given, with the total integrated
output noise calculated like shown below. (Hold Ctrl- and click on the onoise 
label at the top of the graph to integrate the curve)
(iii) Your .log file with the .MEAS results and timestamp from the .AC simulation
as shown below.
EE6307
4
(iv) Finally, attach a screenshot of the input transistors AC small signal parameters 
from Id to Gmb values (showing an NMOS input pair highlighted below) 
And also show the AC small signal parameters from Id to Gmb for the 
common source second stage amplifier (showing PMOS below)
Explain any significant differences from your hand calculations in part (a).
 
END OF ASSIGNMENT

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
