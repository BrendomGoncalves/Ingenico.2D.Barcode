# Ingenico 2D Barcode - Frontend

![Angular](https://img.shields.io/badge/Angular-18-red)
![TypeScript](https://img.shields.io/badge/TypeScript-5.x-blue)
![Node](https://img.shields.io/badge/Node.js-20+-green)
![Status](https://img.shields.io/badge/status-concluido-green)

Sistema web para **gerenciamento de produtos com QRCode**, desenvolvido o frontend com **Angular**.  
O objetivo da aplicação é permitir o controle, visualização e organização dos produtos gerando QRCode para acesso em Totem no quiosque ou smartphone.

---

<p align="center">
  <img width="400" alt="Tela de Login" src="https://github.com/user-attachments/assets/edfd1bdb-a755-4e9e-a9f4-b031cf42aac9" />
  <img width="400" alt="Tela de Gerenciamento de Produtos" src="https://github.com/user-attachments/assets/5b6a5a01-6716-4098-b16d-bb46c050e65d" />
  <img width="400" alt="Tela de Scanner do Totem" src="https://github.com/user-attachments/assets/6f266006-102e-4fbf-8432-9b55865ae69c" />
  <img width="400" alt="Tela de Regitro de Produto" src="https://github.com/user-attachments/assets/2954c4f7-e32d-449f-ad4d-9537a56ac8b8" />
</p>

---

# 📌 Sobre o projeto

O **Ingenico 2D Barcode** é uma aplicação frontend que permite registrar e acompanhar **produtos cadastrados e vinculados a QRCode** de maneira estruturada.

A proposta do sistema é facilitar o controle e acesso aos produtos por empresas com quiosque através de totens e celulares:

- Registrar produtos no sistema
- Acompanhar status dos produtos
- Organizar informações dos produtos e QRCode
- Controlar histórico dos produtos

---

# ⚙️ Funcionalidades do sistema

O sistema foi projetado para fornecer uma interface simples e eficiente para gerenciamento de produtos.

Entre as funcionalidades esperadas estão:

### 📄 Gestão de Produtos

- criação de novos produtos
- visualização dos produtos cadastrados
- acompanhamento do status de QrCode dos produtos

### 👤 Gestão de QrCode

- registro de informações com QRCode
- associação de QRCode estáticos e dinamicos (com página exclusiva para totem)

---

# 🚀 Tecnologias utilizadas

O projeto foi desenvolvido utilizando tecnologias modernas de frontend.

- **Angular**
- **TypeScript**
- **HTML5**
- **CSS / SCSS**
- **Node.js**
- **Angular CLI**
- **PrimeNG**

Ferramentas de desenvolvimento:

- Angular CLI
- npm

---

# 📂 Estrutura do projeto

```
OrdemS
│
├── public/              # Arquivos públicos
├── src/
│   ├── app/             # Componentes, módulos, enums, models, pages e serviços
|      |── Components/
|      |── Guards/
|      |── Interceptors/
|      |── Models/
|      |── Pages/
|      |── Services/
|      |── app.component.scss
|      |── app.component.html
|      |── app.component.ts
|      |── app.config.ts
|      |── app.routes.ts
|
│   ├── environments/    # Configurações de ambiente
│   |── index.html
|   |── style.scss
|   |── main.ts
│
├── angular.json         # Configuração do Angular
├── package.json         # Dependências do projeto
├── tsconfig.json        # Configurações do TypeScript
|── server.ts            # Configurações Node Express
└── README.md
```

---

# 🧰 Pré-requisitos

Antes de executar o projeto é necessário ter instalado:

- **Node.js**
- **npm**
- **Angular CLI**

Instalar Angular CLI:

```bash
npm install -g @angular/cli
```

---

# ▶️ Executando o projeto

### 1 — Clone o repositório

```bash
git clone https://github.com/BrendomGoncalves/OrdemS.git
```

### 2 — Acesse a pasta

```bash
cd OrdemS
```

### 3 — Instale as dependências

```bash
npm install
```

### 4 — Execute o projeto

```bash
ng serve
```

A aplicação ficará disponível em:

```
http://localhost:4200
```

---

# 👨‍💻 Autores

Desenvolvido por:
**Brendom Gonçalves**
**Giuseppe Mota**
**Lucas Silva**

GitHub  
https://github.com/BrendomGoncalves
https://github.com/giuseppemota
https://github.com/eulucasilva
