# Week2 - 홈화면 만들기
---
__2022.10.02__   
1.  홈 화면 만들기 
    * Scaffold 로 appbar / body / bottomNavigationBar 구축
        * assets/font 디렉토리를 만들고 pubspec.yaml파일을 수정하여 폰트 적용 
    * body는 column 안에 children으로 container들을 배치하여 구현

2. 심부름 화면 만들기 
    * errand_list_screen을 추가
        * navigation.push() 함수를 이용하여 화면이동 구현


__2022.10.15__
1. column을 listview로 수정하여 스크롤이 가능하도록 변경
2. 개별적인 margin을 두지 않고 감싸는 listview 내부에 padding을 주어 간격통일성 맞춤  

__2022.10.16__  
1. 심부름 화면에 항목들 추가
    * 리스트뷰를 사용하여 스크롤이 가능하도록 함
2. appbar에 iconbutton을 이용해 뒤로가기 버튼 추가 