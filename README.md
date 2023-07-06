# Hospital-Managerment-Backend
## cài đặt CI và CD
Nhóm sử dụng Ci là GitHub Action và CD là Docker
- B1: tạo Docker file
- B2: tạo docker compose
- B3: tạo file auto.yml để thực hiện việc CI trong file .github/auto.yml
- B4: Tạo tài khoản và mật khẩu trên DockerHub trong phần Setting chọn Seceret, sau đó thêm file DOCKER_USERNAME VÀ DOCKER_PASSWORD 
- B5: chạy file trên docker hub
- B6: tiến hành pull imange về máy bằng câu lệnh docker pull tuzuka/backend:latest
- B7: tiến hành xây dựng container bằng câu lệnh docker port 8000 tuzuka/backend:latest
- B8: truy câp vào đường dẫn cửa container
- B9: trải nghiệm web
