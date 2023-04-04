FROM ubuntu

# 사이트가 잘 동작하는지 체크만 하는 용도의 명령어 수행
# 30초 간격으로 특정 사이트 접속 체크, 응답 지연은 30초 이내에 들어올 때 까지는 오류없음
HEALTHCHECK --interval=30s --timeout=30s CMD [ "curl", "-f", "http://127.0.0.1", "||", "exit 1" ]

# DB 체크 예시
# HEALTHCHECK --interval=30s --timeout=30s CMD [ "mysqladmin", "ping","-h", "127.0.0.1", "--password=1234", "--silent" ]