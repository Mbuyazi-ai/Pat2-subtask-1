#include <iostream>
#include <string>
#include <cctype> // for toupper and isalpha
using namespace std;

// Function to get Morse code for a letter
string getMorse(char c) {
    switch(c) {
        case 'A': return ".-";
        case 'B': return "-...";
        case 'C': return "-.-.";
        case 'D': return "-..";
        case 'E': return ".";
        case 'F': return "..-.";
