<img src = "docs/imgs/torch_logo.png" alt = "Logo Torch" width = "350">

---

# Página de Redirecionamento 🐾

Página de redirecionamento para o deep link no Torch.<br>
O repositório do Frontend está disponível [aqui.](https://github.com/VStorch/TorchApp)<br>
O repositório do backend está disponível [aqui.](https://github.com/VStorch/TorchAppBackend)<br>
Os diagramas de arquitetura e banco de dados estão disponíveis na documentação do software.

---

### Índice

- [Descrição](#descrição)
- [Funcionalidade](#funcionalidade)
- [Como Funciona](#como-funciona)
- [Tecnologias e Dependências](#tecnologias-e-dependências)
- [Desenvolvedores](#desenvolvedores)
- [Vídeo de Demonstração](#vídeo-de-demonstração)
- [Documentação do Software](#documentação-do-software)
- [Status do projeto](#status-do-projeto)

---

### Descrição

O Torch é um aplicativo móvel desenvolvido para facilitar o agendamento de horários em Pet Shops. Com uma interface intuitiva, o app permite que os usuários agendem rapidamente serviços para seus animais de estimação, enquanto os Pet Shops podem gerenciar seus horários de forma eficiente. O objetivo é proporcionar agilidade tanto para os clientes quanto para os fornecedores de serviços.

---

### Funcionalidade

1. Deep Link para redefinição de senha

    - Quando o usuário acessar o link de redefinição de senha, a página irá capturar os parâmetros **token** e **email**  da URL e tentar abrir com o link correspondente.

2. Fallback para o caso de falha

    - Se o app não estiver instalado ou o deep link não funcionar, o usuário será redirecionado automaticamente para a URL de fallback, no caso o repositório do frontend.

---

### Como Funciona

1. O Backend gera um token e manda ele por email junto com o link para esta página: https://vstorch.github.io/PaginaRedirecionamento

2. Ao acessar o link, o JavaScript extrai os parâmetros da URL (token e email).

3. A página tenta abrir o aplicativo por meio de um deep link customizado.

4. O sistema operacional (Android) identifica o app associado e abre diretamente na tela de redefinição de senha.

5. Caso o aplicativo não esteja instalado, o usuário é redirecionado automaticamente para uma página de fallback.

---

### Tecnologias e Dependências

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23F7DF1E.svg?style=for-the-badge&logo=javascript&logoColor=black)

- HTML5
- CSS
- JavaScript

---

### Desenvolvedores

- [João Pedro Pitz](https://github.com/joaopedropitzz)
- [Leonardo Cortelim dos Santos](https://github.com/LeonardoCortelim)
- [Vinícius Storch](https://github.com/VStorch)

---

### Vídeo de Demonstração

<p align="center">
  <a href="https://www.youtube.com/watch?v=xfTUIMbSeD0" target="_blank">
    <img src="https://img.youtube.com/vi/xfTUIMbSeD0/maxresdefault.jpg" 
         alt="Vídeo de Demonstração Torch"
         width="700">
  </a>
</p>

<p align="center">Clique na imagem para assistir no YouTube</p>
<p align="center">
  <sub>Vídeo sem áudio • gravação por Leonardo Cortelim dos Santos</sub>
</p>

---

### Documentação do Software

Acesse a documentação em: [Torch](https://docs.google.com/document/d/1rGbcGYY655Smcz7teA9VlWOLTOMnTLguNPUWll94FlI/edit?tab=t.0)

---

### Status do projeto

Projeto concluído para fins acadêmicos, com possibilidade de evolução futura. 