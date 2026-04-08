#include<stdio.h>
int main(){

printf(“25331a05d7\n”);
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
}
