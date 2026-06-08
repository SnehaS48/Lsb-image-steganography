# LSB Image Steganography — Secret Data Encoding & Decoding in C

LSB Image Steganography is a software application developed in C to securely encode and decode secret text data within BMP image files using Least Significant Bit (LSB) manipulation techniques. The project was implemented using file handling, bitwise operations, and modular software design concepts on a Linux environment. It supports hiding and retrieving secret messages while preserving the visual appearance of the image. The application follows a structured software development approach including requirement analysis, component integration, testing, debugging, and validation of edge cases. Automated build execution was implemented using Makefile, and systematic test cases were executed to ensure correctness and reliability of file I/O operations, encoding logic, and data extraction processes.

## Features

* Secret message encoding into BMP images
* Secret message decoding from BMP images
* Least Significant Bit (LSB) manipulation
* File handling and binary data processing
* Command-line interface support
* Automated build using Makefile
* Validation of image capacity and file integrity

## Technologies Used

* C Programming
* Linux (Ubuntu)
* File I/O
* Bitwise Operations
* Makefile
* GCC
* Modular Programming

## Key Concepts

* Data Hiding Techniques
* Binary File Processing
* Bit Manipulation
* Dynamic Memory Handling
* Software Testing and Debugging
* Structured Software Design

## How to Compile

```bash
gcc *.c -o steganography
```

## How to Run

```bash
./steganography
```

## Outcome

This project strengthened understanding of file systems, binary data manipulation, bitwise operations, debugging, modular software design, and secure data encoding techniques in Linux-based environments.
