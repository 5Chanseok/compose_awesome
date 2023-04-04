# 베이스 이미지
FROM nginx

# 설정 파일 이동
# 기존 파일이 존재하는데, 새로운 파일을 덮어 처리되는지 체크 --> docker client proxy terminal에서 체크 완료
COPY config /etc/nginx/conf.d/default.conf
