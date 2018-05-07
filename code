#include<stdio.h>
#include<string.h>
#include<ctype.h>

int main () {
    
    char str[100];
    int i=0;
    
    fgets(str, sizeof str,stdin);

    while(str[i]) {
        if(islower(str[i])){
          putchar (toupper(str[i]));  
        }
        else if(isupper(str[i])){
           putchar (tolower(str[i])); 
        }
        else{
            putchar(str[i]);
        }
      
      i++;
   }


   
    
    return 0;
}
