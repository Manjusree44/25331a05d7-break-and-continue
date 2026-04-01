#include<stdio.h>
int main(){

int i;


for(i = 0;i <= 15; i++){
if(i % 5 == 0){
continue;
}
if(i == 7){
break;
}
printf("%d", i);
}
return 0;
