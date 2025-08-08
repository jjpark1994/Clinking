# Clinking
현재까지 Log 함수를 만들었습니다.

예를 들어 Log.c Log.h main.c 3개의 파일을 이용하여, 실행파일을 만들었고,
실행파일을 실행하여 
로그 함수가 잘 작동 하는지 확인 하였습니다.


이제는 Log.c + Log.h 들을 오브젝트파일(확장자명 + .o) Log.o로 만들고 
ex)gcc -c Log.c

main.c도 오브젝트 파일(main.o) 로 만든 다음 만들어진 log.o main.o를 이용 하여 실행 파일을 만들어봅시다


과제.. 
A.c 파일에 함수 intA() {B(); return 0}
B.c 파일에 함수 intB() {C(); return 0}
C.c 파일에 함수 intC() {A(); return 0}
main.c 파일 함수 int main (){A(); return 0;)

main.out 을 실행
