# 🗣️ VIDA Project

## Voice, ID, Detection, Authentication

<div align="center">

![GitHub repo size](https://img.shields.io/github/repo-size/unb-mds/VIDAProject)
![GitHub language count](https://img.shields.io/github/languages/count/unb-mds/VIDAProject)
![GitHub top language](https://img.shields.io/github/languages/top/unb-mds/VIDAProject)
![GitHub](https://img.shields.io/github/license/unb-mds/VIDAProject)

_Revolucionando a autenticação através da biometria de voz_

[🚀 Demo](#demo) • [📋 Funcionalidades](#funcionalidades) • [⚡ Início Rápido](#início-rápido) • [🛠️ Tecnologias](#tecnologias) • [📚 Documentação](#documentação)

</div>

---

## 🎯 Sobre o Projeto

O **VIDA** é uma plataforma inovadora de autenticação biométrica baseada em reconhecimento de voz, desenvolvida com foco em **segurança**, **acessibilidade** e **inovação**. Utilizando tecnologias de ponta em Machine Learning e processamento de áudio, o sistema oferece uma alternativa moderna e segura aos métodos tradicionais de autenticação.

### ⬇️ Acesse nossa Landing Page pelo link abaixo

[https://unb-mds.github.io/VIDAProject/](https://unb-mds.github.io/VIDAProject/)

### 🌟 Por que VIDA?

- **🔒 Segurança Avançada**: Autenticação baseada em características únicas da voz
- **♿ Acessibilidade**: Interface inclusiva e fácil de usar
- **⚡ Performance**: Processamento em tempo real com alta precisão
- **🌐 Escalabilidade**: Arquitetura moderna preparada para crescimento
- **🔄 Confiabilidade**: Sistema robusto com validação contínua

---

## ✨ Funcionalidades

### 🎤 Reconhecimento de Voz

- Captura e processamento de áudio em tempo real
- Análise de características vocais únicas
- Algoritmos de ML para identificação precisa

### 🔐 Autenticação Segura

- Sistema de cadastro de perfis vocais
- Verificação de identidade em tempo real
- Proteção contra tentativas de falsificação

### 🌐 API RESTful

- Endpoints para cadastro e autenticação
- Documentação interativa com FastAPI
- Integração fácil com sistemas existentes

---

## 🛠️ Tecnologias

### Backend

- **Python 3.13+** - Linguagem principal
- **FastAPI** - Framework web moderno e rápido
- **SpeechBrain** - Biblioteca de ML para processamento de áudio
- **PyTorch** - Framework de Deep Learning
- **PostgreSQL** - Banco de dados relacional

### DevOps & Infraestrutura

- **Docker** - Containerização
- **Docker Compose** - Orquestração de serviços
- **Poetry** - Gerenciamento de dependências
- **Pytest** - Framework de testes

### Machine Learning

- **TorchAudio** - Processamento de áudio
- **HuggingFace** - Modelos pré-treinados
- **MFCC & GMM** - Extração de características vocais

---

## ⚡ Início Rápido

### Pré-requisitos

- Python 3.13+
- Docker & Docker Compose
- Git

### � Instalação

1. **Clone o repositório**

   ```bash
   git clone https://github.com/unb-mds/VIDAProject.git
   cd VIDAProject
   ```

2. **Configure o ambiente**

   ```bash
   cd vida_project_api
   poetry install
   ```

3. **Inicie os serviços**

   ```bash
   docker-compose up -d
   ```

4. **Acesse a aplicação**
   - API: `http://localhost:8000`
   - Documentação: `http://localhost:8000/docs`

### 🧪 Executando Testes

```bash
poetry run pytest
```

---

## 📚 Documentação

### 🔧 Configuração Avançada

- [Configuração do Ambiente](./docs/setup.md)
- [Documentação da API](./docs/api.md)
- [Guia de Contribuição](./docs/contributing.md)

---

## 🤝 Contribuindo

Contribuições são sempre bem-vindas! Veja nosso [Guia de Contribuição](./CONTRIBUTING.md) para começar.

### 📋 Como Contribuir

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

---

## 👨‍💻 Squad 13 - Equipe de Desenvolvimento

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/osakareaper">
        <img src="https://github.com/osakareaper.png" width="100px;" alt="Marcus"/><br>
        <sub><b>Marcus</b></sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/vhcsdev">
        <img src="https://github.com/vhcsdev.png" width="100px;" alt="Victor Hugo"/><br>
        <sub><b>Victor Hugo</b></sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/Pablo-R-L">
        <img src="https://github.com/Pablo-R-L.png" width="100px;" alt="Pablo"/><br>
        <sub><b>Pablo</b></sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/IsaacMPereira">
        <img src="https://github.com/IsaacMPereira.png" width="100px;" alt="Isaac"/><br>
        <sub><b>Isaac</b></sub>
      </a>
    </td>
  </tr>
  <tr>
    <td align="center">
      <a href="https://github.com/Rukkakun">
        <img src="https://github.com/Rukkakun.png" width="100px;" alt="Paulo"/><br>
        <sub><b>Paulo</b></sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/EduardoRGS">
        <img src="https://github.com/EduardoRGS.png" width="100px;" alt="Eduardo"/><br>
        <sub><b>Eduardo</b></sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/leticia-oliveira">
        <img src="https://github.com/leticia-oliveira.png" width="100px;" alt="Letícia"/><br>
        <sub><b>Letícia</b></sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/gsVieiraaa">
        <img src="https://github.com/gsVieiraaa.png" width="100px;" alt="Gabriel"/><br>
        <sub><b>Gabriel</b></sub>
      </a>
    </td>
  </tr>
</table>

---

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

## 🙏 Agradecimentos

- **Universidade de Brasília (UnB)** - Apoio institucional
- **SpeechBrain Community** - Framework de ML para áudio
- **HuggingFace** - Modelos pré-treinados
- **FastAPI Team** - Framework web moderno

---

<div align="center">

**[⬆ Voltar ao topo](#-vida-project)**

---

_Desenvolvido com ❤️ pelo Squad 13 na Universidade de Brasília_

_Projeto disponível em: https://github.com/unb-mds/VIDAProject_

</div>
