**By Referring to C-based Lab videos and RISC-V-based lab videos**

**Snapshots of the compiled C code and RISC-V**

**Step 1: check whether the leafpad is installed in ur machine by using the commands
leafpad sum1ton.c& (sum1ton.c is the file name)
If the leafpad editor is opened without any errors then type the C code.**
****If the leafpad is not installed in ur machine then install by using the following command**

**sudo snap install leafpad****


****Step 2: Writing the C code in the leafpad editor** using the following command

**leafpad sum1ton.c&**



**Step 3: After writing the C code save the editor by Ctrl+s**

![task3 1](https://github.com/rajath55555/rajathkumar/assets/119932039/59046b31-35d6-4afe-9a91-c101beea5967)



**Step 4: Check for the errors by using the following command(compilation step)**

**gcc sum1ton.c**

**Step 5: Check the output by using the command**

**./a.out**

![task3 2](https://github.com/rajath55555/rajathkumar/assets/119932039/4d5e8199-d14b-4229-8e6f-e9a62bc16bae)


**The results will be displayed as** 

**Sum of numbers from 1 to 600 is 180300**


********************************************************RISCV Compilation and Execution*****************************************************

**Step 1: View the C Code in the editor window using the following command**

**cat sum1ton.c**

![task3 3](https://github.com/rajath55555/rajathkumar/assets/119932039/a0c4836d-9aeb-4d62-bd2b-bfb27da66989)

**Step 2: Compile the code in riscv using the following command**

**riscv64-unknown-elf-gcc -O1 -mabi=lp64 -march=rv64i -o sum1ton.o sum1ton.c**

**Step 3: The ls ltr command in Linux is used to list the contents of the current directory in long format, sorted by last modified time in reverse order.**

**use the command**

**ls -ltr sum1ton.c**


**Search for the Main and check the instructions of the C code execution. It has 15 instructions in the C execution**



![task3 4](https://github.com/rajath55555/rajathkumar/assets/119932039/aff12231-df66-44ce-b53a-2a5df2f605bd)


**Step 4:**

**riscv64-unknown-elf-gcc -Ofast -mabi=lp64 -march=rv64i -o sum1ton.o sum1ton.c**

![task3 6](https://github.com/rajath55555/rajathkumar/assets/119932039/c305f575-8dfa-42f8-af37-f51b00db55c5)


![task3 5](https://github.com/rajath55555/rajathkumar/assets/119932039/4eb0809e-3f07-4aec-98db-c95dd6d735c6)


![task3 7](https://github.com/rajath55555/rajathkumar/assets/119932039/eeb005ed-b4b7-43a1-a804-0f6917c1ecbb)


