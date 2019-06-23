# submit50-cs50-2019-x-mario-less 
#include <cs50.h>
#include <stdio.h>
int get_int_right(string prompt);
int main(void)
{int h;
 //entering optimum hieght 
 do{
     
         h=get_int("height:");
         
 }while(h<1 || h>8);
    printf("stored:%i\n",h);

//hashes and spaces
 for(int i=0;i<h;i++)
 { for( int l=h-i;l>1;l--)
     {
     printf(" ");
 }
 for(int j=0;j<=i;j++)
 {
     printf("#"); 
     
 } 
   printf("\n");  
 }
}
