# Lista Completa de Componentes Shadcn/UI

Este arquivo contém a lista completa de todos os componentes disponíveis no shadcn/ui para referência rápida através do MCP Server.

## 📦 Componentes Disponíveis (Lista Completa)

### 🎨 Layout & Structure
- **accordion** - Componente de acordeão expansível/colapsável
- **aspect-ratio** - Componente para manter proporções de aspecto
- **resizable** - Painéis redimensionáveis (split panes)
- **separator** - Separador visual horizontal/vertical
- **sheet** - Painel lateral deslizante (drawer)
- **sidebar** - Barra lateral de navegação responsiva

### 🧭 Navigation
- **breadcrumb** - Navegação breadcrumb hierárquica
- **menubar** - Barra de menu horizontal
- **navigation-menu** - Menu de navegação avançado
- **pagination** - Paginação de resultados
- **tabs** - Sistema de abas/tabs
- **command** - Command Palette com busca (⌘K)

### 📝 Forms & Input
- **button** - Botão com variantes e tamanhos
- **checkbox** - Caixa de seleção
- **form** - Formulário com validação (React Hook Form)
- **input** - Campo de entrada de texto
- **input-otp** - Input para códigos OTP/verificação
- **label** - Rótulo para formulários
- **radio-group** - Grupo de botões de rádio
- **select** - Seleção dropdown
- **slider** - Controle deslizante (range)
- **switch** - Interruptor toggle
- **textarea** - Área de texto multilinha

### 📊 Data Display
- **table** - Tabela de dados com ordenação
- **card** - Card/container para conteúdo
- **avatar** - Avatar de usuário com fallback
- **badge** - Badge/etiqueta com variantes
- **skeleton** - Placeholder de carregamento
- **chart** - Gráficos e visualizações (Recharts)

### 💬 Feedback & Notifications
- **alert** - Alerta/notificação inline
- **alert-dialog** - Diálogo de alerta/confirmação
- **dialog** - Diálogo modal
- **drawer** - Gaveta lateral (mobile-first)
- **hover-card** - Card ao passar o mouse
- **popover** - Popover flutuante posicionado
- **progress** - Barra de progresso
- **sonner** - Sistema de notificações toast (Sonner)
- **toast** - Notificações toast (Radix UI)
- **tooltip** - Tooltip informativo

### 🎯 Overlays & Menus
- **context-menu** - Menu de contexto (right-click)
- **dropdown-menu** - Menu dropdown
- **toggle** - Botão toggle
- **toggle-group** - Grupo de toggles

### 🖼️ Media & Content
- **carousel** - Carrossel de imagens/conteúdo
- **scroll-area** - Área com scroll customizado

### 📅 Calendar & Date
- **calendar** - Calendário interativo
- **date-picker** - Seletor de data (combinado com calendar e popover)

## 📋 Lista Rápida para Referência

```
accordion, alert, alert-dialog, aspect-ratio, avatar, badge, breadcrumb, 
button, calendar, card, carousel, chart, checkbox, command, context-menu, 
dialog, drawer, dropdown-menu, form, hover-card, input, input-otp, label, 
menubar, navigation-menu, pagination, popover, progress, radio-group, 
resizable, scroll-area, select, separator, sheet, sidebar, skeleton, slider, 
sonner, switch, table, tabs, textarea, toast, toggle, toggle-group, tooltip
```

**Total: 46 componentes disponíveis**

## Como Usar

### Via MCP Server (Recomendado)
Agora que o MCP server está configurado, você pode usar comandos em linguagem natural:

```
Adicione um botão ao projeto
Crie um formulário de login usando componentes shadcn
Mostre-me todos os componentes disponíveis no registry shadcn
Instale o componente card, dialog e form
```

### Via CLI
```bash
# Adicionar um componente específico
npx shadcn@latest add button

# Adicionar múltiplos componentes
npx shadcn@latest add button card dialog

# Adicionar TODOS os componentes (não recomendado, adicione conforme necessário)
npx shadcn@latest add --all
```

## Configuração MCP

O MCP server do shadcn está configurado em `.cursor/mcp.json`. 

Após reiniciar o Cursor, você poderá:
- Navegar por todos os componentes disponíveis
- Buscar componentes por nome ou funcionalidade
- Instalar componentes usando linguagem natural
- Acessar múltiplos registries (se configurados)

## Notas Importantes

1. **Não instale todos os componentes de uma vez** - Adicione apenas os que você realmente precisa para manter o projeto limpo
2. **Componentes são copiados para seu projeto** - Você tem controle total sobre o código
3. **Personalização** - Todos os componentes podem ser modificados conforme necessário
4. **Acessibilidade** - Componentes são construídos com Radix UI, garantindo acessibilidade

## Registry Padrão

O registry padrão do shadcn/ui está disponível sem configuração adicional. Para usar registries privados ou de terceiros, configure em `components.json`:

```json
{
  "registries": {
    "@acme": "https://acme.com/r/{name}.json"
  }
}
```

