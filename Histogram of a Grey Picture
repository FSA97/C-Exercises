#include <stdio.h>
#include <time.h>
#include <stdlib.h>
#define row 100
#define column 100
#define colors 256


int main(){
	int A[row][column];int N,M;
	printf("row & column: ");scanf("%d%d",&N,&M);
	
	/*                                  //Input from keyboard
	for(int i = 0; i < N; i++){
		for(int j = 0; j < M; j++){
			printf("A[%d][%d]",i+1,j+1);scanf("%d",&A[i][j]);
		}
	}
	*/
	
	for(int i = 0; i < N; i++){
		for(int j = 0; j < M; j++){
			A[i][j] = rand()%256;
		}
	}
	
	int histogram[colors];
	for(int i = 0; i < N; i++){
		for(int j = 0; j < M; j++){
			histogram[A[i][j]]++;
		}
	}
	
	for(int i = 0; i < colors;i++){
		printf("%5d - ",i);
		for(int j = 0; j < histogram[i]; j++){
			printf("*");
		}
		printf("\n");
	}



return 0;	
}



