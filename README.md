#include <stdio.h>

int main()
{
int year = 0;
printf("Enter Year Please:");
scanf("%d", &year);

if(year % 4 == 0){
   printf("Its a Leap Year");
}else{
  printf("Its a Nomral Year");
}

}
