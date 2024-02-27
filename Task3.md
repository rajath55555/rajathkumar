**By Referring to C-based Lab videos and RISC-V-based lab videos**

**Snapshots of the compiled C code and RISC-V**

**Step 1: check whether the leafpad is installed in ur machine by using the commands
leafpad sum1ton.c& (sum1ton.c is the file name)
If the leafpad editor is opened without any errors then type the C code.**
****If the leafpad is not installed in ur machine then install by using the following command**

**sudo snap install leafpad****


****Step 2: Writing the C code in the leafpad editor** using the following command

**leafpad sum1ton.c&**

![WhatsApp Image 2024-02-27 at 10 58 21 AM (1)](https://github.com/ajeethdani/ajeetkumarkdani/assets/114277218/21229fef-81a7-4fd6-af08-85449990a4b8)

**Step 3: After writing the C code save the editor by Ctrl+s**

![WhatsApp Image 2024-02-27 at 10 58 21 AM (2)](https://github.com/ajeethdani/ajeetkumarkdani/assets/114277218/a9003904-6d39-479c-a587-dfe039a9d9b5)


**Step 4: Check for the errors by using the following command(compilation step)**

**gcc sum1ton.c**

**Step 5: Check the output by using the command**

**./a.out**

![WhatsApp Image 2024-02-27 at 10 58 21 AM (3)](https://github.com/ajeethdani/ajeetkumarkdani/assets/114277218/a22279f0-6b21-436f-8793-0d69fdaf8e54)

**The results will be displayed as** 

**Sum of numbers from 1 to 50 is 1275**


********************************************************RISCV Compilation and Execution*****************************************************

**Step 1: View the C Code in the editor window using the following command**

**cat sum1ton.c**
![WhatsApp Image 2024-02-27 at 11 51 41 AM](https://github.com/ajeethdani/ajeetkumarkdani/assets/114277218/8cfda518-af70-4453-8c98-78517e8dd6d9)


**Step 2: Compile the code in riscv using the following command**

**riscv64-unknown-elf-gcc -O1 -mabi=lp64 -march=rv64i -o sum1ton.o sum1ton.c**

**Step 3: The ls ltr command in Linux is used to list the contents of the current directory in long format, sorted by last modified time in reverse order.**

**use the command**

**ls -ltr sum1ton.c**
![WhatsApp Image 2024-02-27 at 11 57 31 AM](https://github.com/ajeethdani/ajeetkumarkdani/assets/114277218/94dcbb78-13c0-4509-97cf-a4290e0f8346)


**Search for the Main and check the instructions of the C code execution. It has 15 instructions in the C execution**

![WhatsApp Image 2024-02-27 at 11 56 54 AM](https://github.com/ajeethdani/ajeetkumarkdani/assets/114277218/bc85cf82-6f55-444c-9883-9ffe98e62269)



**Step 4:**

**riscv64-unknown-elf-gcc -Ofast -mabi=lp64 -march=rv64i -o sum1ton.o sum1ton.c**

![WhatsApp Image 2024-02-27 at 11 56 56 AM](https://github.com/ajeethdani/ajeetkumarkdani/assets/114277218/8f4a8e7f-7a17-47fd-ae80-d8cfcef6f633)


![WhatsApp Image 2024-02-27 at 11 56 55 AM](https://github.com/ajeethdani/ajeetkumarkdani/assets/114277218/ad3d5a03-49fb-4419-bf21-374e9a35cd42)


![WhatsApp Image 2024-02-27 at 11 56 55 AM (1)](https://github.com/ajeethdani/ajeetkumarkdani/assets/114277218/10a99f1d-b5d8-498e-88bd-66ef06cbfb49)




