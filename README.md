# Arsenal - Landing Page

Uma landing page moderna e responsiva para o Arsenal, a ferramenta definitiva para gestores de tráfego de negócios locais.

## 🚀 Deploy na Vercel

Este projeto está configurado para deploy automático na Vercel. Para fazer o deploy:

1. **Via Vercel CLI:**
   ```bash
   npm i -g vercel
   vercel --prod
   ```

2. **Via GitHub:**
   - Faça push do código para um repositório GitHub
   - Conecte o repositório na Vercel
   - Deploy automático será executado

3. **Via Dashboard Vercel:**
   - Acesse [vercel.com](https://vercel.com)
   - Importe este projeto
   - Deploy será executado automaticamente

## 📁 Estrutura do Projeto

```
Arsenal/
├── index.html          # Página principal
├── vercel.json         # Configurações da Vercel
├── package.json        # Metadados do projeto
└── README.md          # Documentação
```

## ✨ Características

- **Responsivo:** Funciona perfeitamente em desktop, tablet e mobile
- **Performance:** Otimizado para carregamento rápido
- **SEO:** Meta tags e estrutura otimizada para buscadores
- **Moderno:** Design atual com Tailwind CSS
- **Interativo:** Elementos animados e slider de depoimentos

## 🛠️ Tecnologias Utilizadas

- HTML5 semântico
- Tailwind CSS (via CDN)
- JavaScript vanilla
- Remix Icons
- Google Fonts (Inter + Pacifico)

## 🎨 Funcionalidades

- Hero section com gradiente animado
- Seção de benefícios com cards interativos
- Planos de preços com destaque
- Slider de depoimentos
- FAQ com acordeão
- Footer completo
- Navegação suave entre seções

## 📱 Responsividade

O site é totalmente responsivo e se adapta a:
- Desktop (1200px+)
- Tablet (768px - 1199px)
- Mobile (até 767px)

## 🔧 Desenvolvimento Local

Para testar localmente:

```bash
# Usando Python
python3 -m http.server 3000

# Ou usando Node.js (se tiver live-server instalado)
npx live-server --port=3000
```

Acesse: `http://localhost:3000`

## 📈 Otimizações Implementadas

- Carregamento assíncrono de fontes
- Compressão de imagens via CDN
- CSS otimizado com Tailwind
- JavaScript minificado
- Headers de segurança configurados

## 🚀 Pronto para Produção

Este projeto está 100% pronto para deploy na Vercel com:
- Configurações de build otimizadas
- Headers de segurança
- Redirects configurados
- Performance otimizada
