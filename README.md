# 20200608
1.디자이너 파트
> 1 수평배치1 = 출발지 입력

>2 수평배치2=  도착지 입력

>3 수평배치3= 길찾기,지우기버튼

>4 액티비티스타터
>>-동작
>>:android.intent.action.VIEW
>>-액티비티클래스
>>:com.google.android.maps.MapsAct
>>ivity 
>>-액티비티패키지
>>:com.google.android.apps.maps

2.블록코딩
> -전역변수 ‘출발지’,’도착지’ 선언

>-‘출발’함수 : 출발지의 택스트를 결합
>https://www.google.co/kr/maps/dir
>+ 택스트_출발의 택스트값
>(/dir = google maps의 길찾기 기능
> dir”출발지” / “도착지” = 경로검색)

>-‘도착’함수 : 도착지의 택스트를 결합
>/ + 택스트_도착의 택스트값

>-버튼_길찾기 클릭 시
>‘출발’+’도착’ 함수 호출
>두 개의 함수의 택스트값을 합친 후
>데이터URI값에 저장
>액티비티 시작

>-버튼_지우기  클릭 시
>입력했던 출발지와 도착지의 택스트를
>초기화

