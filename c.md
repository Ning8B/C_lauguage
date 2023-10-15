.md markdown 副檔名  
換行記得空兩格  
```c=  
#include <stdio.h>
int main(){  
  int a;  
  scanf("%d",&a);  
  printf("Hello world");  
return 0;  
}  
```
%=取餘數
//取商  
int main(){} 主程式  
int 變數  
printf("") 列出  
scanf("%d",n) 輸入資料n  
if(條件式){  
  執行事項  
}  
else if(條件式){  
  執行事項  
}  
else //若不符合上述條件則執行{  
  執行事項  
}  
while(1){ //重複迴圈  
  執行事項  
}  
switch(變數)  
  case ?; //當變數為?,則執行  
  break; 結束  
  default; //當變數不為上case的條件時則執行  
使用隨機取數  
#include <stdlib.h>  
#include <time.h>  
srand(time(NULL));  
變數 = (rand()%n); //變數隨機取數0~(n-1)  

  


