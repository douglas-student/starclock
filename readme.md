# 🚀 Projeto: Relógio Atômico com Docker e Apache

Este projeto exibe uma página web que apresenta um **Hello World**, um **relógio atômico** baseado no horário UTC (Tempo Universal Coordenado), e um **background animado com estrelas em movimento**, simulando o espaço sideral. A aplicação é executada em um container Docker utilizando o servidor Apache.

## 📋 Funcionalidades

- Exibição do texto **Hello World**.
- Relógio digital em tempo real com horário **UTC** (usado por astronautas e sistemas globais).
- Animação de fundo com estrelas que se movem como se fosse o espaço.
- Servido por um servidor Apache configurado via Docker Compose.

## 🛠️ Tecnologias Utilizadas

- **HTML5**
- **CSS3** (com animação de estrelas)
- **JavaScript** (para atualização do relógio em tempo real)
- **Docker** e **Docker Compose**
- **Servidor Apache (httpd)**

## 📁 Estrutura do Projeto

```plaintext
docker-apache-project/
├── docker-compose.yml    # Configuração do Docker Compose
├── html/
│   └── index.html        # Página HTML com o relógio e animação
└── .gitignore            # Arquivos ignorados pelo Git
```

## 🚀 Como Rodar o Projeto

1. **Pré-requisitos**:
   - Ter o Docker e o Docker Compose instalados.

2. **Clonar o Repositório**:
   ```bash
   git clone https://github.com/SEU_USUARIO/docker-apache-project.git
   cd docker-apache-project
   ```

3. **Executar o Docker Compose**:
   ```bash
   docker-compose up
   ```

4. **Acessar a Aplicação**:
   - Abra o navegador e acesse `http://localhost:8080`.

## 🌌 Demonstração

- **Hello World**: Exibido na parte superior da página.
- **Relógio Atômico**: Um relógio digital atualizado em tempo real com o horário UTC.
- **Background Animado**: Fundo com estrelas em movimento, simulando o espaço.

![Demonstração](https://via.placeholder.com/800x400?text=Preview+do+Projeto)

## 📝 Personalização

Você pode personalizar o projeto:
- Alterando o estilo do relógio no arquivo `index.html`.
- Adicionando mais elementos HTML ou interatividade com JavaScript.
- Modificando a animação das estrelas.

## 🖥️ Contribuindo

Contribuições são bem-vindas! Siga os passos abaixo para colaborar:
1. Faça um fork do repositório.
2. Crie uma nova branch para suas alterações:
   ```bash
   git checkout -b minha-feature
   ```
3. Commit suas alterações:
   ```bash
   git commit -m "Adicionei uma nova feature"
   ```
4. Envie para o repositório:
   ```bash
   git push origin minha-feature
   ```
5. Abra um Pull Request.

## 📜 Licença

Este projeto é de código aberto e está sob a licença [MIT](https://opensource.org/licenses/MIT).

---

Feito com ❤️ por [Douglas Fiedler](https://github.com/douglas-student). ✨
