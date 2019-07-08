# C-Problems

# P_1

The thieves in Ali Baba land have a problem with their malfunctioning cave in which their booty is stored!

Normally, each thief has a unique password with which the cave opens to store or retrieve their goods.  However lately the cave opens even when a different combination of the passwords are used.

For example, suppose two thieves have, as their respective password: {“open”,”sesame”}. Of course “open” opens the cave, and so does “sesame”.  But the malfunctioning cave also allows strings of the form “opensesame”, “openopen”,”sesameopen” since these “words” are entirely made up of the individual passwords.  Your goal is to write a program that behaves like the malfunctioning cave.
	
You’ll be given N passwords (in lowercase) and a (potentially) concatenated string. Your task is to determine which of the passwords appear in the concatenated string, and output them in the order in which the passwords appear are given in the input (line 2)

If the potentially concatenated string is such that it cannot be formed entirely by the given  passwords, then you need to output “INVALID STRING”.

INPUT: 
First line of input contains N (N>1)
Next line contains N space separated strings in lower case denoting the passwords of the N thieves.
The last line contains the concatenated string in lower case

OUTPUT: If the concatenated string is accepted by the cave, then you need to output the thieves’ passwords in the order in which the passwords appear are given in the input, separated by a space. If the cave rejects it, output “INVALID STRING”.

ASSUMPTION: None of the thieves’ passwords are substrings of any other string.

SAMPLE INPUT 1:
2 
hello world 
worldhellohello
SAMPLE OUTPUT 1:
hello hello world

EXPLANATION:
Clearly the concatenated string is made entirely by using thieves’ passwords. Note that passwords could be present multiple times

SAMPLE INPUT 2:
2
hello world
helloplanet
SAMPLE OUTPUT 2:
INVALID STRING

Initial Template
// My roll number is (please complete)
// My screen name is (please complete)

#include<iostream>
#include<string>
#include<vector>
using namespace std;

int main() {
    
    // enter code here
    
    return 0;
}
