# Site de Casamento - Leo & Dan 💕

Um site completo para gerenciamento de casamento com paleta de cores terracota, desenvolvido especialmente para Leo e Dan.

## 🎨 Design

- **Paleta de Cores**: Terracota (#C65D32, #E07B39, #F4A261, #A0522D)
- **Tipografia**: Georgia, Times New Roman (serif)
- **Estilo**: Elegante, romântico e responsivo
- **Foto de Fundo**: Imagem romântica do casal na seção principal

## ✨ Funcionalidades

### 📱 Site Principal (`index.html`)
- Página inicial com foto do casal como plano de fundo
- Informações completas do casamento:
  - **Data**: 27 de Setembro de 2025 às 17:30
  - **Cerimônia**: Capela Nossa Senhora dos Aflitos, Av. Conselheiro Rosa e Silva, 752 - Graças, Recife - PE
  - **Recepção**: Villa Gold Buffet Recepções e Eventos
- Design responsivo para mobile e desktop
- Navegação suave entre seções
- História personalizada do casal

### 👥 Confirmação de Presença (`rsvp.html`)
- Formulário completo de RSVP
- Informações detalhadas do evento com links para localização
- Campos condicionais baseados na confirmação
- Contagem de adultos e crianças
- Campo para restrições alimentares
- Mensagens personalizadas para os noivos
- Validação de formulário e feedback visual

### 🎁 Lista de Presentes (`gifts.html`)
- Redirecionamento automático para lista da Ferreira Costa
- Link direto: https://www.ferreiracosta.com/lista-de-casamento/presentes/leandroedanubia
- Countdown de 5 segundos antes do redirecionamento
- Interface elegante de transição

### ⚙️ Painel Administrativo (`admin.html`)
- Gerenciamento completo de convidados
- Visualização de confirmações RSVP
- Estatísticas em tempo real
- Configurações do casamento pré-preenchidas
- Interface intuitiva para os noivos

## 🚀 Como Usar no GitHub

### 1. Criar Repositório
1. Acesse [GitHub.com](https://github.com)
2. Clique em "New repository"
3. Nomeie como "leo-dan-casamento" ou similar
4. Marque como "Public"
5. Clique em "Create repository"

### 2. Upload dos Arquivos
1. Clique em "uploading an existing file"
2. Arraste todos os arquivos da pasta do projeto
3. Escreva uma mensagem de commit: "Site de casamento Leo & Dan"
4. Clique em "Commit changes"

### 3. Ativar GitHub Pages
1. Vá em "Settings" do repositório
2. Role até "Pages" no menu lateral
3. Em "Source", selecione "Deploy from a branch"
4. Escolha "main" branch e "/ (root)"
5. Clique em "Save"

### 4. Acessar o Site
Após alguns minutos, seu site estará disponível em:
`https://seuusuario.github.io/nome-do-repositorio`

## 📁 Estrutura de Arquivos

```
leo-dan-wedding/
├── index.html                    # Página principal
├── rsvp.html                     # Confirmação de presença
├── gifts.html                    # Lista de presentes (redirecionamento)
├── admin.html                    # Painel administrativo
├── assets/
│   ├── couple_background.jpg     # Foto do casal para plano de fundo
│   ├── index-CQqjxzdw.css       # Estilos CSS compilados
│   └── index-DuUsBShi.js        # Scripts JavaScript compilados
├── favicon.ico                   # Ícone do site
├── README.md                     # Este arquivo
└── .gitignore                    # Arquivos ignorados pelo Git
```

## 🎯 Informações do Casamento

### 📅 Data e Horário
- **Data**: 27 de Setembro de 2025
- **Horário**: 17:30

### 📍 Locais
- **Cerimônia**: Capela Nossa Senhora dos Aflitos
  - Endereço: Av. Conselheiro Rosa e Silva, 752 - Graças, Recife - PE
- **Recepção**: Villa Gold Buffet Recepções e Eventos
  - [Ver no Google Maps](https://www.google.com/maps/place/Villa+Gold+Buffet+Recep%C3%A7%C3%B5es+e+Eventos/@-8.0574568,-34.9120323,17z/data=!3m1!4b1!4m6!3m5!1s0x7ab1921597ae34b:0x855fa4dbe13799bf!8m2!3d-8.0574568!4d-34.9120323!16s%2Fg%2F11b6ll2zvr?entry=ttu&g_ep=EgoyMDI1MDcwOS4wIKXMDSoASAFQAw%3D%3D)

### 👔 Dress Code
- **Social**

### 🎁 Lista de Presentes
- **Ferreira Costa**: https://www.ferreiracosta.com/lista-de-casamento/presentes/leandroedanubia

## 🎨 Personalização

### Cores
As cores podem ser alteradas editando as variáveis CSS no início de cada arquivo:
```css
:root {
    --terracota-primary: #C65D32;
    --terracota-secondary: #E07B39;
    --terracota-light: #F4A261;
    --terracota-dark: #A0522D;
    --cream: #F5F5DC;
    --warm-white: #FFF8F0;
}
```

### Informações do Casamento
Para alterar datas, locais ou outras informações, edite:
- `index.html` - Informações principais e seção hero
- `rsvp.html` - Detalhes do evento e formulário
- `admin.html` - Configurações padrão do painel

### Foto do Casal
Para alterar a foto de fundo:
1. Substitua o arquivo `assets/couple_background.jpg`
2. Mantenha o mesmo nome ou atualize a referência no CSS

## 💾 Armazenamento de Dados

O site utiliza `localStorage` do navegador para armazenar:
- Confirmações de presença (RSVP)
- Lista de convidados
- Configurações do casamento
- Dados administrativos

**Nota**: Os dados são salvos localmente em cada dispositivo. Para um sistema mais robusto, considere integrar com um backend.

## 📱 Compatibilidade

- ✅ Chrome, Firefox, Safari, Edge
- ✅ Dispositivos móveis (iOS/Android)
- ✅ Tablets e desktops
- ✅ Design totalmente responsivo
- ✅ Touch-friendly para dispositivos móveis

## 🔧 Funcionalidades Técnicas

- **CSS Grid e Flexbox** para layouts responsivos
- **JavaScript Vanilla** para interatividade
- **LocalStorage** para persistência de dados
- **Animações CSS** para melhor experiência do usuário
- **Formulários validados** com feedback visual
- **Máscaras de input** para telefone
- **Redirecionamento automático** para lista de presentes
- **Links diretos** para Google Maps

## 🆘 Suporte

Para dúvidas ou problemas:
1. Verifique se todos os arquivos foram enviados corretamente
2. Confirme que o GitHub Pages está ativado
3. Aguarde alguns minutos para a propagação
4. Teste em diferentes navegadores
5. Verifique se a foto do casal está no diretório `assets/`

## 💝 Créditos

Site criado especialmente para **Leo & Dan**
- **Data do Casamento**: 27 de Setembro de 2025
- **Local**: Recife - PE
- **Paleta**: Terracota
- **Estilo**: Romântico e elegante

---

**Feito com ❤️ para um dia inesquecível!**

*Que este site ajude a tornar o casamento de Leo e Dan ainda mais especial e organizado!*

