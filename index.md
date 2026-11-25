
---
layout: home
title: FPGA VGA Driver Project
tags: fpga vga verilog
categories: demo
---

The aim of this project was use Verilog and a Basys 3 Development board to generate graphics ona a VGA monitor. I started with the ColoursStripes template code. I made changes with the code and I learned how it works. After that I added a French, Italian, German and Jamaican flags. I added a 2 switches to change between them. This project helped me understand how vga graphics and pixel coordinates work.
I am adding a test sentence here at 13:24 on 03/12/24.

## **Template VGA Design**
### **Project Set-Up**
I used Vivado to develop the code for my board. My project uses row and column coordinates to determine and change the each pixel on the VGA monitor. The RGB outputs control the each pixel. I used SW0 as the rset switch, SW1 and SW2 to change between flags.

<img width="1204" height="600" alt="Screenshot 2026-11-25 164102" src="https://github.com/user-attachments/assets/ccdd2eee-98f5-4b2a-923c-45497cbae14a" />

### **Template Code**
The original ColourStripes template displays eight vertical colour stripes on a vga monitor. It uses pixel coordinates and RGB values to control the colours. The VGA synchronisation signals control the display of the image on the screen.
<img width="1204" height="600" alt="Screenshot 2026-11-25 164102" src="https://github.com/user-attachments/assets/c40d138c-aa2b-4a81-9303-feb61dfa5d26" />
### **Simulation**
I used Vivado Behavioral Simulation to observe the RGB outputs, pixel coordinates and VGA synchronisation signals. The initial simulation showed undefined values because the input signals were not driven. A testbench is needed to provide the clock, reset and switch values to test the design properly.
<img width="1062" height="680" alt="image" src="https://github.com/user-attachments/assets/aa735dfe-38dd-4a0a-ad9a-cc22ad02e4ea" />
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
### **Synthesis**
Describe the synthesis & implementation outputs for your design, are there any differences to that of the original design? Guideline 1-2 short paragraphs.
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
