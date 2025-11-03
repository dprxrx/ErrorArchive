FROM nginx:1.25-alpine

# 작업 디렉토리 설정
WORKDIR /usr/share/nginx/html

# 모든 정적 리소스 복사
COPY . .

RUN chmod -R 755 /usr/share/nginx/html

# 포트 오픈
EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]