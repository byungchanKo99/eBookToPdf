# eBookToPdf
https://eastshine12.tistory.com/55
윗 분이 만든거에서 일부 수정하기
* 앞으로 더 수정해볼 것
- ui 개선
- pdf 생성 위치 설정
- 초반에 pdf 생성 시작했다는 걸 더 직관적으로 보여주기
- mac 실행파일로 만들기
<br /><br /><br />

# 설치방법
*mac 기준
1. poetry가 없다면 설치한다.   
   ```brew install poetry```
3. poetry 가상환경을 켠다.   
   ```poetry shell```
5. poetry 의존성을 설치한다.   
   ```poetry install```
6. 파일 실행   
   ```python eBookToPdf.py```

# 사용법
1. '좌표 위치 클릭' 버튼 클릭 후 캡처할 영역의 좌측상단, 우측하단 좌표를 구한다.
2. 총 페이지 수와 생성할 PDF 이름을 작성한다.
3. 다음 페이지를 넘겨보며 화면이 완전히 랜더링되는 시간을 참고하여 캡처 속도를 조절한다.
4. PDF로 만들기 클릭!
5. 이때 접근 권한을 요청한다면 승인하고 프로그램을 껏다 켠다.
6. 다시 PDF로 만들기 클릭!
7. 이때 아무 것도 안하고 가만히 있으면 조금 있다가 알아서 마우스 움직이고 캡처를 시작한다.
8. 캡처 이미지가 많아지면, PDF 변환 시간이 길어질 수 있으므로 잠시 기다린다.
9. 'PDF 변환 완료!'라는 문구가 뜨면 PDF 생성이 완료된 것이다.
10. PDF 파일은 실행 파일과 같은 경로에 생성된다.
<br /><br /><br />

# 사용 시 유의사항
1. 이미지 좌표 영역이 뷰어 영역을 벗어나면 안된다.
2. 반드시 키보드 오른쪽 방향키를 통해 다음 페이지 전환이 되어야 한다.
3. 페이지 수가 많을 경우 PDF 용량이 꽤 되므로 HDD 용량이 여유가 있어야 한다.
4. PDF 재생성 오류 시 프로그램을 재실행한다.
