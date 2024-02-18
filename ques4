#include <stdio.h>
#include<string.h>
int main() 
    {
        char str[80],ch;
        int i,len,j;
        printf("enter the string\n");
        fgets(str,80,stdin);
        printf("enter the character\n");
        scanf("%c",&ch);
        len=strlen(str);
        for(i=0;i<len;i++)
        {
            if(str[i]==ch)
            {
                for(j=i;j<len;j++)
                {
                    str[j]=str[j+1];
                }
                len--;
                i--;
            }
        }
        printf("the final string is %c=%s ",ch,str);
        return 0;
    }
