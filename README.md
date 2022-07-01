# myHomeP
# 출저 나무위키 피파온라인4
https://namu.wiki/w/%ED%94%BC%ED%8C%8C%20%EC%98%A8%EB%9D%BC%EC%9D%B8%204

# 실행화면
![homeP10](https://user-images.githubusercontent.com/104752580/176826926-e9650e4e-79a4-47f6-81c9-3a2c99c4a87d.JPG)
![homeP11](https://user-images.githubusercontent.com/104752580/176826931-43c96dd6-b2f4-49bc-b215-9b4112c0d5cc.JPG)
![homeP12](https://user-images.githubusercontent.com/104752580/176826933-390a86cb-fee7-4e4a-a1bd-d86f2bf302d1.JPG)

# 홈페이지 만들기
![homeP3](https://user-images.githubusercontent.com/104752580/176815730-16051e88-d8d4-4969-a9a5-fdf194f58046.JPG)

css와 js를 연결시겨주고 jquery를 1.12.4 버전으로 설정하는 코드 입니다.

![homeP1](https://user-images.githubusercontent.com/104752580/176815936-e50d7b92-3144-4c30-a23d-9504716f5910.JPG)
![homeP2](https://user-images.githubusercontent.com/104752580/176815940-2324d4bb-b9e0-4fe7-a8ad-d628b7d9ea2d.JPG)

div 태그를 이용하여 위치를 정해주고 class를 선언합니다.

링크를 연결시켜주는 a태그 안에는 게임 정보에 대한 나무위키 링크를 설정합니다. 그리고 다른 html 파일을 연동시켜줍니다.

iframe 이라는 태그를 이용해 동영상 플에이어를 삽입했습니다.

# css
![homeP4](https://user-images.githubusercontent.com/104752580/176816545-d11ec3b1-d0b2-42e4-9914-b0d336bd4d8a.JPG)
![homeP5](https://user-images.githubusercontent.com/104752580/176816547-0843df92-6296-42c6-aec6-7a612cc88c8a.JPG)
![homeP6](https://user-images.githubusercontent.com/104752580/176816553-4594baea-0db2-4c6a-9564-93277b1459d1.JPG)

css 전체 바탕색을 검정색으로 설정하고 li 태그에 스타일을 제거해 줬습니다.

clear 클래스에는 cear : both를 통해서 float 속성을 지정하지 않은 속성들만 float 아래에 존재하게 했습니다.

imgs 클래스에 overflow:hidden 속성을 이용해 가로 1000 세로 220이 넘어가면 안보이게 했습니다.

imgs>img 클래스는 transition을 통해서 애니메이션 속도를 0초로 지정했습니다.

# js
![homeP7](https://user-images.githubusercontent.com/104752580/176817384-2b0e259a-4707-43bb-8fb5-f8eb785d065e.JPG)

start 함수로 코드를 실행하게 했습니다.

변수 imgs를 5, now를 0으로 설정해줬습니다.

.imgs>img의 0번째부터 5번째까지 슬라이드를 2초동안 보여주고 왼쪽으로 넘어가며 다음 img가 보이는 코드를 만들어 줬습니다. 하지만 제가 css에서 슬라이드를 0초로 지정해 놓았기 때문에 바로 넘어갑니다.

slide 함수로 이미지가 0번째부터 5번째까지 img를 순서대로 반복시키는 코드를 만들어 줬습니다.

# 추가 html
![homeP8](https://user-images.githubusercontent.com/104752580/176826082-8b54b389-024b-4d46-951a-67d56024709e.JPG)
![homeP9](https://user-images.githubusercontent.com/104752580/176826088-910787c5-7bcc-447b-a1a9-99167cce4348.JPG)

다운로드.html에는 다운로드를 받을 수 있는 버튼을 만들어 버튼을 클릭하면 다운로드가 되었습니다. 홈으로 돌아가 주세요 라는 메세지가 나오게 만들었고,
홈으로 돌아가기 글씨를 홈페이지로 돌아갈 수 있는 링크를 걸었습니다.

로그인.html에는 id와 password를 입력하는 로그인 창을 만든후 확인을 누르면 로그인이 되었습니다. 홈으로 돌아가 주세요 라는 메세지가 나오게 만들었고,
홈으로 돌아가기 링크를 걸었습니다.



