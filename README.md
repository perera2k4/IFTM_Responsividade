<div align="center">
  <img src="./img/if-logo.png" alt="Logo IFTM" width="450"/>
  <h3>Instituto Federal de Educação, Ciência e Tecnologia do Triângulo Mineiro - Campus Ituiutaba</h3>
  <p><em>Graduação em Tecnologia em <u>Análise e Desenvolvimento de Sistemas</u></em></p>
</div>

# 🦸‍♂️ Vingadores - Website Responsivo

## 📋 Descrição do Projeto

Este projeto é um website responsivo dedicado aos Vingadores da Marvel, desenvolvido como parte do trabalho de **Responsividade**. O site apresenta informações sobre a equipe de heróis, galeria de pôsteres e design totalmente adaptável para diferentes dispositivos.

## 🎯 Funcionalidades Implementadas

### 📱 Design Responsivo
- **Layout Flexível**: Adaptação automática para diferentes tamanhos de tela
- **Navegação Mobile**: Menu otimizado para dispositivos móveis
- **Grid Adaptativo**: Sistema de grid que se reorganiza conforme o viewport
- **Imagens Responsivas**: Todas as imagens se ajustam proporcionalmente

### 🧭 Navegação
- **Menu de Navegação**: Links âncora para seções específicas (Home, Sobre, Equipe, Pôsteres)
- **Scroll Suave**: Transições suaves entre seções
- **Header Fixo**: Navegação sempre acessível no topo da página

### 👥 Seção da Equipe
- **Cards Interativos**: Hover effects nos cards dos heróis
- **Grid Responsivo**: Layout que se adapta de 1 a 3 colunas
- **Informações dos Heróis**: Cards individuais para cada membro da equipe

### 🖼️ Galeria de Pôsteres
- **Grid de Imagens**: Exibição organizada de 12 pôsteres
- **Layout Adaptativo**: De 2 a 6 colunas dependendo do dispositivo
- **Otimização de Carregamento**: Imagens otimizadas para web

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estrutura semântica da página
- **CSS3**: Estilização avançada e layout responsivo
- **Google Fonts**: Fonte Raleway para tipografia elegante
- **Flexbox**: Sistema de layout flexível
- **CSS Grid**: Layout em grade para componentes
- **Media Queries**: Responsividade para diferentes dispositivos

## 📁 Estrutura do Projeto

```
📦 vingadores-responsivo/
├── 📄 index.html                           # Página principal
├── 🎨 css/
│   └── style.css                           # Estilos CSS responsivos
├── 📖 README.md                            # Documentação
├── 📸 Screenshot Vingadores (Grande).jpg   # Screenshot desktop
├── 📸 Screenshot Vingadores (Média).jpg    # Screenshot tablet
├── 📸 Screenshot Vingadores (Pequena).jpg  # Screenshot mobile
└── 📁 img/                                 # Imagens do projeto   
    ├── 🖼️ if-logo                          # Logo IFTM
    ├── 🖼️ logo.png                         # Logo dos Vingadores
    ├── 🖼️ cover.jpg                        # Imagem de capa
    ├── 👥 team-01.jpg a team-06.jpg        # Fotos da equipe
    └── 🎬 poster-01.jpg a poster-12.jpg    # Pôsteres dos filmes
```

## 🚀 Como Visualizar

1. **Acesse o Github Pages:** [`https://perera2k4.github.io/IFTM_Responsividade/`](https://perera2k4.github.io/IFTM_Responsividade/)
<br>ou
2. **Clone ou baixe o projeto**
1. **Abra o arquivo [`index.html`](index.html)** em qualquer navegador web moderno
4. **Teste a responsividade**:
   - Redimensione a janela do navegador
   - Use as ferramentas de desenvolvedor (F12) para simular dispositivos móveis
   - Navegue pelas seções usando o menu

## 📱 Breakpoints Responsivos

### 📱 Mobile (até 640px)
- Header em coluna com logo centralizado
- Grid da equipe em 1 coluna
- Grid de pôsteres em 2 colunas
- Footer empilhado
<div align="center" style="max-height: 1000px; overflow-y: auto; border: 1px solid #ccc; padding: 10px;">
  <img src="./Screenshot Vingadores (Pequena).jpg" alt="Screenshot Mobile" width="100%"/>
</div>

### 📱 Tablet (641px - 799px)
- Grid da equipe em 2 colunas
- Grid de pôsteres em 4 colunas
<div align="center" style="max-height: 1000px; overflow-y: auto; border: 1px solid #ccc; padding: 10px;">
  <img src="./Screenshot Vingadores (Média).jpg" alt="Screenshot Mobile" width="100%"/>
</div>

### 🖥️ Desktop Grande (800px+)
- Grid da equipe em 3 colunas com hover effects
- Grid de pôsteres em 6 colunas
- Footer em layout horizontal
<div align="center" style="max-height: 1000px; overflow-y: auto; border: 1px solid #ccc; padding: 10px;">
  <img src="./Screenshot Vingadores (Grande).jpg" alt="Screenshot Mobile" width="100%"/>
</div>

## 💡 Funcionalidades Técnicas

### CSS Features
- **Flexbox Layout**: Header e navegação flexíveis
- **CSS Grid**: Sistema de grade para equipe e pôsteres
- **Media Queries**: 4 breakpoints para responsividade total
- **Hover Effects**: Animações nos cards da equipe
- **Parallax Effect**: Efeito de profundidade na seção cover
- **Custom Scrollbar**: Scroll personalizado

### HTML Features
- **Estrutura Semântica**: Tags HTML5 apropriadas
- **Navigation Links**: Âncoras para navegação interna
- **Responsive Images**: Atributos para otimização de imagens
- **Accessibility**: Alt texts e estrutura acessível

## 📝 Créditos

- **Desenvolvimento**: <u>Bruno Pereira</u>
- **Projeto**: Aula de Responsividade, professor <u>Me. Daniel Pimentel</u>