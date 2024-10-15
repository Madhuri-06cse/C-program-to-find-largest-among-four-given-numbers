# C-program-to-find-largest-among-four-given-numbers
# C-program-to-find-the-largest-number-among-four-given-numbers
#include<stdio.h>
void main()
{
int a,b,c,d,big;
printf("enter the numbers a,b,c,d :");
scanf("%d%d%d%d",&a,&b,&c,&d);
if(a>b)
      {
      if(a>c)
             {
             if(a>d)
             big=a;
             else
             big=d;
             }
             else
                 {
                 if(c>d)
                 big=c;
                 else
                 big=d;
                 }
          }
          else
              {
              if(b>c)
                    {
                     if(b>d)
                     big=b;
                     else
                     big=d;
                     }
               else
                   {
                   if(c>d)
                   big=c;
                   else
                   big=d;
                   }
                 }
printf("\n largest number is %d",big);
}
