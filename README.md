#include<stdio.h>
int main(){

int num[5],i,sum=0;
float avg;

for(i=0;i<5;i++){
    printf("num[%d]= ",i);
    scanf("%d",&num[i]);

}

for(i=0;i<5;i++){
    sum=sum+num[i];
}
printf("sum= %d\n",sum);
printf("average of sum = %.2f\n",(float)sum/5);
return 0;
}
