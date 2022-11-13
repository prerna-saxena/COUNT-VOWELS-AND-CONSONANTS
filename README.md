# COUNT-VOWELS-AND-CONSONANTS


// Online C compiler to run C program online
#include <stdio.h>
#include <string.h>

int main() {
    int i, vcount=0, ccount=0;
    char str[i];
    printf("ENTER A STRING\n");
    scanf("%s", &str[i]);
    for(i=0; i<strlen(str); i++)
    {
        str[i] = tolower(str[i]); 
        if(str[i]=='a'||str[i]=='i'||str[i]=='e'||str[i]=='o'||str[i]=='u')
        {
            vcount++;
        }
        else if(str[i] >= 'a' && str[i] <= 'z'){
            ccount++;
        }
    }
    
    printf( vcount);
    printf("NO OF CONSONANTS IN A STRING", ccount);
    
}
