# Hacktoberfest
#include &lt;stdio.h> #include &lt;stdlib.h> int main() {   char ch[1000];   FILE *fptr;   if ((fptr = fopen("beginnersbook.txt", "r")) == NULL) {     printf("Error! File does not exist.");     // beginnersbook.txt exits if the file pointer returns NULL.     exit(1);   }
