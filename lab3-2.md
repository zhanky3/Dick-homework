# a
a
#include<stdio.h>
int main(){
		int n=0;
		scanf("%d",&n);
		int flag=0;
	    int result[100];
	    for(int i=0;n!=0;i++){
	    	result[i]=n%16;
	    	n=n/16;
			flag++; 
	    	
		}
		int nothing;
	for(int i=flag-1;i>=0;i--)	{
		if(result[i]>=10){
		  switch(result[i]){
		  case 10:printf("A");break;
		  case 11:printf("B");break;
		  case 12:printf("C");break;
		  case 13:printf("D");break;
		  case 14:printf("E");break;
		  case 15:printf("F");break;
		  case 16:printf("G");break;
		  default:;	
		    }
       }
       else printf("%d",result[i]);
	}
	printf("\n");
	
		
		
		
	return 0;	
		
	}
 