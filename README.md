# 🥐 Sistema Salgadaria - TCC

<p align="center">
  <img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" alt="Laravel" width="300">
</p>

<p align="center">
  <strong>Um sistema moderno para gerenciar sua salgadaria</strong><br>
  Desenvolvido com Laravel e tecnologias web modernas
</p>

---

## 📋 Índice

- [🚀 Pré-requisitos](#-pré-requisitos)
- [📥 Clonando o Repositório](#-clonando-o-repositório)
- [⚙️ Configuração do Ambiente](#-configuração-do-ambiente)
- [📦 Instalando Dependências](#-instalando-dependências)
- [🔧 Comandos Úteis](#-comandos-úteis)

---

## 🚀 Pré-requisitos

Antes de começar, certifique-se de que você tem:

> **📌 Pré-requisito importante:** Converse com **Kauan (@kauanmmartins)** para ser adicionado como colaborador do repositório

### Ferramentas Necessárias

| Ferramenta | Status | Link |
|-----------|--------|------|
| **PHP** | ✅ | [Como instalar](https://www.youtube.com/watch?v=gQ-P0yMBE9U) |
| **Node.js & npm** | ✅ | [Como instalar](https://www.youtube.com/watch?v=DbJlrkW63XU) |
| **Composer** | ✅ | [Como instalar](https://www.youtube.com/watch?v=Dimtx-pQPuA) |

### Verificando Instalações

Abra o **Prompt de Comando** e execute:

```bash
php -v        # Verificar PHP
node -v       # Verificar Node.js
npm -v        # Verificar npm
composer -v   # Verificar Composer
```

---

## 📥 Clonando o Repositório

Siga os passos abaixo para clonar o repositório:

1. **Abra o VS Code**
2. **Clique em** "Clonar Repositório" (Explorador ou Controle de Código-Fonte)
3. **Selecione** "Clonar de GitHub"
4. **Escolha** o repositório que começa com `kauanmmartins`
5. **Escolha** o local onde deseja salvar o projeto em seu computador

✅ **Repositório clonado com sucesso!**

---

## ⚙️ Configuração do Ambiente

### 1. Navegue até a pasta do projeto

```bash
cd sistema-salgadaria_tcc
```

### 2. Configure o arquivo `.env`

```bash
cp .env.example .env
```

### 3. Gere a chave da aplicação

```bash
php artisan key:generate
```

---

## 📦 Instalando Dependências

Abra o terminal do VS Code e execute os seguintes comandos:

```bash
# 📦 Instalar dependências PHP
composer install

# 📦 Instalar dependências JavaScript/CSS (Vite, Mix, etc)
npm install
```

⏳ **Aguarde a instalação ser concluída...**

---

## 🔧 Comandos Úteis

### 🔄 Comandos Git

| Comando | Descrição |
|---------|-----------|
| `git pull origin main` | Atualizar repositório local com a branch principal |
| `git fetch` | Buscar atualizações do repositório remoto |
| `git checkout nome-da-branch` | Trocar de branch |
| `git checkout -b nova-branch` | Criar e trocar para uma nova branch |

### 📊 Comandos Laravel

| Comando | Descrição |
|---------|-----------|
| `php artisan migrate` | Executar as migrations do banco de dados |
| `php artisan migrate:reset` | Desfazer todas as migrations |
| `php artisan serve` | Iniciar o servidor local na porta 8000 |

### 🎨 Comandos Frontend

| Comando | Descrição |
|---------|-----------|
| `npm run dev` | Compilar assets em modo desenvolvimento |
| `npm run build` | Compilar assets para produção |
| `npm run watch` | Observar mudanças nos arquivos |

---

## 🚀 Iniciando o Projeto

Com tudo configurado, execute:

```bash
# Iniciar o servidor Laravel
php artisan serve
```

A aplicação estará disponível em: **http://localhost:8000**

---

## 📝 Fluxo de Trabalho Recomendado

1. **Criar uma nova branch** para suas alterações:
   ```bash
   git checkout -b feature/minha-funcionalidade
   ```

2. **Fazer suas alterações** e testar localmente

3. **Fazer commit** com mensagens descritivas:
   ```bash
   git add .
   git commit -m "Descrever a alteração"
   ```

4. **Enviar para o repositório remoto**:
   ```bash
   git push origin feature/minha-funcionalidade
   ```

5. **Criar um Pull Request** para review

---

## 📞 Suporte

Para dúvidas ou problemas, entre em contato com:
- **Kauan** (@kauanmmartins) - Proprietário do repositório

---

## 📄 Licença

Este projeto está sob a licença **MIT**. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

<p align="center">
  Made with ❤️ by Grupo Casa dos Salgados TCC - 2025
</p>
