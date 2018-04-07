# FaceCountingCCTV
openCV를 이용해서 사람의 얼굴인 인식 후에 카운팅을 하는 CCTV 이다. </br>
물론 이름은 CCTV 이지만 CCTV의 용도 외에도 다른 곳에 사용이 가능하며, 오픈 소스로 되어 있기 때문에 다른 혹시 자신이 원하는 부분을 고칠수도 있다. </br>

# 간단한 파일 설명 
CCTV-Code.py가 바로 주 메인 코드이자 유일하게 실행이 될 코드이다. 📂 </br>
CCTV-Code.py의 코드는 insung3511의 OpenCV_Face_detection_code를 참고하여 제작이 되었다. </br>
>>> <a href="https://github.com/insung3511/OpenCV_Face_detection_code"> 🗃OpenCV_Face_detection_code 🗃 </a> <<< </br>
</br>
CCTV-Code.py만 있어서는 실행이 안된다. 컴퓨터가 얼굴을 인식해주기 위해서는 haarcascade_frontalface_default.xml 라는 파일이 있어야만 한다.</br>
얼굴인식의 기준은 사람의 눈과 그리고 전체적인 형태인데, 이거는 CCTV-Code.py 자체에 담기에는 힘들기도하고 코드길이가 너무나도 늘어나 따로 파일 저장하기로 선택을 했다.</br>


