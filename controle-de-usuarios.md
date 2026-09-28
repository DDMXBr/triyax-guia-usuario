## Controle de Usuários

### Grupo de Operação

**Caminho:** Controle de usuários > Grupo de Operação

Tela onde o usuário principal da conta cria e organiza os grupos de operação. Cada grupo reúne um conjunto de permissões — configurações de acesso, módulos liberados e veículos visíveis — que depois pode ser aplicado aos usuários da conta, evitando configurar cada usuário individualmente.

---

#### O que você encontra nesta tela

**Botão Novo grupo de operações**

Fica no topo da janela e abre o cadastro de um novo grupo.

**Campo de busca**

Filtra a lista de grupos pelo nome conforme você digita.

**Lista de grupos**

Tabela com o **Nome** de cada grupo cadastrado e, ao lado, os botões **Editar** (ícone de lápis) e **Remover** (ícone de lixeira). A lista é paginada e pode ser ordenada pelo nome.

**Janela de configuração do grupo**

Aberta ao criar ou editar um grupo. No topo fica o nome do grupo, que pode ser informado em mais de um idioma. Abaixo, cada solução disponível para a conta aparece como um painel expansível. O painel da solução principal é exibido com o nome do sistema configurado para o seu domínio e possui três abas: **Configurações do usuário**, **Módulos** e **Veículos**.

---

#### Funcionalidades

**Criar um grupo de operação**

Cadastra um novo grupo com o conjunto de permissões desejado.

Como usar:

1. Clique em **Controle de usuários** na barra superior e escolha **Grupo de Operação**.
2. Clique em **Novo grupo de operações**.
3. Informe o nome do grupo em pelo menos um idioma.
4. Expanda o painel da solução e ajuste as abas **Configurações do usuário**, **Módulos** e **Veículos**.
5. Clique em **Salvar**.

> **Dica:** O botão **Salvar** só fica disponível depois que o grupo tiver um nome preenchido em algum idioma.

**Editar um grupo de operação**

Altera o nome ou as permissões de um grupo já existente.

Como usar:

1. Localize o grupo na lista (use o campo **Buscar** se necessário).
2. Clique no ícone de lápis (**Editar**) na linha do grupo.
3. Faça as alterações desejadas e clique em **Salvar**.

> **Dica:** Para desistir das alterações, clique em **Cancelar** ou no ícone de fechar — nada é gravado.

**Configurar as permissões do usuário**

Na aba **Configurações do usuário** você define o comportamento padrão de quem pertence ao grupo.

Como usar:

1. Abra a janela de configuração do grupo e expanda o painel da solução.
2. Na aba **Configurações do usuário**, informe a **Latitude do mapa** e a **Longitude do mapa** para definir o ponto inicial do mapa.
3. Marque as permissões desejadas (autenticação de dois fatores, acesso ao item Controle, edição de veículos, movimentação entre pastas, acesso a todos os veículos).
4. Escolha as **Áreas de Interesse**, **Pontos de Interesse** e **Rotas programadas** que o grupo poderá ver.

> **Dica:** Nas listas de áreas, pontos e rotas há um campo de busca e a opção **Selecionar/Deselecionar todos** para agilizar a seleção.

**Liberar módulos**

Na aba **Módulos** você escolhe quais serviços do sistema ficam disponíveis para o grupo.

Como usar:

1. Abra a aba **Módulos**.
2. Marque os módulos desejados e, dentro de cada um, os itens específicos que devem ficar liberados.
3. Use **Selecionar todos** ou **Deselecionar todos** para marcar ou desmarcar tudo de uma vez.

> **Dica:** O módulo de rastreamento é sempre liberado e não pode ser desmarcado.

**Definir os veículos do grupo**

Na aba **Veículos** você escolhe quais veículos os usuários do grupo poderão acompanhar.

Como usar:

1. Abra a aba **Veículos**.
2. Marque, na árvore de pastas, os veículos ou pastas desejados.
3. Clique em **Salvar**.

> **Dica:** Se a opção **Permitir acesso à todos os veículos** estiver marcada em **Configurações do usuário**, a árvore não é exibida. Para escolher veículos específicos, desmarque essa opção primeiro.

**Remover um grupo de operação**

Exclui um grupo que não é mais utilizado.

Como usar:

1. Localize o grupo na lista.
2. Clique no ícone de lixeira (**Remover**).
3. Confirme a operação na mensagem exibida.

> **Dica:** O botão de remover fica desabilitado enquanto houver usuários vinculados ao grupo. Desvincule os usuários antes de removê-lo.

---

#### Campos e Filtros

| Campo / Filtro | O que faz |
|---|---|
| Buscar | Filtra a lista de grupos pelo nome |
| Nome | Nome do grupo, que pode ser informado em mais de um idioma |
| Latitude do mapa / Longitude do mapa | Ponto em que o mapa abre para os usuários do grupo |
| Habilitar Autenticação de dois fatores (E-mail) | Exige um código enviado por e-mail no acesso |
| Permitir acesso ao item de 'Controle' | Libera o item Controle no menu |
| Permitir editar veículos | Permite alterar os dados dos veículos |
| Permitir movimentação de veículos entre pastas | Permite mover veículos de uma pasta para outra |
| Permitir acesso à todos os veículos | Libera toda a frota, sem precisar escolher veículo a veículo |
| Permissão de Áreas de Interesse | Áreas de interesse visíveis para o grupo |
| Permissão de Pontos de Interesse | Pontos de interesse visíveis para o grupo |
| Permissão de Rotas programadas | Rotas programadas visíveis para o grupo |

[↑ Voltar ao Índice](index.md#índice)

---

### Logs

**Caminho:** Controle de usuários > Logs

Tela que registra as ações realizadas pelos usuários da conta, como acessos e alterações de configuração. Permite consultar quem fez o quê, quando e em qual tela, além de exportar o resultado para planilha.

---

#### O que você encontra nesta tela

**Painel Filtrar**

Painel expansível no topo com o período da busca, a ordenação por data, os filtros de **Operação**, **Solução** e **Usuário**, e os botões **Buscar** e **Exportar**.

**Tabela de registros**

Lista as ações encontradas com as colunas **Data**, **Operação**, **Solução**, **Tela**, **Usuário**, **E-mail** e endereço de acesso de rede (**IP**). Cada linha tem um botão para ver o registro completo. A tabela é paginada, com 25, 50, 75 ou 100 registros por página.

---

#### Funcionalidades

**Pesquisar ações por período**

Consulta as ações realizadas em um intervalo de tempo.

Como usar:

1. Clique em **Controle de usuários** na barra superior e escolha **Logs**.
2. Clique no ícone de relógio (**Pesquisar Período**) ou no quadro **De / Até** e escolha a **Data Inicial** e a **Data Final**, com os respectivos horários.
3. Se quiser, refine com **Operação**, **Solução** ou **Usuário**.
4. Clique em **Buscar**.

> **Dica:** A seta ao lado do relógio (**De (Até agora)**) oferece atalhos prontos — últimos 5, 15 ou 30 minutos, 1, 2 ou 8 horas, 1 dia, 1 semana ou 1 mês.

**Ordenar por data**

Define se os registros aparecem do mais recente para o mais antigo ou o contrário.

Como usar:

1. No painel **Filtrar**, localize os dois botões de ordenação.
2. Escolha **Data (mais recente primeiro)** ou **Data (mais antiga primeiro)**.
3. Clique em **Buscar** para aplicar.

> **Dica:** A ordenação vale também para a exportação.

**Filtrar por um usuário a partir da tabela**

Adiciona rapidamente um usuário ou e-mail ao filtro, sem precisar digitá-lo.

Como usar:

1. Passe o mouse sobre a célula **Usuário** ou **E-mail** de um registro.
2. Clique no ícone de funil que aparece.
3. Clique em **Buscar** para ver apenas as ações daquele usuário.

> **Dica:** Útil para investigar, a partir de uma ação suspeita, tudo o que o mesmo usuário fez no período.

**Visualizar o registro completo**

Mostra todos os detalhes de uma ação específica.

Como usar:

1. Localize o registro na tabela.
2. Clique no ícone da última coluna (**Visualizar Log**).
3. Consulte os detalhes na janela que se abre e feche-a ao terminar.

> **Dica:** Os detalhes trazem informações que não cabem na tabela, como os dados alterados na operação.

**Exportar para planilha**

Gera um arquivo Excel com os registros que atendem aos filtros atuais.

Como usar:

1. Ajuste o período e os filtros desejados.
2. Clique em **Exportar**.
3. Aguarde o download do arquivo.

> **Dica:** A exportação traz até 5.000 registros por arquivo e leva o logotipo da conta que você está usando. Para períodos com muitas ações, divida a exportação em intervalos menores.

---

#### Campos e Filtros

| Campo / Filtro | O que faz |
|---|---|
| Data Inicial / Data Final | Início e fim do período pesquisado, com data e hora |
| De (Até agora) | Atalhos de período contados a partir do momento atual |
| Ordenação por data | Mostra primeiro os registros mais recentes ou os mais antigos |
| Operação | Um ou mais tipos de ação a considerar |
| Solução | Restringe a busca a uma solução específica |
| Usuário | Nome de usuário ou e-mail de quem realizou a ação |

[↑ Voltar ao Índice](index.md#índice)

---
