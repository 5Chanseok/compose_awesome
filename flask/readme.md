# 파일 구조
flask
L readme.md
L app
    L Dockerfile            # flask 컨테이너 이미지를 기술한 파일
    L app.py                # flask의 엔트리포인트
    L requirements.txt      # flask 구동을 위한 패키지 설치 파일
L docker-compose.yml        # 컴포즈 파일 (호환된다 compose.yml)