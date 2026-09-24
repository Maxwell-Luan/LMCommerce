# LMCommerce

[![NPM](https://img.shields.io/npm/l/react)](https://github.com/Maxwell-Luan/LMCommerce/blob/main/LICENSE) 

# Sobre o projeto

LMCommerce é uma aplicação full stack web e mobile construída com fundamentos base em Java / Spring no back-end e React / TypeScript no front-end.

A aplicação consiste em um e-commerce completo, com um catálogo de produtos, login de usuário para efetuar compras em perfil de cliente e perfil administrativo para cadastrar, alterar, atualizar e excluir produtos.

## Layout web
![Web 1](https://github.com/Maxwell-Luan/LMCommerce/blob/main/assets/catalogo.png)
![Web 2](https://github.com/Maxwell-Luan/LMCommerce/blob/main/assets/carrinho.png)
![Web 3](https://github.com/Maxwell-Luan/LMCommerce/blob/main/assets/area_administrativa.png)
![Web 4](https://github.com/Maxwell-Luan/LMCommerce/blob/main/assets/cadastro_produto.png)

## Layout mobile

<p align="center">
  <img src="https://github.com/Maxwell-Luan/LMCommerce/blob/main/assets/catalogo_mobile.png" alt="Mobile 1" width="300"/>
  <img src="https://github.com/Maxwell-Luan/LMCommerce/blob/main/assets/carrinho_mobile.png" alt="Mobile 2" width="300"/>
</p>
<p align="center">
  <img src="https://github.com/Maxwell-Luan/LMCommerce/blob/main/assets/area_administrativa_mobile.png" alt="Mobile 3" width="300"/>
  <img src="https://github.com/Maxwell-Luan/LMCommerce/blob/main/assets/cadastro_produto_mobile.png" alt="Mobile 4" width="300"/>
</p>

## Modelo conceitual
![Modelo Conceitual](https://github.com/Maxwell-Luan/LMCommerce/blob/main/assets/modelo_conceitual.png)

# Tecnologias utilizadas
## Back end
- Java
- Spring Boot
- JPA / Hibernate
- Maven
## Front end
- HTML
- CSS
- TypeScript
- ReactJS
- Yarn
## Implantação em produção
- Back-end: Railway
- Front-end web: Netlify
- Banco de dados: PostgreSql
- Containerização: Docker
## Competências gerais
- Front-end responsivo
- Layout back-end em camadas
- React Router DOM para navegação entre telas
- Spring security com autenticação em token JWT
- Controle de acesso por perfil de usuário
- Manipulação do local storage do navegador
- Testes em ambiente de produção, teste e desenvolvimento
- ORM
- Validação de dados
- JPQL
- API Rest
- Criação de containers e imagens com Docker
## Agradecimentos
  A realização desse projeto só foi possível graças aos aprendizados adquiridos através do professor Nélio Alves(https://www.linkedin.com/in/nelio-alves/) e a plataforma de ensino DevSuperior (https://devsuperior.club/).


# Como executar o projeto

Você pode executar a aplicação completa (Back-end, Front-end e Banco de Dados PostgreSQL) utilizando o **Docker Compose**, sem a necessidade de instalar Java, Node.js ou PostgreSQL localmente.

### 📋 Pré-requisitos
- **[Docker Desktop](https://www.docker.com/)** instalado **e em execução** na sua máquina.

### 🏃 Passo a Passo rodando com Docker (Recomendado)

1. **Abra o Docker Desktop** no seu computador e aguarde até que o status indique que o serviço está ativo (*Engine running*).

2. **Clone o repositório:**
   ```bash
   git clone [https://github.com/Maxwell-Luan/LMCommerce.git](https://github.com/Maxwell-Luan/LMCommerce.git)
   
   cd LMCommerce
   ```
   
3. **Suba a aplicação**
   ```bash
   docker compose up -d --build
   ```
   
4. **Visualização e testes**
   ```bash
   Aguarde subir todos os serviços (PostgreSQL, Back-end e Front-end) com o comando anterior e acesse o frontend em: http://localhost

   Usuários padrão para teste de login:

   E-mail: alice@gmail.com
   Senha: 123456
   Roles: Cliente

   E-mail: luan@gmail.com
   Senha: 123456
   Roles: Cliente e Admin

# Autor

Luan Maxwell de Oliveira Santos

www.linkedin.com/in/luan-maxwell22194
