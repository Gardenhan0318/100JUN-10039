# 100JUN-10039
STUDY
#include<stdio.h>

int main() {

    int score = 0;//점수
    int sum = 0;  //총합
    int mean = 0; //평균
    int i;


    for (int i = 1; i <= 5; i++) {//학생1~5까지의 점수 입력
        scanf_s("%d", &score);//scanf_s를 쓴 이유는 #define _CRT_SECURE_NO_WARNINGS 안 쓰기 위해서
        if (score < 40)
            score = 40;
        sum += score;
    }
    mean = sum / 5;
    printf("%d", mean);
}
	
		int avg = (score1 + score2 + score3 + score4 + score5) / 5;
		printf("학생 평균의 점수:%d", avg);

	
	return 0;

}
