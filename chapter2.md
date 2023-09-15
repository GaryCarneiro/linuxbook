# Computer Hardware Essentials

Before we embark on our journey to learning Linux, let us understand how Linux and the Computer Hardware interact with each other to make an Operating system work to achieve some common goals like making the Hardware accessible to the user for performing common tasks like editing files, connecting to Internet, installing and running applications etc.


## The Processor

The Processor is a short for Central Processing Unit. This is brain of the computer and just like the brain, it interacts with different parts of the body, a processor interacts with different components such  as Disk, GPU, Mouse, Keyboard, Network Card etc. The Processor takes differents instructions from Input devices and executes tasks in form ones and zeroes. These ones and zeroes are called instructions to the processor and whole Computer System is built around the processor executing these ones and zeroes


For example, lets say you have a calculator program running on GUI, the processor is actually computing the numbers as advised by the program. You type in the numbers and want to add them together, this forms a Instruction and Operands to the Processor. Below is an instruction to add 2 numbers 20 and 10

```asm

MOV EAX, 20
ADD EAX, 10

```