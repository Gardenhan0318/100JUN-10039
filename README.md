# 100JUN-10039
STUDY
#define _CRT_SECURE_NO_WARNINGS
#include <stdio.h> 

int main(void) {
	int score1, score2, score3, score4, score5; //학생의 점수 변수 설정
	score1 = 0; 
	score2 = 0;
	score3 = 0;
	score4 = 0;
	score5 = 0; //학생의 점수 변수 설정


		printf("원섭의 점수:");
		scanf("%d", &score1);

		printf("세희의 점수:");
		scanf("%d", &score2);

		printf("상근의 점수:");
		scanf("%d", &score3);

		printf("숭의 점수:");
		scanf("%d", &score4);

		printf("강수의 점수:");
		scanf("%d", &score5);

		if (score1 < 40, score4 < 40) { //원섭과 숭의 점수는 40미만
			score1 =40, score4 =40; // 원섭과 숭의 점수는 40으로 취급
		}

		
	
		int avg = (score1 + score2 + score3 + score4 + score5) / 5;
		printf("학생 평균의 점수:%d", avg);

	
	return 0;

}
