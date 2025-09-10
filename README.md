![thumbnail-Praticando CSS_ Grid e Flexbox](https://user-images.githubusercontent.com/76708357/191305858-3d53d611-1ad9-4c3c-b11a-79ff9713153a.png)

# ![image](https://user-images.githubusercontent.com/76708357/191308741-fb59ba6c-8750-4e09-873b-6ab2e96225b7.png) Culturama

O **Culturama** é um site responsivo para divulgação de eventos culturais, desenvolvido como projeto educacional da Alura. O projeto demonstra a aplicação prática de **CSS Grid** e **Flexbox** para criar layouts modernos e responsivos.

🔗 **[Acesse o Figma do projeto](https://www.figma.com/file/mC6DmuXPGWHYkMWOQD3khm/2713---Praticando-CSS%3A-Grid-e-Flexbox?node-id=79%3A289)**

## 🎯 Objetivo do Projeto

Criar uma plataforma web para divulgação de eventos culturais com foco em:

- Layout responsivo para diferentes dispositivos
- Organização visual atrativa de conteúdo
- Navegação intuitiva e acessível
- Demonstração prática de CSS Grid e Flexbox

## ✨ Funcionalidades

- 📱 **Design Responsivo**: Adaptável para mobile, tablet e desktop
- 🎨 **Interface Moderna**: Design limpo com cores vibrantes
- 🗂️ **Categorização**: Organização de eventos por categorias
- 📅 **Agenda**: Seção dedicada para eventos próximos
- 🔍 **Busca**: Campo de pesquisa integrado no header
- 🎪 **Cards Interativos**: Hover effects e transições suaves

## 🛠️ Tecnologias Utilizadas

### HTML5

- Estrutura semântica e acessível
- Uso correto de tags de heading (h1-h6)
- Organização em seções temáticas

### CSS3

O CSS é o protagonista deste projeto, utilizando técnicas modernas:

#### **Flexbox Properties:**

- `display: flex` - Containers flexíveis
- `flex-direction` - Direção dos itens
- `flex-wrap` - Quebra de linha
- `flex-grow` - Crescimento proporcional
- `justify-content` - Alinhamento horizontal
- `align-items` - Alinhamento vertical
- `order` - Reordenação de elementos

#### **Grid Layout:**

- `display: grid` - Containers de grade
- `grid-template-columns` - Definição de colunas
- `grid-template-rows` - Definição de linhas
- `grid-template-areas` - Áreas nomeadas
- `grid-column` e `grid-row` - Posicionamento
- `grid-area` - Atribuição de áreas
- `gap`, `column-gap`, `row-gap` - Espaçamentos

#### **Responsive Design:**

- **Mobile First**: Design base otimizado para dispositivos móveis
- **Breakpoints**: 720px (tablet) e 1440px (desktop)
- **Media Queries**: Adaptação fluida entre tamanhos de tela

#### **Outras Técnicas CSS:**

- **CSS Variables**: Paleta de cores centralizada
- **Transitions**: Efeitos suaves de hover
- **Background Images**: Integração de elementos gráficos
- **Typography**: Hierarquia tipográfica clara

### Recursos Externos

- **Google Fonts**: Fjalla One e Work Sans
- **Reset CSS**: Meyer Reset para normalização
- **Ícones**: Assets próprios integrados

## 🎨 Paleta de Cores

```css
:root {
  --amarelo: #ffc756; /* Destaque principal */
  --laranja: #f66139; /* Shows e Teatro */
  --lilas: #7f8ffe; /* Festivais e Cinema */
  --verde: #56b78c; /* Arte e Fotografia */
  --cinza-claro: #d9d9d9; /* Cards e backgrounds */
  --cinza-escuro: #959595; /* Informações secundárias */
}
```

## 📱 Layout Responsivo

### Mobile (até 719px)

- Layout vertical em coluna única
- Menu com wrap para dispositivos menores
- Cards empilhados verticalmente

### Tablet (720px+)

- Grid de categorias em 2 colunas
- Reorganização do banner
- Melhor aproveitamento do espaço horizontal

### Desktop (1440px+)

- Layout complexo com Grid Template Areas
- Menu horizontal otimizado
- Sidebar de categorias integrada
- Cards organizados em múltiplas colunas

## 📂 Estrutura do Projeto

```
culturama/
├── index.html              # Página principal
├── README.md              # Documentação
└── assets/
    ├── img/               # Imagens e ícones
    │   ├── banners/       # Imagens do carousel
    │   ├── eventos/       # Thumbnails dos eventos
    │   ├── agenda/        # Imagens da agenda
    │   └── icons/         # Ícones da interface
    └── style/
        ├── style.css      # Estilos principais
        ├── flex.css       # Layouts com Flexbox
        └── grid.css       # Layouts com CSS Grid
```

## 🎪 Seções do Site

1. **Header/Navegação**

   - Logo responsivo
   - Menu de navegação
   - Campo de busca integrado
   - Localização com ícones

2. **Banner Principal**

   - Grid de imagens promocionais
   - Layout adaptável por breakpoint

3. **Categorias**

   - 8 categorias de eventos
   - Cores temáticas distintas
   - Seção de destaques integrada

4. **Próximos Eventos**

   - Cards com informações completas
   - Layout flexível e responsivo
   - Botões de ação

5. **Agenda**

   - Eventos organizados por data
   - Design diferenciado para informações temporais
   - Sistema de notificações

6. **Footer**
   - Links organizados por categorias
   - Informações institucionais
   - Logo da empresa

Neste repositório você tem acesso a todo o material produzido no curso.

## � Como Executar o Projeto

### Pré-requisitos

- Navegador web moderno (Chrome, Firefox, Safari, Edge)
- Editor de código (VS Code, Sublime Text, etc.) - opcional para edição

### Instalação e Execução

1. **Clone ou baixe o repositório:**

   ```bash
   git clone [URL_DO_REPOSITORIO]
   ```

2. **Navegue até a pasta do projeto:**

   ```bash
   cd culturama
   ```

3. **Abra o arquivo index.html:**
   - **Opção 1**: Clique duplo no arquivo `index.html`
   - **Opção 2**: Arraste o arquivo para o navegador
   - **Opção 3**: Use a extensão Live Server do VS Code para desenvolvimento

### Desenvolvimento Local

Para desenvolvimento, recomenda-se usar um servidor local:

**Com VS Code + Live Server:**

1. Instale a extensão "Live Server"
2. Clique com botão direito em `index.html`
3. Selecione "Open with Live Server"

**Com Python (se instalado):**

```bash
python -m http.server 8000
```

Acesse: `http://localhost:8000`

**Com Node.js (se instalado):**

```bash
npx http-server
```

## 🎓 Conceitos Aprendidos

### Flexbox

- **Containers flexíveis** para layouts unidimensionais
- **Alinhamento** de elementos em eixos principais e cruzados
- **Distribuição** de espaço disponível
- **Reordenação** visual de elementos
- **Responsividade** natural dos layouts

### CSS Grid

- **Layouts bidimensionais** complexos
- **Template areas** para organização visual
- **Grid lines** e posicionamento preciso
- **Responsive grids** com media queries
- **Sobreposição** controlada de elementos

### Responsive Design

- **Mobile First** approach
- **Breakpoints** estratégicos
- **Layouts flexíveis** que se adaptam
- **Otimização** para diferentes dispositivos

## 🔄 Próximos Passos / Possíveis Melhorias

- [ ] **JavaScript**: Adicionar interatividade (filtros, busca, carousel)
- [ ] **Acessibilidade**: Melhorar navegação por teclado e screen readers
- [ ] **Performance**: Otimização de imagens e lazy loading
- [ ] **PWA**: Transformar em Progressive Web App
- [ ] **API Integration**: Conectar com backend real de eventos
- [ ] **Animações**: CSS animations e micro-interações
- [ ] **SEO**: Meta tags e structured data

## 📝 Licença

Este projeto foi desenvolvido durante o curso da Alura e é destinado para fins educacionais.

## 👨‍💻 Autor

**Desenvolvido por Alura** - Curso de CSS Grid e Flexbox

---

💡 **Dica**: Este projeto é uma excelente base para quem quer aprender CSS Grid e Flexbox na prática. Experimente modificar os layouts e criar suas próprias variações!
