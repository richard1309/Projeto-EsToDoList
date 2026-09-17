# Projeto Escopo-ToDoList

# Projeto EsToDoList

# Seção 1: Objetivo do Projeto

O EsToDoList vem com a proposta de ajudar na organização dos estudantes, sabendo que muitas vezes o excesso de tarefas pode acabar se tornando um problema. Dessa forma, o nosso projeto tem o objetivo de auxiliar e organizar o dia a dia dos estudantes, contando com uma plataforma de uso simples e intuitivo para que você possa concluir suas atribuições sem atrasos ou empecilhos.

# Seção 2: Requisitos Funcionais (RF)

- **RF01 - Cadastrar Tarefa:** Para adicionar tarefa o usuário deverá ir na aba de nova tarefa, informar o título, quando ela deve ser concluída, quando deve receber lembretes, o prazo e o status de realização
- **RF02 - Editar Tarefa** O usuário clica no item da tarefa na lista para abrir a tela de detalhes ou em um menu de ações secundárias (ícone de três pontos/configurações na barra superior ou no card). A tela exibe o formulário preenchido para alterar título, prazos, alertas e status.
- **RF03 - Excluir Tarefa** A opção de exclusão fica acessível nas opções do card ou dentro da tela de edição. O sistema exibe um diálogo de confirmação (*modal/pop-up*) antes de remover permanentemente a tarefa do banco de dados.
- **RF04 - Marcar Tarefa como Concluída** Conforme o mock-up, há um ícone de verificação circular (✓) localizado no canto direito de cada card de tarefa.
    - **Diferenciação Visual:** Ao clicar no círculo, ele é preenchido/destacado, a caixa de seleção à esquerda muda de estado e o texto da tarefa assume uma cor mais clara ou visualmente atenuada em relação às tarefas pendentes.
- **RF05 - Pesquisar/Filtrar Tarefas** A interface apresenta as ferramentas de busca diretamente na barra superior do aplicativo:
    - **Ícone de Lupa (Pesquisa):** Presente no cabeçalho (desktop e mobile), permitindo buscar tarefas por título.
    - **Ícone de Filtro/Menu (Três linhas):** Localizado na barra de ferramentas superior para filtrar por status (pendente/concluída) ou ordenação por data.
    - **Menu de Navegação Inferior (Mobile):** Permite alternar rapidamente entre a tela principal de tarefas, busca e perfil do usuário.

# Seção 3: Requisitos Não Funcionais (RNF)

Responsividade: A responsividade no site é um dos pilares fundamentais para garantir que possa ser utilizado tanto em telas maiores como em laptops ou em menores como em smartphones, garantindo o conforto e melhor usabilidade para o usuário

Disponibilidade: O sistema deve ficar disponível na maior parte do tempo para garantir que o usuário possa utilizar em todos os momentos

Compatibilidade: O sistema vai ser compatível com os principais navegadores e também com Android e IOS

# Seção 4: Fora de Escopo

Funcionalidades que ficaram fora do primeiro planejamento são recursos mais visuais no site, como calendário e poder adicionar fotos e vídeos nas tarefas. Também a possibilidade de integrar com ferramentos como Word, Canva, etc..

Essas funcionalidades ficaram de fora em primeiro momento para agilizar a conclusão do trabalho e diminuir a complexidade técnica.

# Modelo cascata

| Requisitos | Análise | Desenvolvimento | Testes | Implementação |
| --- | --- | --- | --- | --- |
| Escrever o documento de escopo com todas a funcionalidades | Definir a paleta de cores e a fonte que serão usadas no site | Escrever o código HTML da página principal | Verificar se o aplicativo funciona correctamente nos navegadores Chrome e Firefox | Corrigir um bug reportado por um usuário uma semana após o lançamento |
| Entrevistar alunos para entender como eles organizam suas tarefas hoje | Desenhar as telas do aplicativo no Figma | Programar a função em javascript que salva uma nova tarefa no navegador | Tentar “quebrar” o campo de data, inserindo um texto em ves de um número | Publicar a versão final do site em um servidor onlinepara que todos possam usar |
| Levantar as regras de negócio (o que é tarefa, campos obrigatórios, prazos e lembretes) | Especificar os fluxos do usuário (criar/editar/excluir/concluir) em um pequeno diagrama/descrição | Implementar o CRUD de tarefas (criar, listar, editar, excluir) com armazenamento local (localStorage) | Testar filtros e busca (pendente/concluída, ordenação por data, pesquisa por título) | Fazer deploy do site/app (ex.: GitHub Pages, Vercel ou Netlify) |
| Definir critérios de aceitação (ex.: “tarefa atrasada fica destacada”, “lembrete dispara no horário”) | Planejar a estrutura de dados e componentes (modelo da tarefa, telas e navegação) | Implementar lembretes/notificações (ex.: setTimeout/service worker/Notifications API) | Testar responsividade em diferentes tamanhos de tela e dispositivos | Monitorar erros/feedback e aplicar correções e pequenas melhorias pós-lançamento |

# MATRIZ DE RISCO-

![image.png](image.png)

| Risco(descrição) | Probabilidade (Baixa/Alta) | Impacto (Baixo/Alto) | Plano de ação  ( O que faremos para prevenir ou remediar) |
| --- | --- | --- | --- |
| ex: O único programador do projeto fica doente e se ausenta por uma semana | baixa | alto | Plano de ação: manter toda a documentação do projeto atualizada e sala em um local compartilhado(como o notion) para que outras pessoas possam entender o andamento |
| Risco 1: E se todo o código desenvolvido em uma aula fosse perdido porque ninguém fez commit ou enviou o projeto para GitHub | média | alto | Rotina de backup diária do código, cópias de segurança em outros locais |
| Risco 2: Internet indisponível no momento da entrega/apresentação | baixa | médio | Salvar os arquivos em pen-drive ou para modo offline |
| Risco 3: Os alunos pediram um chat para conversar sobre as tarefas durante o desenvolvimento do programa | média | média | Poderia ser feito como uma nova atualização ou versão do aplicativo |