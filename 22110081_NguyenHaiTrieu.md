# Lab #1,22110081, Nguyen Hai Trieu, INSE331280E_03FIE
# Task 1: Software buffer overflow attack
**Question 1**:
- Compile both C programs and shellcode to executable code. 
- Conduct the attack so that when C executable code runs, shellcode willc also be triggered. 
  You are free to choose Code Injection or Environment Variable approach to do. 
- Write step-by-step explanation and clearly comment on instructions and screenshots that you have made to successfully accomplished the attack.
**Answer 1**:
## 1. Compile both C programs and shellcode to executable code. :
Create vul.c and sh.c.
Complie using command :
gcc vul.c -o vul.out -fno-stack-protector -z execstack -mpreferred-stack-boundary=2
gcc sh.c -o sh.out -fno-stack-protector -z execstack -mpreferred-stack-boundary=
![image](https://github.com/user-attachments/assets/e12fae0e-8010-4763-b90f-73d88f0e6df8)
![image](https://github.com/user-attachments/assets/8cfbb852-63ca-4550-b327-8da906c3f53f)

## 2. Conducting attack
Get 
# Task 2: Attack on the database of bWapp 
  
