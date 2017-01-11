//using repl.it for this code 
#include "stdio.h"

int main(void) {
    // Disable stdout buffering
    setvbuf(stdout, NULL, _IONBF, 0);

    printf("Hello World\n");
    printf("Hi SI Wildcats\n");
    printf("My favorite colors are red and blue");
    // for Homework you were also supposed to write an agreement to your syllabus
    printf("Hi Mrs. GS\n");
    printf("\n");
    printf("I understand the syllabus and agree to the course expectations");
    printf("\n");
    printf("Thanks, Mrs. GS");
    
    return 0;
}
