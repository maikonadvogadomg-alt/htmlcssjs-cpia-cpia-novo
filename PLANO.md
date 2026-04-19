# PLANO DO PROJETO: HTML/CSS/JS (cópia) (cópia)

> Gerado automaticamente pelo SK Code Editor em 19/04/2026, 14:09:27
> **111 arquivo(s)** | **~111 linhas de codigo**

---

## RESUMO EXECUTIVO

- **Tipo de aplicacao:** Aplicacao Web Frontend (React)
- **Frontend / Stack principal:** React + Vite, TypeScript

**Para rodar o projeto:**
```bash
# Abra index.html no Preview (botao Play)
```

---

## ESTRUTURA DE ARQUIVOS

```
HTML/CSS/JS (cópia) (cópia)/
├── .sk/
│   ├── memoria.json
│   └── perfil-jasmim.md
├── dist/
│   ├── auditoria.html
│   ├── codigo-formatacao.txt
│   ├── comparador.html
│   ├── favicon.png
│   ├── icon-192.png
│   ├── icon-512.png
│   ├── index.html
│   ├── manifest.json
│   └── sw.js
├── public/
│   ├── auditoria.html
│   ├── codigo-formatacao.txt
│   ├── comparador.html
│   ├── favicon.png
│   ├── icon-192.png
│   ├── icon-512.png
│   ├── manifest.json
│   └── sw.js
├── replit_integrations/
│   └── audio/
│       ├── audio-playback-worklet.js
│       ├── audio-utils.ts
│       ├── index.ts
│       ├── useAudioPlayback.ts
│       ├── useVoiceRecorder.ts
│       └── useVoiceStream.ts
├── src/
│   ├── components/
│   │   ├── ui/
│   │   │   ├── accordion.tsx
│   │   │   ├── alert-dialog.tsx
│   │   │   ├── alert.tsx
│   │   │   ├── aspect-ratio.tsx
│   │   │   ├── avatar.tsx
│   │   │   ├── badge.tsx
│   │   │   ├── breadcrumb.tsx
│   │   │   ├── button.tsx
│   │   │   ├── calendar.tsx
│   │   │   ├── card.tsx
│   │   │   ├── carousel.tsx
│   │   │   ├── chart.tsx
│   │   │   ├── checkbox.tsx
│   │   │   ├── collapsible.tsx
│   │   │   ├── command.tsx
│   │   │   ├── context-menu.tsx
│   │   │   ├── dialog.tsx
│   │   │   ├── drawer.tsx
│   │   │   ├── dropdown-menu.tsx
│   │   │   ├── form.tsx
│   │   │   ├── hover-card.tsx
│   │   │   ├── input-otp.tsx
│   │   │   ├── input.tsx
│   │   │   ├── label.tsx
│   │   │   ├── menubar.tsx
│   │   │   ├── navigation-menu.tsx
│   │   │   ├── pagination.tsx
│   │   │   ├── popover.tsx
│   │   │   ├── progress.tsx
│   │   │   ├── radio-group.tsx
│   │   │   ├── resizable.tsx
│   │   │   ├── scroll-area.tsx
│   │   │   ├── select.tsx
│   │   │   ├── separator.tsx
│   │   │   ├── sheet.tsx
│   │   │   ├── sidebar.tsx
│   │   │   ├── skeleton.tsx
│   │   │   ├── slider.tsx
│   │   │   ├── switch.tsx
│   │   │   ├── table.tsx
│   │   │   ├── tabs.tsx
│   │   │   ├── textarea.tsx
│   │   │   ├── toast.tsx
│   │   │   ├── toaster.tsx
│   │   │   ├── toggle-group.tsx
│   │   │   ├── toggle.tsx
│   │   │   └── tooltip.tsx
│   │   ├── pwa-install.tsx
│   │   ├── settings-panel.tsx
│   │   ├── theme-provider.tsx
│   │   ├── theme-toggle.tsx
│   │   └── tiptap-editor.tsx
│   ├── hooks/
│   │   ├── use-mobile.tsx
│   │   └── use-toast.ts
│   ├── lib/
│   │   ├── ai-service.ts
│   │   ├── queryClient.ts
│   │   ├── settings.ts
│   │   └── utils.ts
│   ├── pages/
│   │   ├── auditoria-financeira.tsx
│   │   ├── campo-livre.tsx
│   │   ├── code-assistant.tsx
│   │   ├── comparador-juridico.tsx
│   │   ├── comunicacoes-cnj.tsx
│   │   ├── consulta-corporativo.tsx
│   │   ├── consulta-pdpj.tsx
│   │   ├── consulta-processual.tsx
│   │   ├── filtrador.tsx
│   │   ├── login.tsx
│   │   ├── not-found.tsx
│   │   ├── painel-processos.tsx
│   │   ├── playground.tsx
│   │   ├── previdenciario.tsx
│   │   ├── robo-djen.tsx
│   │   ├── token-generator.tsx
│   │   └── tramitacao.tsx
│   ├── App.tsx
│   ├── index.css
│   └── main.tsx
├── capacitor.config.ts
├── index.html
├── package.json
├── PLANO.md
├── SISTEMA.md
├── tsconfig.json
├── vite.config.apk.ts
└── vite.config.ts
```

---

## STACK TECNOLOGICO DETECTADO

- **Frontend:** React + Vite, TypeScript

---

## ARQUIVOS PRINCIPAIS

- `dist/index.html` — Arquivo principal
- `index.html` — Pagina HTML principal
- `replit_integrations/audio/index.ts` — Arquivo principal
- `src/App.tsx` — Componente raiz do frontend
- `src/main.tsx` — Arquivo principal

---

## GUIA COMPLETO — O QUE CADA PARTE DO PROJETO FAZ

> Esta secao explica, em linguagem simples, o que e para que serve cada pasta e cada arquivo.

### 📁 Raiz do Projeto (pasta principal)
> Arquivos de configuracao e pontos de entrada ficam aqui.

**`PLANO.md`** _(1 linha)_
Este documento! Gerado automaticamente pelo SK Code Editor com toda a estrutura do projeto.

**`SISTEMA.md`** _(1 linha)_
Arquivo de documentacao em Markdown (texto formatado com #titulos, **negrito**, listas).

**`capacitor.config.ts`** _(1 linha)_
Arquivo de CONSTANTES/CONFIGURACAO — valores fixos usados em varios lugares do projeto.

**`index.html`** _(1 linha)_
Pagina HTML raiz do projeto. E o ponto de entrada que o browser carrega primeiro.

**`package.json`** _(1 linha)_
Registro de dependencias e scripts do projeto. Aqui ficam os comandos (npm run dev, npm start) e os pacotes instalados.

**`tsconfig.json`** _(1 linha)_
Configuracao do TypeScript. Diz para o computador como interpretar o codigo .ts e .tsx.

**`vite.config.apk.ts`** _(1 linha)_
Arquivo de CONSTANTES/CONFIGURACAO — valores fixos usados em varios lugares do projeto.

**`vite.config.ts`** _(1 linha)_
Configuracao do Vite (servidor de desenvolvimento). Define a porta, alias de caminhos e plugins usados.

---

### 📁 `.sk/`
> Pasta '.sk' — agrupamento de arquivos relacionados.

**`memoria.json`** _(1 linha)_
Arquivo de dados ou configuracao no formato JSON (chave: valor).

**`perfil-jasmim.md`** _(1 linha)_
Arquivo de documentacao em Markdown (texto formatado com #titulos, **negrito**, listas).

---

### 📁 `dist/`
> Codigo compilado/gerado automaticamente — NAO edite diretamente.

**`auditoria.html`** _(1 linha)_
Arquivo HTML — parte do projeto.

**`codigo-formatacao.txt`** _(1 linha)_
Arquivo TXT — parte do projeto.

**`comparador.html`** _(1 linha)_
Arquivo HTML — parte do projeto.

**`favicon.png`** _(1 linha)_
Arquivo de imagem.

**`icon-192.png`** _(1 linha)_
Arquivo de imagem.

**`icon-512.png`** _(1 linha)_
Arquivo de imagem.

**`index.html`** _(1 linha)_
Pagina HTML raiz do projeto. E o ponto de entrada que o browser carrega primeiro.

**`manifest.json`** _(1 linha)_
Manifesto do PWA — define nome, icone e configuracoes para instalar o app no celular.

**`sw.js`** _(1 linha)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

---

### 📁 `public/`
> Arquivos estaticos: imagens, icones, fontes, arquivos publicos.

**`auditoria.html`** _(1 linha)_
Arquivo HTML — parte do projeto.

**`codigo-formatacao.txt`** _(1 linha)_
Arquivo TXT — parte do projeto.

**`comparador.html`** _(1 linha)_
Arquivo HTML — parte do projeto.

**`favicon.png`** _(1 linha)_
Arquivo de imagem.

**`icon-192.png`** _(1 linha)_
Arquivo de imagem.

**`icon-512.png`** _(1 linha)_
Arquivo de imagem.

**`manifest.json`** _(1 linha)_
Manifesto do PWA — define nome, icone e configuracoes para instalar o app no celular.

**`sw.js`** _(1 linha)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

---

### 📁 `src/`
> Codigo-fonte principal do projeto. Nao apague esta pasta.

**`App.tsx`** _(1 linha)_
Componente RAIZ do frontend — e o pai de todos os outros componentes. Aqui ficam as rotas principais.

**`index.css`** _(1 linha)_
Arquivo de estilos visuais — cores, tamanhos, fontes, espacamentos da interface.

**`main.tsx`** _(1 linha)_
Ponto de entrada do React — monta o componente App na pagina HTML.

---

### 📁 `replit_integrations/audio/`
> Pasta 'audio' — agrupamento de arquivos relacionados.

**`audio-playback-worklet.js`** _(1 linha)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`audio-utils.ts`** _(1 linha)_
Funcoes UTILITARIAS — ferramentas reutilizaveis de uso geral no projeto.

**`index.ts`** _(1 linha)_
Arquivo INDEX — ponto de entrada da pasta, exporta tudo que esta dentro.

**`useAudioPlayback.ts`** _(1 linha)_
HOOK React personalizado para gerenciar estado/comportamento de 'audioplayback'.

**`useVoiceRecorder.ts`** _(1 linha)_
HOOK React personalizado para gerenciar estado/comportamento de 'voicerecorder'.

**`useVoiceStream.ts`** _(1 linha)_
HOOK React personalizado para gerenciar estado/comportamento de 'voicestream'.

---

### 📁 `src/components/`
> Pecas visuais reutilizaveis da interface (botoes, cards, formularios...).

**`pwa-install.tsx`** _(1 linha)_
Componente React — parte visual reutilizavel da interface do usuario.

**`settings-panel.tsx`** _(1 linha)_
Componente de CONFIGURACOES — tela onde o usuario ajusta preferencias do app.

**`theme-provider.tsx`** _(1 linha)_
Componente PROVIDER — 'fornece' dados/funcoes para todos os componentes filhos via Context API do React.

**`theme-toggle.tsx`** _(1 linha)_
Componente React — parte visual reutilizavel da interface do usuario.

**`tiptap-editor.tsx`** _(1 linha)_
Componente EDITOR — area de edicao de texto, codigo ou conteudo rico.

---

### 📁 `src/hooks/`
> Hooks React customizados — logica reutilizavel de estado e efeitos.

**`use-mobile.tsx`** _(1 linha)_
Componente React — parte visual reutilizavel da interface do usuario.

**`use-toast.ts`** _(1 linha)_
HOOK React personalizado para gerenciar estado/comportamento de '-toast'.

---

### 📁 `src/lib/`
> Funcoes auxiliares reutilizaveis em varios lugares do projeto.

**`ai-service.ts`** _(1 linha)_
Arquivo de SERVICO/API — funcoes para comunicar com o servidor ou API externa.

**`queryClient.ts`** _(1 linha)_
Arquivo de SERVICO/API — funcoes para comunicar com o servidor ou API externa.

**`settings.ts`** _(1 linha)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`utils.ts`** _(1 linha)_
Funcoes UTILITARIAS — ferramentas reutilizaveis de uso geral no projeto.

---

### 📁 `src/pages/`
> Telas completas do app — cada arquivo aqui e uma pagina navegavel.

**`auditoria-financeira.tsx`** _(1 linha)_
Componente React — parte visual reutilizavel da interface do usuario.

**`campo-livre.tsx`** _(1 linha)_
Componente React — parte visual reutilizavel da interface do usuario.

**`code-assistant.tsx`** _(1 linha)_
Componente React — parte visual reutilizavel da interface do usuario.

**`comparador-juridico.tsx`** _(1 linha)_
Componente React — parte visual reutilizavel da interface do usuario.

**`comunicacoes-cnj.tsx`** _(1 linha)_
Componente React — parte visual reutilizavel da interface do usuario.

**`consulta-corporativo.tsx`** _(1 linha)_
Componente React — parte visual reutilizavel da interface do usuario.

**`consulta-pdpj.tsx`** _(1 linha)_
Componente React — parte visual reutilizavel da interface do usuario.

**`consulta-processual.tsx`** _(1 linha)_
Componente React — parte visual reutilizavel da interface do usuario.

**`filtrador.tsx`** _(1 linha)_
Componente React — parte visual reutilizavel da interface do usuario.

**`login.tsx`** _(1 linha)_
Componente de LOGIN/AUTENTICACAO — tela de entrada com usuario e senha.

**`not-found.tsx`** _(1 linha)_
Componente React — parte visual reutilizavel da interface do usuario.

**`painel-processos.tsx`** _(1 linha)_
Componente React — parte visual reutilizavel da interface do usuario.

**`playground.tsx`** _(1 linha)_
Componente React — parte visual reutilizavel da interface do usuario.

**`previdenciario.tsx`** _(1 linha)_
Componente React — parte visual reutilizavel da interface do usuario.

**`robo-djen.tsx`** _(1 linha)_
Componente React — parte visual reutilizavel da interface do usuario.

**`token-generator.tsx`** _(1 linha)_
Componente React — parte visual reutilizavel da interface do usuario.

**`tramitacao.tsx`** _(1 linha)_
Componente React — parte visual reutilizavel da interface do usuario.

---

### 📁 `src/components/ui/`
> Componentes de UI (interface) basicos e genericos.

**`accordion.tsx`** _(1 linha)_
Componente ACCORDION — secoes que abrem/fecham ao clicar, economizando espaco na tela.

**`alert-dialog.tsx`** _(1 linha)_
Componente de NOTIFICACAO/ALERTA — mensagem temporaria que aparece na tela (ex: 'Salvo com sucesso!').

**`alert.tsx`** _(1 linha)_
Componente de NOTIFICACAO/ALERTA — mensagem temporaria que aparece na tela (ex: 'Salvo com sucesso!').

**`aspect-ratio.tsx`** _(1 linha)_
Componente React — parte visual reutilizavel da interface do usuario.

**`avatar.tsx`** _(1 linha)_
Componente AVATAR — foto ou iniciais do usuario em formato circular.

**`badge.tsx`** _(1 linha)_
Componente BADGE (etiqueta) — pequeno indicador com numero ou status (ex: '3 novas mensagens').

**`breadcrumb.tsx`** _(1 linha)_
Componente React — parte visual reutilizavel da interface do usuario.

**`button.tsx`** _(1 linha)_
Componente de BOTAO — elemento clicavel reutilizavel com estilo padrao do projeto.

**`calendar.tsx`** _(1 linha)_
Componente CALENDARIO/AGENDA — visualizacao e selecao de datas e eventos.

**`card.tsx`** _(1 linha)_
Componente CARD (cartao) — exibe uma informacao em um bloco visual com borda e sombra. Muito usado para listas de items.

**`carousel.tsx`** _(1 linha)_
Componente React — parte visual reutilizavel da interface do usuario.

**`chart.tsx`** _(1 linha)_
Componente de GRAFICO — visualizacao de dados em forma de grafico (barras, linhas, pizza...).

**`checkbox.tsx`** _(1 linha)_
Componente React — parte visual reutilizavel da interface do usuario.

**`collapsible.tsx`** _(1 linha)_
Componente React — parte visual reutilizavel da interface do usuario.

**`command.tsx`** _(1 linha)_
Componente React — parte visual reutilizavel da interface do usuario.

**`context-menu.tsx`** _(1 linha)_
CONTEXT do React — mecanismo para compartilhar dados entre componentes sem passar por props.

**`dialog.tsx`** _(1 linha)_
Componente DIALOG — caixa de dialogo que exige resposta do usuario (confirmar, cancelar...).

**`drawer.tsx`** _(1 linha)_
Componente React — parte visual reutilizavel da interface do usuario.

**`dropdown-menu.tsx`** _(1 linha)_
Componente de MENU/DROPDOWN — lista de opcoes que aparece ao clicar em um botao.

**`form.tsx`** _(1 linha)_
Componente de FORMULARIO — campos de entrada de dados (texto, selecao, etc.) com validacao.

**`hover-card.tsx`** _(1 linha)_
Componente CARD (cartao) — exibe uma informacao em um bloco visual com borda e sombra. Muito usado para listas de items.

**`input-otp.tsx`** _(1 linha)_
Componente de CAMPO DE ENTRADA — elemento de input com estilo personalizado.

**`input.tsx`** _(1 linha)_
Componente de CAMPO DE ENTRADA — elemento de input com estilo personalizado.

**`label.tsx`** _(1 linha)_
Componente React — parte visual reutilizavel da interface do usuario.

**`menubar.tsx`** _(1 linha)_
Componente de MENU/DROPDOWN — lista de opcoes que aparece ao clicar em um botao.

**`navigation-menu.tsx`** _(1 linha)_
Componente de NAVEGACAO/CABECALHO — barra superior com logo, menu e links de navegacao.

**`pagination.tsx`** _(1 linha)_
Componente React — parte visual reutilizavel da interface do usuario.

**`popover.tsx`** _(1 linha)_
Componente React — parte visual reutilizavel da interface do usuario.

**`progress.tsx`** _(1 linha)_
Componente React — parte visual reutilizavel da interface do usuario.

**`radio-group.tsx`** _(1 linha)_
Componente React — parte visual reutilizavel da interface do usuario.

**`resizable.tsx`** _(1 linha)_
Componente React — parte visual reutilizavel da interface do usuario.

**`scroll-area.tsx`** _(1 linha)_
Componente React — parte visual reutilizavel da interface do usuario.

**`select.tsx`** _(1 linha)_
Componente React — parte visual reutilizavel da interface do usuario.

**`separator.tsx`** _(1 linha)_
Componente React — parte visual reutilizavel da interface do usuario.

**`sheet.tsx`** _(1 linha)_
Componente React — parte visual reutilizavel da interface do usuario.

**`sidebar.tsx`** _(1 linha)_
Componente de BARRA LATERAL — menu ou painel que aparece na lateral da tela.

**`skeleton.tsx`** _(1 linha)_
Componente React — parte visual reutilizavel da interface do usuario.

**`slider.tsx`** _(1 linha)_
Componente React — parte visual reutilizavel da interface do usuario.

**`switch.tsx`** _(1 linha)_
Componente React — parte visual reutilizavel da interface do usuario.

**`table.tsx`** _(1 linha)_
Componente de TABELA — exibe dados em linhas e colunas.

**`tabs.tsx`** _(1 linha)_
Componente de ABAS — permite alternar entre diferentes secoes de conteudo com clique.

**`textarea.tsx`** _(1 linha)_
Componente React — parte visual reutilizavel da interface do usuario.

**`toast.tsx`** _(1 linha)_
Componente de NOTIFICACAO/ALERTA — mensagem temporaria que aparece na tela (ex: 'Salvo com sucesso!').

**`toaster.tsx`** _(1 linha)_
Componente de NOTIFICACAO/ALERTA — mensagem temporaria que aparece na tela (ex: 'Salvo com sucesso!').

**`toggle-group.tsx`** _(1 linha)_
Componente React — parte visual reutilizavel da interface do usuario.

**`toggle.tsx`** _(1 linha)_
Componente React — parte visual reutilizavel da interface do usuario.

**`tooltip.tsx`** _(1 linha)_
Componente React — parte visual reutilizavel da interface do usuario.

---

## CONTEXTO PARA IA (copie e cole para continuar o projeto)

> Use este bloco para explicar o projeto para qualquer IA ou desenvolvedor:

```
Projeto: HTML/CSS/JS (cópia) (cópia)
Tipo: Aplicacao Web Frontend (React)
Stack: React + Vite, TypeScript
Arquivos: 111 | Linhas: ~111

Estrutura principal:
  .sk/memoria.json
  .sk/perfil-jasmim.md
  PLANO.md
  SISTEMA.md
  capacitor.config.ts
  dist/auditoria.html
  dist/codigo-formatacao.txt
  dist/comparador.html
  dist/favicon.png
  dist/icon-192.png
  dist/icon-512.png
  dist/index.html
  dist/manifest.json
  dist/sw.js
  index.html
  package.json
  public/auditoria.html
  public/codigo-formatacao.txt
  public/comparador.html
  public/favicon.png
  public/icon-192.png
  public/icon-512.png
  public/manifest.json
  public/sw.js
  replit_integrations/audio/audio-playback-worklet.js
  replit_integrations/audio/audio-utils.ts
  replit_integrations/audio/index.ts
  replit_integrations/audio/useAudioPlayback.ts
  replit_integrations/audio/useVoiceRecorder.ts
  replit_integrations/audio/useVoiceStream.ts
  src/App.tsx
  src/components/pwa-install.tsx
  src/components/settings-panel.tsx
  src/components/theme-provider.tsx
  src/components/theme-toggle.tsx
  src/components/tiptap-editor.tsx
  src/components/ui/accordion.tsx
  src/components/ui/alert-dialog.tsx
  src/components/ui/alert.tsx
  src/components/ui/aspect-ratio.tsx
  src/components/ui/avatar.tsx
  src/components/ui/badge.tsx
  src/components/ui/breadcrumb.tsx
  src/components/ui/button.tsx
  src/components/ui/calendar.tsx
  src/components/ui/card.tsx
  src/components/ui/carousel.tsx
  src/components/ui/chart.tsx
  src/components/ui/checkbox.tsx
  src/components/ui/collapsible.tsx
  src/components/ui/command.tsx
  src/components/ui/context-menu.tsx
  src/components/ui/dialog.tsx
  src/components/ui/drawer.tsx
  src/components/ui/dropdown-menu.tsx
  src/components/ui/form.tsx
  src/components/ui/hover-card.tsx
  src/components/ui/input-otp.tsx
  src/components/ui/input.tsx
  src/components/ui/label.tsx
  src/components/ui/menubar.tsx
  src/components/ui/navigation-menu.tsx
  src/components/ui/pagination.tsx
  src/components/ui/popover.tsx
  src/components/ui/progress.tsx
  src/components/ui/radio-group.tsx
  src/components/ui/resizable.tsx
  src/components/ui/scroll-area.tsx
  src/components/ui/select.tsx
  src/components/ui/separator.tsx
  src/components/ui/sheet.tsx
  src/components/ui/sidebar.tsx
  src/components/ui/skeleton.tsx
  src/components/ui/slider.tsx
  src/components/ui/switch.tsx
  src/components/ui/table.tsx
  src/components/ui/tabs.tsx
  src/components/ui/textarea.tsx
  src/components/ui/toast.tsx
  src/components/ui/toaster.tsx
  src/components/ui/toggle-group.tsx
  src/components/ui/toggle.tsx
  src/components/ui/tooltip.tsx
  src/hooks/use-mobile.tsx
  src/hooks/use-toast.ts
  src/index.css
  src/lib/ai-service.ts
  src/lib/queryClient.ts
  src/lib/settings.ts
  src/lib/utils.ts
  src/main.tsx
  src/pages/auditoria-financeira.tsx
  src/pages/campo-livre.tsx
  src/pages/code-assistant.tsx
  src/pages/comparador-juridico.tsx
  src/pages/comunicacoes-cnj.tsx
  src/pages/consulta-corporativo.tsx
  src/pages/consulta-pdpj.tsx
  src/pages/consulta-processual.tsx
  src/pages/filtrador.tsx
  src/pages/login.tsx
  src/pages/not-found.tsx
  src/pages/painel-processos.tsx
  src/pages/playground.tsx
  src/pages/previdenciario.tsx
  src/pages/robo-djen.tsx
  src/pages/token-generator.tsx
  src/pages/tramitacao.tsx
  tsconfig.json
  vite.config.apk.ts
  vite.config.ts
```

---

*Plano gerado pelo SK Code Editor — 19/04/2026, 14:09:27*