# FocoProdutivo - Estudo & Organização

## O FocoProdutivo é uma aplicação web minimalista e totalmente responsiva, desenhada para ajudar a focar nos estudos e organizar tarefas diárias. Integra o método Pomodoro, um painel de tarefas ágil e um sistema de memorização ativa através de flashcards.

> Tudo é guardado automaticamente em tempo real na nuvem através do Firebase Firestore, garantindo que nunca perde o seu progresso.

> Funcionalidades
￼ ⏱️ Método Pomodoro: Temporizador com ciclos ajustáveis de foco, pausa curta e pausa longa com alertas sonoros integrados.
￼ 📋 Quadro de Tarefas: Adicione, filtre por status (todas, pendentes, concluídas) e defina níveis de prioridade (Alta, Média, Baixa) para as suas metas diárias.
￼ 🗂️ Flashcards: Crie perguntas e respostas organizadas por categorias para testar os seus conhecimentos de forma ativa.
￼ ☁️ Sincronização na Nuvem: Gravação automática de estatísticas, tarefas e cartões associados ao seu ID exclusivo de utilizador.

## Como usar no iPhone (como App Nativo)

> Esta aplicação foi otimizada para dispositivos móveis e pode ser instalada diretamente no ecrã do seu iPhone:
1. Abra o link do seu GitHub Pages no navegador Safari (ex: ⁠https://seu-usuario.github.io/focoprodutivo/⁠).
2. Toca no botão de Partilhar (ícone do quadrado com a seta para cima na barra inferior).
3. Role as opções e selecione Adicionar ao Ecrã Principal (Add to Home Screen).
4. Confirme tocando em Adicionar.
5. Abra a aplicação a partir do novo ícone no seu ecrã inicial para usá-lo em modo de ecrã inteiro (sem barras de navegação).

## Configuração do Banco de Dados (Firebase)

>Caso queira utilizar o seu próprio banco de dados Firestore:
1. Crie um projeto gratuito no Firebase Console.
2. Ative o Firestore Database em modo de teste.
3. Vá a Authentication > Sign-in Method e ative o fornecedor Anónimo (Anonymous) — este passo é obrigatório para evitar erros de conexão.
4. Substitua o objeto ⁠firebaseConfig⁠ no ficheiro ⁠index.html⁠ pelas chaves do seu projeto.
5. Atualize o ficheiro no seu GitHub!