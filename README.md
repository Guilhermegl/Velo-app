# ⚡ Velo — Workspace Pessoal

> "A disciplina é a ponte entre onde você está e onde quer estar."

Velo é um workspace pessoal completo, construído em um único arquivo HTML.  
Sem instalação, sem backend, sem cadastro. Abre no navegador e funciona.

---

## 🎯 Para quem é o Velo?

| Modo | Perfil | O que muda |
|---|---|---|
| 📚 Estudo | Concurseiros, estudantes | Meta de sessões, simulados, cronograma, countdown da prova |
| 💼 Trabalho | Profissionais, freelancers | Painel de projetos, mensagens de foco profissional |
| 🌿 Pessoal | Uso geral | Diário, rastreador de hábitos, mensagens de bem-estar |

---

## ✨ Funcionalidades

### ⚡ Captura Rápida
- Anote qualquer ideia em segundos
- Tags personalizadas para organizar
- Filtro por tag com um clique
- Fixar notas importantes

### ✅ Tarefas
- Tarefas únicas, diárias ou semanais
- Recorrentes resetam automaticamente (diárias à meia-noite, semanais toda segunda)
- Indicador de tarefas atrasadas

### 📅 Calendário
- Visualização mensal completa
- Clique em qualquer dia para adicionar tarefa diretamente

### 🍅 Pomodoro
- Timer configurável (padrão 25 min foco / 5 min pausa)
- Modo Foco — bloqueia a tela até o tempo acabar
- Streak de dias consecutivos
- Celebração visual ao bater a meta diária
- Som de notificação ao completar sessão

### 🃏 Flashcards
- Crie decks de pergunta e resposta
- Marque como "sei" ou "não sei"
- Progresso do deck em tempo real

### 🎯 Simulados (modo Estudo)
- Registre matéria, banca, acertos e total
- Cálculo automático de percentual
- Histórico completo com filtro por matéria

### 🗓 Cronograma (modo Estudo)
- Cronograma semanal visual
- Blocos coloridos por matéria com horário de início e fim

### 📁 Projetos (modo Trabalho)
- Crie projetos com emoji, nome e prazo
- Barra de progresso visual em percentual

### 📓 Diário (modo Pessoal)
- Uma entrada por dia em texto livre
- Histórico das últimas 7 entradas

### 🌿 Rastreador de Hábitos (modo Pessoal)
- Crie hábitos com emoji personalizado
- Contador de dias acumulados 🔥

### 📚 Espaços e Páginas
- Crie espaços e páginas com editor completo
- Blocos: texto, subtítulo, toggle, checklist, callout, citação, código, imagem
- Toggle infinitamente aninhável

### 🗃 Boards
- Modos: Tabela, Kanban e Gráficos
- Kanban com colunas por status
- 4 tipos de gráfico: Barra, Linha, Área, Donut

### 🔍 Busca Global
- Busca em tempo real por capturas, tarefas e páginas

---

## 🧠 Inteligência Emocional

Todo dia ao abrir o app, o Velo pergunta como você está:

- 😴 Cansado → sugere sessões menores
- 🎯 Focado → encoraja atacar o conteúdo mais difícil
- 😰 Ansioso → orienta a quebrar em pedaços pequenos
- 😄 Animado → incentiva a aproveitar a energia

---

## 🔔 Notificações e Alertas

- 📲 Lembrete às 19h — notificação nativa do navegador
- 🚨 Countdown da prova — contagem regressiva na sidebar
- 😤 Accountability às 21h — cobrança se você começou mas não terminou a meta
- 📊 Relatório semanal automático todo domingo
- 🏆 15 conquistas desbloqueáveis por uso

---

## 💾 Como os dados são salvos

Todos os dados ficam no **localStorage do navegador**, no seu próprio dispositivo. Nenhuma informação é enviada para servidores.

| ✅ Vantagens | ⚠️ Atenção |
|---|---|
| Funciona 100% offline | Limpar cache apaga os dados |
| Dados 100% privados | Cada navegador tem dados separados |
| Zero cadastro | Aba anônima não persiste dados |

> 💡 **Recomendação:** exporte o backup `.json` regularmente nas ⚙️ Configurações.

---

## 📱 Como usar

**Opção 1 — Acessar online**  
Abra o link no navegador e use direto. Nenhuma instalação necessária.

**Opção 2 — Instalar como PWA (recomendado)**  
No Chrome: Menu (3 pontos) → "Adicionar à tela inicial" → o app abre em tela cheia e funciona offline.

**Opção 3 — Rodar localmente**  
Baixe o repositório, abra a pasta e clique duas vezes no arquivo `index.html`.

---

## 🛠️ Tecnologias

| Tecnologia | Uso |
|---|---|
| HTML5 | Estrutura do app |
| CSS3 | Visual, animações e temas |
| JavaScript ES6 | Toda a lógica (237 funções) |
| localStorage | Persistência de dados |
| Service Worker | Funcionamento offline |
| Web App Manifest | Instalação como PWA |

> 100% frontend. Arquivo único de 254KB. Zero dependências.

---

## 📁 Estrutura do projeto

velo/
├── index.html      # App completo (único arquivo)
├── manifest.json   # PWA manifest
├── netlify.toml    # Configuração de redirecionamento
└── README.md       # Este arquivo

---

---

## 🔐 Privacidade

Este app não coleta nenhum dado. Não há cadastro, login, envio para servidores, analytics ou cookies de terceiros.  
Seus dados ficam **exclusivamente no seu dispositivo**.

---

## 📝 Licença

MIT — use, modifique e distribua livremente.

---

Desenvolvido por **Guilherme Lima**.

> Velo — porque velocidade sem direção é só agitação.
