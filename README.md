**ß-Assembler**
===================


A simple assembler for a custom microprocessor, with support for logisim's rom..





![it's a simple assembler that translate assembly code into machine code that can be used in a Logisim's ROM.](https://lh3.googleusercontent.com/-owNW8ChFVCc/WKSpS0jC7qI/AAAAAAAAACQ/Q1Xd-24Xj5EajLfJBN1Xa43HI1wEqDTagCLcB/s0/1502.PNG "screenshot.PNG")

----------

### What is it?

it's a simple assembler that translate assembly code into machine code that can be used in a Logisim's ROM.

### How can i compile this?
This assembler is made in c#, you can simply download the pre-compiled file [here](https://github.com/AlessioGiacobbe/GPLMicroProcessor-Assembler/blob/master/GPL2015%20Assembler/compiled/GPL2015_Assembler.exe) or build your own version using Visual Studio.

### Configuration
you can use your own configuration, according to the supported operations, and it must to be formatted like this :
```
0000 HALT
0001 LD A,n
0010 LD A,B
0011 LD A,C
0100 LD B,A
0101 LD C,A
0110 ADD A,B
0111 ADD A,C
1000 SUB A,C
1001 INC B
1010 DEC B
1011 JP addr
1100 IN A
1101 OUT A
1110 JP P, addr
1111 JP M, addr
```

### More questions?
if you have more questions you can contact me at giacobbealessio@gmail.com


