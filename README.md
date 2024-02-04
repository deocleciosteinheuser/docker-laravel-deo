# Crie o projeto laravel
docker run --rm -v $(pwd):/app composer create-project --prefer-dist laravel/laravel nome-do-projeto
# Carregar as configurações do projeto
<code>git clone https://github.com/deocleciosteinheuser/docker-laravel-deo.git projeto-nome/docher</code>
# Copiar as comfigurações para a raiz
copy-item fidex/docker/* fidex
# Abra a raiz do pojeto
cd projeto-nome
# Criar e executar a imagem docker 
docker-compose up -d --build
# Acessar o projeto
http://localhost:8080/
