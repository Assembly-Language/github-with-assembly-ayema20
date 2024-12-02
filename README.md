# asm-github1

Solve all code file 
compile and check proper running
after each program commit with proper comment and push
give the proper remarks here in readme


reg #  23-NTUT-CS-1142  Name 23-NTU-CS-1142



remarks about sum-even

I go through a list of numbers and check if each one is even by looking at its last bit.
 If the number is even, I add it to the total sum and count how many even numbers there are.
 After finishing the list, I display the total sum and count of even numbers.
 I use the test command to check if the last bit is 0, which indicates an even number.


remarks about sum-odd
it iterates through an array of integers,
checking if each number is odd by testing the least significant bit using the `test` command.
 If the number is odd, it adds it to the sum and increments the count. After processing the array, 
it displays the total sum and count of odd numbers. The `test` command checks if the least significant bit (LSB) is set, indicating an odd number.


remarks about sum-pos
The program sums and counts the positive numbers in an array by checking if each number has its most significant bit (MSB) cleared (indicating it's positive). It uses the test instruction to examine the MSB and the jmp command to skip processing if the number is negative.


Overall remarks
I used loops and jmp according to given conditions and based scenerios.