Name:- Nalin kumar srivastava

PRN:- 23070123157

Branch:- ENTC- B3

Experiment 4

Aim:- To Study and implement C++ Bitwise Operators

Theory:- Bitwise operators in C++ are used to perform operations on the binary representations of integers. These operators work directly on the bits of integer types and can be very efficient for low-level programming tasks, such as manipulating flags, performing binary arithmetic, or interfacing with hardware.

# Types of Bitwise Operators

1. Bitwise AND (&)

Operation: Performs a bitwise AND operation between two integers. The result bit is set to '1' if both corresponding bits of the operands are '1', otherwise it is '0'.

Example:-
5 & 3   // 0101 & 0011 = 0001 

2. Bitwise OR (|)

Operation: Performs a bitwise OR operation between two integers. The result bit is set to '1' if at least one of the corresponding bits of the operands is '1'.

Example:-
5 | 3   // 0101 | 0011 = 0111

3. Bitwise XOR (^)

Operation: Performs a bitwise XOR (exclusive OR) operation between two integers. The result bit is set to '1' if only one of the corresponding bits of the operands is '1', but not both.

Example:-
5 ^ 3   // 0101 ^ 0011 = 0110 

4. Bitwise NOT (~)

Operation: Performs a bitwise NOT operation, also known as the complement. This operation flips all the bits of the integer, changing '0' to '1' and '1' to '0'.

Example:-
~5      // ~0101 = 1010 

5. Bitwise Left Shift (<<)

Operation: Shifts the bits of the integer to the left by a specified number of positions. Bits shifted out of the left are discarded, and '0' bits are shifted in from the right.

Example:-
5 << 1  // 0101 << 1 = 1010 

6. Bitwise Right Shift (>>)

Operation: Shifts the bits of the integer to the right by a specified number of positions. Bits shifted out of the right are discarded. For signed integers, the behavior depends on the implementation, but generally, the sign bit is preserved (arithmetic shift) or zeros are shifted in (logical shift).

Example:-
5 >> 1  // 0101 >> 1 = 0010 

# Applications of Bitwise Operators

1. Flags and Bitmasking: Bitwise operators are commonly used to set, clear, toggle, and test flags stored within an integer. For example, in a configuration register, each bit might represent a different setting.

2. Efficient Calculations: Bitwise shifts can be used to perform fast multiplications or divisions by powers of 2. For example, multiplying by 2 can be achieved with a left shift (<< 1).

3. Binary Data Manipulation: Bitwise operators are useful for manipulating raw binary data and interfacing with hardware at a low level.

4. Encryption and Compression: Bitwise operations are fundamental in algorithms for encryption and data compression, where precise control over individual bits is required.

Example:-

#include <iostream>

int main() {

    unsigned int a = 5;  // Binary: 0101
    
    unsigned int b = 3;  // Binary: 0011

    std::cout << "a & b: " << (a & b) << std::endl; 
    std::cout << "a | b: " << (a | b) << std::endl; 
    std::cout << "a ^ b: " << (a ^ b) << std::endl; 
    std::cout << "~a: " << (~a) << std::endl;     
    std::cout << "a << 1: " << (a << 1) << std::endl; 
    std::cout << "a >> 1: " << (a >> 1) << std::endl; 

    return 0;
}



Program:-


![image](https://github.com/user-attachments/assets/0ff37521-fde7-4a3f-8827-653f01c900f1)

![image](https://github.com/user-attachments/assets/29dc8f69-18ad-42d5-a465-77570a9aa7f4)

![image](https://github.com/user-attachments/assets/6853b13e-bed4-4964-856a-7881d5a53bbf)



OUTPUT:-

![image](https://github.com/user-attachments/assets/e1718d86-48ce-42dd-b207-d9d0c62a33ec)
