**📘 4:1 Multiplexer (MUX) – Verilog**

**🔷 Overview**

 A 4:1 Multiplexer (MUX) selects one of four input signals (a, b, c, d) based on two select lines (sel[1:0]) and forwards it to a single output.
 
**🎯 Truth Table**

**sel[1:0]      Output (y)**

    00              a
    
    01              b
    
    10              c
    
    11              d

**🧠 Working Principle**
 sel = 00 → Output = a

 sel = 01 → Output = b

 sel = 10 → Output = c

 sel = 11 → Output = d

 👉 Select lines act as control inputs to choose the data.

 🧪 **Testbench Summary**
 
 Applied all combinations of sel[1:0]
 
 Verified correct selection of inputs
 
 Observed waveform output for each case
<img width="1919" height="996" alt="WAVEFORM" src="https://github.com/user-attachments/assets/4a7e6b78-201b-4713-a3a0-33d5912d7399" />

**🛠 Tools Used**

 Xilinx Vivado
 
 Verilog HDL
 
**📊 Result**

 Successful implementation of 4:1 MUX
 
 Output correctly follows select inputs
 
 Waveform verified 
 
**🚀 Applications**

 Data routing
 
 Bus selection
 
 Communication systems
 
 ALU and processor design
 
**📌 Conclusion**

 This project demonstrates how multiple inputs can be efficiently controlled and routed using select lines, forming a key building block in digital systems.

 
