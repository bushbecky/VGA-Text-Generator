# VGA-Text-Generator
A basic VGA text generator for printing text from FPGA to Monitor via VGA. The module is written in VHDL but it can work with Verilog and I'll show some usages below.  

# Environment
I'm using Vivado Webpack 2015.3 and Basys3 FPGA Dev Board for this project.

# Supported Characters
ASCII code 0 - 127

# Disclosure
- This little text generator is originally a part of my school projects. Unfortunately, the other parts such as how to handle vga and etc are exclude from this project since those files are wrriten by the school staffs and I don't have their consent. However, the code is relatively easy and short. You will be able to apply it after you understand the logic.
- This project is inspired by [MadLittleMods/FP-V-GA-Text](https://github.com/MadLittleMods/FP-V-GA-Text).
- I'm totally a newbie in Verilog and VHDL(couples week of school class for Verilog and learn VHDL by study MadLittleMods' code line by line). And this is why I'm trying to keep this project as simple as possible. A lot of the existing vga text module is too good/complex(sometimes due to optimisation) for me to understand and none of them fits my need.
- This project is just a generator without any(well, still has a bit of opt but easy to understand) optimisation. I hope this project will give you a quick start on printing text via vga. However, you may need to work a bit more to get some advance features such as dynamic text(I include a hint in wrapper.vhd), font size changing, font color changing and etc.

# Usages(working in progress)
### Verilog
If you would like to call this generator's modules from Verilog, you can use:
- **Case 1:**
- **Case 2:**

### VHDL
If you would like to call this generator's modules from VHDL, you can use:
- **Case 1:**
- **Case 2:**



License
-------
    The MIT License (MIT)
    
    Copyright (c) 2015 Derek Wang
    
    Permission is hereby granted, free of charge, to any person obtaining a copy
    of this software and associated documentation files (the "Software"), to deal
    in the Software without restriction, including without limitation the rights
    to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
    copies of the Software, and to permit persons to whom the Software is
    furnished to do so, subject to the following conditions:
    
    The above copyright notice and this permission notice shall be included in all
    copies or substantial portions of the Software.
    
    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
    AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
    OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
    SOFTWARE.
