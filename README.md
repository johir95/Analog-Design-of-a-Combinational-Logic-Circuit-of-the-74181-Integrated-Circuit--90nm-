# Analog-Design-of-a-Combinational-Logic-Circuit-of-the-74181-Integrated-Circuit--90nm-
&nbsp;
&nbsp;
&nbsp;
<h2>About:</h2>
The 74181 ALU (arithmetic/logic unit) chip powered many of the minicomputers of the 1970s: it provided fast 4-bit arithmetic and logic functions, and could be combined to handle larger words. The 74181 implements a 4-bit ALU providing 16 logic functions and 16 arithmetic functions.
There are four selection inputs, S0 to S3, to select the function. M is used to select between logical and arithmetic operation, and Cn is the carry-in. A and B is the data to be processed (four bits). F is the number output. There are also P and a G signals for a carry-look ahead adder.
Initially, I designed individual schematics, symbols, and layouts for basic logic gates (2-input AND, 3-input AND, 4-input AND etc). Integrated these into a comprehensive 74181 ALU, utilizing the symbols as building blocks for the complete IC layout in Cadence Virtuoso.

<a href="𝘩𝘵𝘵𝘱𝘴://𝘸𝘸𝘸.𝘳𝘪𝘨𝘩𝘵𝘰.𝘤𝘰𝘮/2017/03/𝘪𝘯𝘴𝘪𝘥𝘦-𝘷𝘪𝘯𝘵𝘢𝘨𝘦-74181-𝘢𝘭𝘶-𝘤𝘩𝘪𝘱-𝘩𝘰𝘸-𝘪𝘵.𝘩𝘵𝘮𝘭" />  </a>
ref : 𝘩𝘵𝘵𝘱𝘴://𝘸𝘸𝘸.𝘳𝘪𝘨𝘩𝘵𝘰.𝘤𝘰𝘮/2017/03/𝘪𝘯𝘴𝘪𝘥𝘦-𝘷𝘪𝘯𝘵𝘢𝘨𝘦-74181-𝘢𝘭𝘶-𝘤𝘩𝘪𝘱-𝘩𝘰𝘸-𝘪𝘵.𝘩𝘵𝘮𝘭

&nbsp;
&nbsp;
&nbsp;

<h2>𝗖𝗶𝗿𝗰𝘂𝗶𝘁 𝘁𝘆𝗽𝗲𝘀:</h2>

 -  CMOS INVERTER      x7
 -  CMOS 2-INPUT NAND  x1
 -  CMOS 4-INPUT NAND  x2

 -  CMOS 2-INPUT AND     x20
 -  CMOS 3-INPUT AND     x12
 -  CMOS 4-INPUT AND     x5

 -  CMOS 2-INPUT NOR     x5
 -  CMOS 3-INPUT NOR    x4
 -  CMOS 4-INPUT NOR    x2
 -  CMOS 2-INPUT XOR     x8

&nbsp;
&nbsp;
&nbsp;

<h2>𝗞𝗲𝘆 𝗙𝗲𝗮𝘁𝘂𝗿𝗲𝘀:</h2>

-  **Tools:** Cadence Virtuoso (Crack)
-  **Technology Node:** gpdk090
-  **Length of nmos & pmos:** 100n
-  **Total width of nmos & pmos:** 120n
-  **Fingers of nmos and pmos:** 120n
-  **Physical Verification Tool:** LVS & DRC ( ASSURA)
&nbsp;
&nbsp;
&nbsp;

<h2>Schamatic Diagram:</h2>

<img align="[right" alt="Chip Design" width="400" src="https://github.com/johir95/Analog-Design-of-a-Combinational-Logic-Circuit-of-the-74181-Integrated-Circuit--90nm-/blob/main/sch1.png">

&nbsp;
&nbsp;

<img align="[right" alt="Chip Design" width="400" src="https://github.com/johir95/Analog-Design-of-a-Combinational-Logic-Circuit-of-the-74181-Integrated-Circuit--90nm-/blob/main/sch3.png">

&nbsp;
&nbsp;
&nbsp;

<h2>Layout Diagram:</h2>

<img align="[right" alt="Chip Design" width="400" src="https://github.com/johir95/Analog-Design-of-a-Combinational-Logic-Circuit-of-the-74181-Integrated-Circuit--90nm-/blob/main/lay1.png">

&nbsp;
&nbsp;

<img align="[right" alt="Chip Design" width="400" src="https://github.com/johir95/Analog-Design-of-a-Combinational-Logic-Circuit-of-the-74181-Integrated-Circuit--90nm-/blob/main/lay4.png">

&nbsp;
&nbsp;


<h2>Verification:</h2>

<h3>DRC Check:</h3>

<img align="[right" alt="Chip Design" width="400" src="https://github.com/johir95/Analog-Design-of-a-Combinational-Logic-Circuit-of-the-74181-Integrated-Circuit--90nm-/blob/main/DRC.png">

&nbsp;
&nbsp;

<h3>LVS Check:</h3>

<img align="[right" alt="Chip Design" width="400" src="https://github.com/johir95/Analog-Design-of-a-Combinational-Logic-Circuit-of-the-74181-Integrated-Circuit--90nm-/blob/main/LVS.png">

&nbsp;
&nbsp;
