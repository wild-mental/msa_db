# MSA 애플리케이션 EKS 배포 예제를 위한 MySQL DB 컨테이너 이미지
- Docker Hub 이미지 Repo : https://hub.docker.com/r/makersworld/msa-db-mysql8/tags

# 이미지 실행 커맨드
- Mac : `docker run --name msa-db -p 12345:3306 makersworld/msa-db-mysql8:arm64`
- Win : `docker run --name msa-db -p 12345:3306 makersworld/msa-db-mysql8:amd64`

# MySQL 접속
- 환경에 맞추어 DBHOST 설정 (127.0.0.0)
- 초기 유저 및 비밀번호 : root/12341234
- 접속 커맨드 : mysql -h DBHOST -P 12345 -u root -p12341234
