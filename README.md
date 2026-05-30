<div align="center">
  <img src="img1.jpeg" width="150" alt="Logo Autensense" />
  
  <h1>Autensense</h1>
</div>

<p>
  O AutenSense é um sistema web desenvolvido para auxiliar pessoas com Transtorno do Espectro Autista, familiares e cuidadores a encontrarem ambientes mais adequados sensorialmente. A plataforma permite visualizar locais mapeados na cidade de Manaus, consultar níveis de estímulos como ruído, iluminação e fluxo de pessoas, além de utiliza tecnologia e geolocalização para permitir realizar avaliações colaborativas.
</p>

<img width="1338" height="897" alt="image" src="img2.jpeg" />
<img width="1338" height="897" alt="image" src="img3.jpeg" />

---
## 💡Sobre o Projeto - Proposta
As barreiras invisíveis e as dificuldades enfrentadas por pessoas com TEA, devido à intensidade e imprevisibilidade dos estímulos urbanos, se tornou cada vez mais notavel com o passar dos anos. Propor a criação de uma plataforma digital interativa destinada à avaliação da percepção sensorial em ambientes urbanos foi uma ideia viavel para resolver essa situação. Ela apoia as famílias e os próprios usuários neurodivergentes no planejamento de suas rotinas e atividades diárias, garantindo maior previsibilidade, segurança, inclusão social e qualidade de vida na cidade. Sendo uns dos seus objetivos:
- Mapear a previsibilidade urbana através de dados colaborativos sobre ruído, iluminação e fluxo de pessoas.  
- Promover a autonomia e segurança de indivíduos neurodivergentes e suas famílias no planejamento de rotinas diárias

---
## 📄Funcionalidades
- Mapa Interativo com Geolocalização: Exibição geográfica em tempo real dos locais urbanos cadastrados e facilidade de buscar/localizar ambientes próximos.
- Avaliação Sensorial Colaborativa: Mecanismo para registrar avaliações e compartilhar experiências sobre os locais com base em critérios como níveis de ruído, iluminação e fluxo de pessoas.
- Filtros e Classificação Sensorial: Aplicação de filtros baseados em características sensoriais e visualização de um ranking que classifica os ambientes com base no conforto que oferecem.
- Perfil Sensorial Personalizado: Criação e configuração de perfis específicos focados nas necessidades e preferências de cada usuário.

---
## 🎞️Demonstração

---
## 💻 Tecnologias Utilizadas

| Camada | Tecnologia | Motivo |
| :--- | :--- | :--- |
| **Front-End** | HTML5, CSS3, JavaScript e Leaflet | Utilizados para construir a estrutura semântica, a estilização responsiva e a interatividade da interface. A biblioteca Leaflet é empregada especificamente para integrar os serviços de geolocalização e renderizar o mapa interativo. |
| **Back-End** | PHP | Responsável pelo processamento de todas as regras de negócio do sistema, gerenciamento das requisições web e pela integração segura entre a interface e a camada de dados. |
| **Banco de Dados** | MySQL | Atua como o Sistema Gerenciador de Banco de Dados (SGBD) relacional, garantindo o armazenamento estruturado, a persistência e a integridade de dados complexos (como tabelas de usuários, locais e avaliações). |
| **Servidor** | Apache (via XAMPP) | O Apache é utilizado como o servidor web local para interpretar os scripts em PHP e intermediar a comunicação com o banco de dados durante o ambiente de desenvolvimento e testes. |
| **Deploy** |  |  |

---
## 🗂️Estrutura de Pastas
```
🗂️AUTENSENSETCC2/
│
├── 📁backend/
│   ├── 📁data/
│   │   ├── 📄avaliacoes.json
│   │   ├── 📄favoritos.json
│   │   ├── 📄perfis.json
│   │   └── 📄users.json
│   │
│   ├── 📁node_modules/
│   ├── 📄init.sql
│   ├── 📄package.json
│   ├── 📄package-lock.json
│   └── 📄server.js
│
├── 📄index.html
├── 📄style.css
├── 📄app.js
│
├── 📁imagens do sistema
│   ├── 📄hero.jpg
│   ├── 📄iconeLogo.png
│   ├── 📄ambienteSilencioso.jpg
│   ├── 📄baixoRuido.jpg
│   ├── 📄bibliotecaTranquila.jpg
│   ├── 📄cafeteria.jpg
│   └── 📄outras imagens dos locais
```

---
## 🔎Como Executar
### Pré-requisitos:
```
* XAMPP instalado
* Apache e MySQL ativados no XAMPP
* Navegador web
* phpMyAdmin para importar o banco de dados
````
### Instalação:
```
1. Baixar ou clonar o repositório do projeto.
2. Copiar a pasta autensenseTCC para C:\xampp\htdocs.
3. Abrir o XAMPP e iniciar Apache e MySQL.
4. Acessar o phpMyAdmin em http://localhost/phpmyadmin.
5. Criar ou importar o banco autensense_db.
6. Verificar se o arquivo backend/configg/conexao.php está apontando para o banco correto.
7. Abrir o sistema no navegador pelo link:
   http://localhost/autensenseTCC/index.html
```
### Para teste externo:
Usamos ngrok com o comando:
```
ngrok http 80
```
---
## 👤 Autores
| Nome | GitHub | E-mail |
| :--- | :--- | :--- |
| Cibely da Silva Dácio |[@usuário](https://github.com/usuario) | [cibely16dacio@gmail.com](mailto:cibely16dacio@gmail.com) |
| Enderson Conceição Lopes | [@usuário](https://github.com/usuario)  | [enderson10lopes@gmail.com](mailto:enderson10lopes@gmail.com) |
| Glenda Nayara Hipi de Almeida | [@usuário](https://github.com/usuario)  | [glendalmeida18@gmail.com](mailto:glendalmeida18@gmail.com) |
| Haugley Heber de Castro Marques | [@usuário](https://github.com/usuario)  | [castrohaugley17@gmail.com](mailto:castrohaugley17@gmail.com) |
| Naille Maria Batista Medeiros | [@usuário](https://github.com/usuario)  | [naillemaria@gmail.com](mailto:naillemaria@gmail.com) |
