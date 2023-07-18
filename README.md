# array-sum-and-avg
#include<stdio.h>
int main(){

int num[5],i;
float avg,sum=0.00;

for(i=0;i<5;i++){
    printf("num[%d]= ",i);
    scanf("%d",&num[i]);

}

for(i=0;i<5;i++){
    sum=sum+num[i];
}
avg=sum/5.00;
printf("sum=%.2f\n",sum);
printf("average of sum = %.2f\n",avg);
return 0;
}
