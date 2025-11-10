# Print-A-to-Z-Using-While-Loop
Using C language program is made which gives the output to Print A to Z Using While Loop
#include <stdio.h>
int main() {
    char ch = 'A';
    while(ch <= 'Z') {
        printf("%c ", ch);
        ch++;
    }
    return 0;
}
