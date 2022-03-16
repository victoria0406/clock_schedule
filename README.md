# clock schedule
### 목적
기존에 내가 사용하던 스케쥴표들은 균일하지 못한 색상과 좋지 못한 비주얼을 가지고 있었다. 따라서 조금 더 보기 좋고, 깔끔한 스케쥴어플을 만들되, 시계라를 만들어 좀 더 새로움을 더하고 싶었다. 

### 목표
1. 데이타베이스 구조 수업의 첫번째 과제와 연동시켜, JDBS를 활용하자. 
2. 최소한의 액티비티를 사용하여, 실제 사용하게 만들어 보자. 
3. 혼자 하는 프로젝트이지만, sw process model을 적용시켜, 조금 더 계획적이고 효율적인 프로젝트를 진행해보자.
4. 실사용이 목표이므로, 배터리 사용량이나 전환 속도등을 고려하자. 
5. 안드로이드의 life cycle을 이해하자. 

### UI 디자인  
![image](https://user-images.githubusercontent.com/81007362/158601258-9e99b6c8-6f60-4f9b-89c6-fd595e85a223.png)
### 테마 색상  
<p align="center"><img src="https://user-images.githubusercontent.com/81007362/158588858-4e23401f-da95-4175-b797-723524c81461.png"></p>


특징
1. 시계는 바늘은 가만히 있고, 원판이 회전한다. 이 때, 해당 일과 시간은 자유시간을 제외하고는 흰빛을 약간 넣는다. 
2. 잠금화면의 지난 일과, 다음일은 스와이프로 넘긴다. 이 때, 껐다가 키면 다시 돌아온다. 
3. 각각의 요일 일과를 보는 것은 스와이프로 구현한다. (카드 넘어가듯)

### 구현 과정
1. 구현 시 주의사항
  어짜피 내 어플이므로, 1시부터 7시까지는 강제 종료할 방법을 찾자(배터리 위해서), 앱 잠금 기능으로 수업 중 집중을 더해주자
2. 구현 순서
  1) 프론트엔드 구현(java, android studio)
  2) db 구현(JDBS)


### 참고자료
앱 잠금 기능 구현 https://stickode.tistory.com/121
