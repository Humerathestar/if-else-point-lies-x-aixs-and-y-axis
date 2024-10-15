the point lies x-axis and y-axis 
#include <stdio.h>
int main()
{
 int x,y;
 printf("enter the value");
 scanf("%d%d",&x,&y);
 if(x==0 && y==0){
     printf("the point is origin");}
    else if(y==0){
        printf("point lies on x-axis");}
    else{
        printf("pont lies on y-axis");
    }

    return 0;
}
