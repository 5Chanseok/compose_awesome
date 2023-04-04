# 베이스 이미지
FROM ubuntu

# 압축해제 후 추가
ADD web.tar /home/

# URL 다운로드
ADD https://raw.githubusercontent.com/ultralytics/yolov5/master/requirements.txt /home/requirements.txt

# 파일 추가, 이름을 바꿔서 넣어보기
ADD readme.md /home/readme2.md

# 특정 이름으로 시작하는 모든 파일(패턴 지정) 추가
ADD po*.txt /home/

# 특정 이름 + 한 글자로 시작하는 모든 파일을 추가
ADD po?.txt /home/