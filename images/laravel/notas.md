Para criar uma imagem com base do Dockerfile:
    docker build -t alexsousa/laravel:latest .

Para criar um container com base na imagem:
    docker run --rm --name laravel -p 8080:8000 alexsousa/laravel