# Passo a passo para execução do código:

### 1. Instalar o [WampServer](https://www.wampserver.com/en/)

Baixar e instalar o WampServer.

### 2. Colocar o código baixado na pasta ***wamp64/www***

![passo2](https://i.ibb.co/2PzXyNr/Capturar2.png)

### 3. Entrar em ***localhost*** no browser
Ao entrar em 'localhost' pelo browser, clica na opção **"Adicionar Virtual Host"**

![passo3](https://i.ibb.co/PMTRsBx/image.png)

### 4. Adicionar o path da aplicação no segundo campo

Obs: No caso abaixo, a pasta do ***Wampserver*** está no Disco Local (C:)

![passo4](https://i.ibb.co/5GdWSf4/image.png)

Após adicionar o campo, clicar "Iniciar a criação do VirtualHost"

### 5. Depois de criar, reiniciar DNS O Wampserver

![passo5](https://i.ibb.co/q91LmCg/image.png)

### 6. Voltando ao 'localhost' no browser, entrar na Ferramenta 'phpMyAdmin'

![passo6](https://i.ibb.co/ZgB5g5y/image.png)

### 7. Fazer login no 'phpMyAdmin' 


Username: *root*

Senha: *DEIXAR VAZIO*


![passo7](https://i.ibb.co/MPXQSXx/image.png)

### 8. Ir na pasta 'SQL' e adicionar o código do arquivo ***ellisdev.sql***

Depois de adicionar, clicar em 'Executar' para criar o banco de dados e a tabela.

![passo8](https://i.ibb.co/K9dMyKS/capturar1.png)

### 9. Acessar a URL 'localhost/EllisDev/codeIgniter/index.php' !!!

