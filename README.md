# Monte Horebe Coworking 🏢

Projeto desenvolvido para o **Monte Horebe Coworking**, com o objetivo de criar um site institucional para apresentar o espaço, suas salas e serviços.

## 💻 Sobre o projeto

O site conta com páginas para apresentar:

* 🏠 Página inicial
* 🏢 Salas disponíveis
* ⭐ Avaliações
* ❓ Perguntas frequentes
* 📍 Localização

As informações das salas são carregadas de forma dinâmica por meio de uma API, com as imagens armazenadas na AWS S3.

## 🛠️ Tecnologias

* HTML5
* CSS3
* JavaScript
* AWS S3
* AWS SDK
* Fetch API

## 📂 Estrutura

```text
coworking-space/
├── api/
├── assets/
├── css/
├── images/
├── js/
├── avaliacoes.html
├── faq.html
├── index.html
├── localizacao.html
└── salas.html
```

## ▶️ Como executar

Para executar o projeto localmente, utilize um servidor HTTP. Com Python:

```bash
python -m http.server 8000
```

Depois, acesse:

```text
http://localhost:8000
```

## 📚 Projeto acadêmico

Este projeto foi desenvolvido como parte das atividades da graduação em **Engenharia de Software**, colocando em prática conceitos de desenvolvimento web.

---
