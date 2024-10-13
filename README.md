# Huffman Coding

## Overview
This repository contains an implementation of Huffman Coding, a widely-used algorithm for data compression. Huffman coding is a lossless data compression technique that assigns variable-length codes to input characters, where shorter codes are assigned to more frequent characters. This project demonstrates the core principles of Huffman coding and provides an easy-to-understand implementation in C++.

## Features
- **Huffman Tree Construction**: Builds a binary tree based on character frequency.
- **Encoding**: Converts input text into a binary string using Huffman codes.
- **Decoding**: Reconstructs the original text from the encoded binary string.
- **Memory Management**: Ensures efficient memory handling with proper destruction of nodes in the Huffman tree.

## Getting Started

### Prerequisites
- A C++ compiler (e.g., g++, clang)
- Basic knowledge of data structures (particularly trees and priority queues)

### Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/ConCorde04/huffman-coding.git

 
Usage
When prompted, enter the text you want to encode.
The program will output the corresponding Huffman codes for each character.
You can then enter an encoded string to decode it back to the original text.
