# Programmierung in C / C++: Übung 3

## Data types and Variables

## What is the value range relationship between "char", "short", "int", "long" and "long long". What is defined about their type size/value range? What about unsigned types?

The standard tooks this different types and their supported ranges only in relationship and defines minimum boundaries.

> sizeof(char) ≤ sizeof(short) ≤ sizeof(int) ≤ sizeof(long) ≤ sizeof(long long)

* char min. 8bit 
* short min. 16bit
* long min. 32bit
* long long min. 64bit

## Give 3 examples of integer data types that have a fixed size? In what standard were they introduced?

* C99 Standard
* defines optional fixed size integers
* int8_t, uint16_t, int16_t (See here...)[http://en.cppreference.com/w/c/types/integer]