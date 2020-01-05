# FaceShield

학습을 위한 프로젝트<br>
FaceShield는 영상을 사용자가 업로드하면 자동으로 영상 속 사람의 얼굴을 탐지하여 블러처리를 해주는 얼굴 모자이크 웹서비스이다.
업로드 된 파이썬파일은 OpenCV, Posenet, FaceRecognition을 이용하여, 동영상 속 사람얼굴을 모두 찾아 블러링하는 '기본 기능'과 특정 인물의 사진을 넣으면 영상 속의 해당 특정 인물을 제외한 다른 인물들을 블러링하는 '고급기능'에 대한 코드이다.

<출처><br>
영상 속 사람 얼굴 탐지(Posenet : https://github.com/rwightman/posenet-python)<br>
특정 인물 제외하고 블러처리 기능(Face Recognition : https://github.com/ageitgey/face_recognition/blob/master/README.md)
