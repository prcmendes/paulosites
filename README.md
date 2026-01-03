🚀 MarketMaster - Vitrine de Produtos Digitais

O **MarketMaster** é uma plataforma moderna e intuitiva desenvolvida para empreendedores digitais que desejam publicar e gerenciar seus próprios ebooks, cursos e produtos de afiliados com facilidade.

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Google Gemini](https://img.shields.io/badge/Google%20Gemini-4285F4?style=for-the-badge&logo=google&logoColor=white)

## ✨ Funcionalidades

- **🛒 Vitrine Dinâmica**: Exibição elegante de produtos com categorias e detalhes.
- **🔐 Área Restrita**: Painel administrativo protegido por senha para gestão de conteúdo.
- **🤖 Assistente IA**: Integração com Google Gemini para recomendar produtos aos usuários com base em suas necessidades.
- **📱 Totalmente Responsivo**: Experiência otimizada para celulares, tablets e desktops.
- **💾 Persistência Local**: Seus produtos ficam salvos no navegador através do `localStorage`.
- **🎯 Foco em Conversão**: Design limpo seguindo diretrizes de conformidade para Google Ads.

## 🛠️ Tecnologias Utilizadas

- **React 19**: Biblioteca para construção da interface.
- **Tailwind CSS**: Estilização moderna e rápida.
- **Google Generative AI SDK (@google/genai)**: Motor da inteligência artificial.
- **Lucide Icons**: Ícones minimalistas.

## ⚙️ Configuração e Instalação

### 1. Requisitos
Você precisará de uma chave de API do Google Gemini. Obtenha a sua em [Google AI Studio](https://aistudio.google.com/).

### 2. Variáveis de Ambiente
O projeto utiliza uma variável de ambiente para a chave da IA:
- `API_KEY`: Sua chave privada do Google Gemini.

> **Dica**: Se estiver publicando na **Vercel** ou **Netlify**, adicione esta chave nas configurações de "Environment Variables" do painel de controle da hospedagem.

### 3. Acesso Administrativo
Para acessar a área de publicações:
1. Clique em **Painel** na barra de navegação.
2. Digite a senha padrão: `admin` (você pode alterar isso no arquivo `App.tsx`).

## 🚀 Como Publicar

Este é um projeto frontend puro. Para colocar no ar:
1. Suba os arquivos para um repositório no **GitHub**.
2. Conecte o repositório à **Vercel** ou **Netlify**.
3. Configure a variável `API_KEY`.
4. O deploy será feito automaticamente!

---

Desenvolvido para transformar a forma como você vende produtos digitais. 📈
