# Loja de Livros Cristãos - Seção HERO

Uma página de vendas elegante e emocional para livros cristãos, desenvolvida com Next.js 15, App Router e Tailwind CSS.

## 🎯 Objetivo

Criar uma experiência que transmita **paz**, **fé**, **esperança**, **confiança** e **alegria** através de um design limpo e focado em conversão.

## 🎨 Design e Cores

### Paleta de Cores (seguindo especificações)

- **Azul principal**: `#2F5D8C` - Transmite confiança e serenidade
- **Verde secundário**: `#3A7D44` - Representa esperança e crescimento
- **Dourado (CTA)**: `#C9A44C` - Destaca ações importantes
- **Background**: `#F7F6F2` - Suavidade e elegância
- **Texto**: `#2E2E2E` - Legibilidade otimizada

### Tipografia

- **Títulos**: Playfair Display (elegante e impactante)
- **Texto**: Inter (legibilidade e clareza)

## 🏗️ Estrutura Técnica

### Layout Responsivo

- **Desktop**: Duas colunas (foto do pastor + conteúdo)
- **Mobile**: Layout empilhado (foto acima, texto centralizado abaixo)

### Componentes

- `Hero.tsx` - Componente principal da seção HERO
- Layout responsivo usando CSS Grid e Flexbox
- Animações sutis de entrada (fade-in + slide-up)

### Recursos Implementados

- ✅ Next.js 15 com App Router
- ✅ Tailwind CSS personalizado
- ✅ Fontes Google (Playfair Display + Inter)
- ✅ Design totalmente responsivo
- ✅ Acessibilidade (alt text, contraste, focus states)
- ✅ Animações sutis e não intrusivas
- ✅ SEO otimizado (meta tags, lang="pt-BR")

## 🚀 Como executar

```bash
# Instalar dependências
npm install

# Executar em desenvolvimento
npm run dev

# Acessar no navegador
http://localhost:3000

# Build para produção
npm run build
```

## 📱 Características da Seção HERO

### Conteúdo

- **Headline impactante**: "Uma palavra que fortalece sua fé e renova sua esperança"
- **Subtítulo acolhedor**: Texto explicativo sobre os benefícios dos livros
- **CTA em destaque**: "Adquirir os livros" com design que chama atenção
- **Foto do pastor**: Placeholder responsivo com efeitos visuais

### Interatividade

- Hover effects no botão CTA
- Animações de entrada sequenciais
- Elementos decorativos sutis
- Focus states para acessibilidade

### Otimizações

- Carregamento otimizado das fontes (`display: 'swap'`)
- Respeito às preferências de movimento (`prefers-reduced-motion`)
- HTML semântico para SEO
- Meta tags otimizadas

## 🎯 Conversão e UX

- **Visual clean**: Sem poluição, foco no essencial
- **Hierarquia clara**: Título → Subtítulo → CTA
- **Cores estratégicas**: Palavras-chave destacadas em cores da marca
- **Mobile-first**: Experiência otimizada em todos os dispositivos
- **Emotional design**: Elementos que transmitem serenidade e confiança

## 📂 Estrutura de Arquivos

```
src/
├── app/
│   ├── layout.tsx     # Layout principal + configuração de fontes
│   ├── page.tsx       # Página inicial com Hero
│   └── globals.css    # Estilos globais e CSS customizado
├── components/
│   └── Hero.tsx       # Componente da seção HERO
tailwind.config.ts     # Configuração do Tailwind
```

## 🔧 Customizações Disponíveis

O componente Hero aceita props opcionais para personalização:

```tsx
<Hero className="custom-hero-styles" />
```

As cores estão configuradas no Tailwind como classes utilitárias personalizadas para fácil manutenção.

---

**Status**: ✅ **Projeto concluído com sucesso**

A seção HERO está pronta para integração em um projeto maior ou pode ser expandida com seções adicionais como depoimentos, detalhes dos livros, footer, etc.
