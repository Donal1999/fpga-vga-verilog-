---
Layout: home
Title: FPGA VGA Driver Project
Tags: fpga vga verilog
Autor: Dónal Ó Maoilchiaráin 
---
This is a blog I wrote to document my VGA driver project for System on Chip Design and Verification. I programed an FPGA to display an image on a monitor. 


## **Template VGA Design**
### **Project Set-Up**
The board I used for this project  was a  Basys 3 with an Artix-7 FPGA. I used the Vivado IDE to develop the VGA driver using the hardware description language verilog. I followed a design flow to create the VGA driver. 

<img width="994" height="588" alt="Screenshot 2025-12-02 145214" src="https://github.com/user-attachments/assets/c5732c02-cc86-43e6-981c-34f9531b7aba" />

### **Template Code**
Outline the structure and design of the Verilog code templates you were given. What do they do? Include reference to how a VGA interface works. Guideline: 2/3 short paragraphs, consider including screenshot(s).
I was given two verilog code templates for this project. One was a static image of vertical stripes. Each stripe was a different colour. The second template was dynamic.It cycled through a range of colours. The full screen was a  
### **Simulation**
Explain the simulation process. Reference any important details, include a well-selected screenshot of the simulation. Guideline: 1/2 short paragraphs.
### **Synthesis**
Describe the synthesis and implementation processes. Consider including 1/2 useful screenshot(s). Guideline: 1/2 short paragraphs.
### **Demonstration**
Perhaps add a picture of your demo. Guideline: 1/2 sentences.

## **My VGA Design Edit**
Introduce your own design idea. Consider how complex/achievabble this might be or otherwise. Reference any research you do online (use hyperlinks).
### **Code Adaptation**
Briefly show how you changed the template code to display a different image. Demonstrate your understanding. Guideline: 1-2 short paragraphs.
### **Simulation**
Show how you simulated your own design. Are there any things to note? Demonstrate your understanding. Add a screenshot. Guideline: 1-2 short paragraphs.
<img width="1525" height="867" alt="Screenshot 2025-12-02 145036" src="https://github.com/user-attachments/assets/37457dca-6a14-489c-a9c7-14fd73d7f859" />


### **Synthesis**
Describe the synthesis & implementation outputs for your design, are there any differences to that of the original design? Guideline 1-2 short paragraphs.
<img width="1077" height="613" alt="Screenshot 2025-12-02 151229" src="https://github.com/user-attachments/assets/a9b47e1f-2e36-4e7e-a5c7-38fc261c039d" />

### **Demonstration**
If you get your own design working on the Basys3 board, take a picture! Guideline: 1-2 sentences.

## **More Markdown Basics**
This is a paragraph. Add an empty line to start a new paragraph.

Font can be emphasised as *Italic* or **Bold**.

Code can be highlighted by using `backticks`.

Hyperlinks look like this: [GitHub Help](https://help.github.com/).

A bullet list can be rendered as follows:
- vectors
- algorithms
- iterators

Images can be added by uploading them to the repository in a /docs/assets/images folder, and then rendering using HTML via githubusercontent.com as shown in the example below.

<img src="https://raw.githubusercontent.com/melgineer/fpga-vga-verilog/main/docs/assets/images/VGAPrjSrcs.png">
