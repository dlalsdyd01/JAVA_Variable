# JAVA_Variable  


  
## ✅ 변수란? 데이터를 저장할 수 있는 메모리 공간에 붙여진 이름  
  
int : 정수  
  
float,double : 실수 
  
char : 문자 하나  
  
boolean : 논리값 (참/거짓)  
  
String : 문자열  
  

예제  
```
public class DataTypeExample {
    public static void main(String[] args) {
        // 정수형 (int)
        int age = 25;

        // 실수형 (double)
        double height = 173.5;

        // 문자형 (char)
        char grade = 'A';

        // 논리형 (boolean)
        boolean isStudent = true;

        // 문자열 (String)
        String name = "이민용";

        // 출력
        System.out.println("이름: " + name);
        System.out.println("나이: " + age);
        System.out.println("키: " + height + "cm");
        System.out.println("등급: " + grade);
        System.out.println("학생 여부: " + isStudent);
    }
}
```

int는 4바이트로, 약 ±21억의 표현범위를 가진다.  
long은 8바이트로, 그보다 크거나 작다. 자료형으로 사용할 때 숫자뒤에L을 붙인다.  

  
float와 double은 모두 실수를 저장할 수 있는 자료형이지만, 정밀도와 크기에서 차이가 있다.  
double은 8바이트로, 소수점 약 15-16자리 정확도  
float는 4바이트로, 소수점 약 6-7자리 정확도  


## ✅ 변수 이름 짓는 법  
  
저장할 값에 어울리는 이름  
  
밑줄, 문자, 숫자 사용 가능  
  
밑줄 또는 문자로 시작 가능  
  
한 단어 또는 2개 이상 단어의 연속  
  
소문자로 시작, 각 단어의 시작 글자는 대문자  
  
예약거 사용 불가 (public, static, void...)  
  
  
## ✅ 상수란? 한 번 정해지면 절대로 변하지 않는 값"을 저장하는 메모리 공간
```
final 자료형 상수이름 = 값;
```
예) PI, E, GRAVITY


