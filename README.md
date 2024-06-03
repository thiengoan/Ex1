# Ex1
Tạo 1 đường mạng docker
192.168.100.0/24 với gateway là 192.168.100.1
Tạo docker file chạy web laravel
docker network create \ --driver=bridge \ --subnet=192.168.100.0/24 \ --ip-range=192.168.100.0/24 \ --gateway=192.168.100.1 \ studydocker
