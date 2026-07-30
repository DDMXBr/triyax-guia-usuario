## Checklists

### Consultar Checklists

**Caminho:** Checklists > Consultar Checklists

Esta tela permite consultar e exportar os registros de checklist realizados pelos motoristas nos veículos da frota. É possível visualizar na tela os itens verificados, o resultado de cada item e os arquivos anexados, ou gerar um relatório em PDF ou Excel para análise posterior.

---

#### O que você encontra nesta tela

**Abas de navegação**

A tela possui duas abas principais:

- **Checklists** — aba de consulta direta, com filtros de período e seleção de veículo para visualização imediata dos registros na tela.
- **Relatórios Processados** — aba que lista os relatórios gerados em segundo plano (PDF e Excel), disponíveis para download após o processamento.

**Painel de Filtros (aba Checklists)**

Painel expansível no topo da aba **Checklists**. Contém os campos de data inicial e data final, o botão de seleção de veículo e os botões de ação **Visualizar** e **Exportar**.

**Área de Resultados (aba Checklists)**

Exibida abaixo do painel de filtros após clicar em **Visualizar**. Mostra as informações do veículo selecionado (grupo, categoria, placa e identificação) seguidas de uma ou mais tabelas com todos os registros de checklist no período consultado.

---

#### Funcionalidades

**Visualizar checklists na tela**

Exibe diretamente na tela todos os registros de checklist realizados por um veículo no período informado, com o resultado de cada item verificado.

Como usar:

1. No painel de filtros, defina o **Data Inicial** e o **Data Final** do período que deseja consultar.
2. Clique no botão de ícone de veículo (ícone de carros) para abrir a janela de seleção de veículos. Selecione **exatamente um veículo** e confirme.
3. Clique no botão **Visualizar**. Os registros serão carregados abaixo do painel, organizados em tabelas por checklist.

> **Dica:** A visualização direta na tela está disponível apenas para um veículo por vez. Para consultar múltiplos veículos ao mesmo tempo, utilize a função de exportação.

**Exportar relatório em PDF**

Gera um arquivo PDF com todos os registros de checklist dos veículos selecionados no período informado e disponibiliza para download na aba **Relatórios Processados**.

Como usar:

1. Defina o **Data Inicial** e o **Data Final** no painel de filtros.
2. Clique no botão de ícone de veículo para abrir a seleção. Escolha um ou mais veículos (até 50) e confirme.
3. Clique no botão **Exportar** e selecione a opção **PDF** no menu exibido.
4. Aguarde a confirmação de envio e acesse a aba **Relatórios Processados** para baixar o arquivo quando estiver pronto.

> **Dica:** O limite de veículos para exportação é de 50. Ao selecionar mais do que isso, o sistema exibirá um aviso e o relatório não será gerado.

**Exportar relatório em Excel**

Gera um arquivo Excel com os registros de checklist e disponibiliza para download na aba **Relatórios Processados**.

Como usar:

1. Defina o **Data Inicial** e o **Data Final** no painel de filtros.
2. Clique no botão de ícone de veículo para abrir a seleção. Escolha um ou mais veículos (até 50) e confirme.
3. Clique no botão **Exportar** e selecione a opção **Excel** no menu exibido.
4. Aguarde a confirmação de envio e acesse a aba **Relatórios Processados** para baixar o arquivo quando estiver pronto.

> **Dica:** O formato Excel é ideal para fazer análises comparativas entre veículos ou cruzar os dados de checklist com outras planilhas da operação.

**Visualizar arquivos e fotos anexadas ao item de checklist**

Abre uma janela com as imagens ou arquivos que o motorista anexou a um item específico durante a realização do checklist.

Como usar:

1. Após visualizar os checklists na tela, localize na tabela um item que possua o ícone de clipe (indicador de arquivo anexado) na coluna **Foto Anexada**.
2. Clique no ícone de clipe desse item. Uma janela será aberta exibindo as imagens anexadas.
3. Na janela, clique em uma miniatura na coluna lateral para ampliar a imagem na área principal.
4. Para salvar todas as imagens, clique no botão **Baixar Todas as Imagens** na parte inferior da janela.

> **Dica:** A coluna de foto anexada só exibe o ícone nos itens que realmente possuem arquivos. Itens sem anexo não mostram o ícone e não permitem abertura da galeria.

---

#### Campos e Filtros

| Campo / Filtro        | O que faz                                                                                                                   |
|-----------------------|-----------------------------------------------------------------------------------------------------------------------------|
| **Data Inicial**      | Define o início do período a ser consultado; o padrão ao abrir a tela são os últimos 15 dias                                |
| **Data Final**        | Define o fim do período a ser consultado; o padrão é a data atual                                                          |
| **Seleção de Veículo** | Abre a janela para escolher os veículos da consulta; aceita um veículo para visualização e até 50 para exportação          |

[↑ Voltar ao Índice](index.md#índice)

---

### Configurar Checklists

**Caminho:** Checklists > Configurar Checklists

Esta tela permite criar, editar e gerenciar os modelos de checklist utilizados pelos motoristas durante a operação. Cada configuração define quais itens serão verificados, o tipo de equipamento utilizado e quais veículos receberão o checklist.

---

#### O que você encontra nesta tela

**Lista de Configurações**

Tabela principal que exibe todas as configurações de checklist cadastradas. Cada linha mostra o nome da configuração e botões de ação para editar ou gerenciar os veículos vinculados. À esquerda de cada linha há uma caixa de seleção para marcar configurações que serão excluídas.

**Barra de Ações**

Localizada acima da tabela. Contém o botão **Nova Configuração de Checklist** para iniciar o cadastro de uma nova configuração e o ícone de lixeira para apagar as configurações marcadas na lista.

**Janela de Criação / Edição**

Aberta ao clicar em **Nova Configuração de Checklist** ou no ícone de editar de uma configuração existente. Apresenta:

- Aba **Configuração** — campos do checklist: nome, tipo de equipamento e lista de itens a serem verificados.
- Aba **Veículos** — seletor de veículos para vincular à nova configuração (disponível somente na criação).

---

#### Funcionalidades

**Criar nova configuração de checklist**

Cadastra um novo modelo de checklist com nome, tipo de equipamento, itens e veículos vinculados.

Como usar:

1. Clique no botão **Nova Configuração de Checklist** no topo da tela.
2. Na janela que abrir, preencha o campo **Nome** com um nome descritivo para o checklist.
3. Selecione o **Tipo** de equipamento: **Teclado KNOV** (para terminais físicos) ou **Smartphone / Tablet** (para aplicativos móveis).
4. Na lista de itens abaixo, edite os itens existentes e adicione novos conforme necessário.
5. Clique na aba **Veículos**, selecione na árvore os veículos que receberão este checklist e clique em **Salvar**.

> **Dica:** O tipo de equipamento determina o limite de caracteres do nome de cada item — 16 caracteres para Teclado KNOV e 40 para Smartphone/Tablet. Ao trocar o tipo para KNOV, informações detalhadas dos itens (descrição, imagens, documentos) são limpas automaticamente.

**Editar configuração existente**

Altera o nome, tipo, itens ou notificações de uma configuração já cadastrada.

Como usar:

1. Localize a configuração na lista e clique no ícone de lápis na coluna de ações.
2. Na janela que abrir, altere os campos desejados na aba **Configuração**.
3. Clique em **Salvar** para confirmar as alterações.

> **Dica:** Ao editar uma configuração existente, a aba **Veículos** não é exibida. Para alterar os veículos vinculados, use o ícone de veículos diretamente na lista principal.

**Gerenciar veículos vinculados**

Adiciona ou remove veículos associados a uma configuração de checklist já cadastrada.

Como usar:

1. Na lista de configurações, clique no ícone de veículos (ícone de carros) na linha da configuração desejada.
2. Na janela que abrir, marque ou desmarque os veículos desejados na árvore de seleção.
3. Confirme a seleção para salvar os vínculos.

> **Dica:** Um mesmo veículo pode estar vinculado a apenas uma configuração de checklist por vez. Revisar os vínculos periodicamente garante que os motoristas recebam o checklist correto.

**Adicionar e reordenar itens do checklist**

Inclui novos itens de verificação no checklist e ajusta a ordem em que serão apresentados ao motorista.

Como usar:

1. Na janela de criação ou edição, clique no botão **+** abaixo da lista de itens para adicionar um novo item.
2. Digite o nome do item no campo **Mensagem** que aparece na linha criada.
3. Para reordenar, clique nas setas de subir ou descer (▲ / ▼) à esquerda do nome do item.

> **Dica:** O checklist sempre começa com um item de horímetro ou hodômetro (selecionável) e termina com o item fixo **Fim de Checklist**, que não pode ser removido ou reordenado. O limite máximo é de 49 itens verificáveis.

**Configurar detalhes de um item (somente Smartphone / Tablet)**

Define propriedades avançadas de um item: descrição explicativa, obrigatoriedade de foto e marcação como impeditivo.

Como usar:

1. Na lista de itens, clique no ícone de editar (lápis) na linha do item desejado.
2. Na janela que abrir, preencha o campo **Informações** com instruções ou orientações para o motorista.
3. Marque **Impeditivo** se o item não conforme deve bloquear o prosseguimento da operação.
4. Marque **Foto obrigatória para conforme** e/ou **Foto obrigatória para não conforme** conforme a necessidade.
5. Use os botões de documento e imagem para anexar arquivos de referência ao item.
6. Clique em **Concluir** para salvar as configurações do item.

> **Dica:** Itens marcados como **Impeditivo** são destacados na coluna correspondente da lista com um ícone de confirmação, facilitando a revisão da configuração.

**Configurar notificação por e-mail para itens não conformes**

Define endereços de e-mail que receberão alertas sempre que um item do checklist for marcado como não conforme pelo motorista.

Como usar:

1. Na janela de criação ou edição, role até a seção **Notificar item não conforme** abaixo da lista de itens.
2. No campo **E-mail**, digite o endereço desejado e pressione **Enter** ou **;** (ponto e vírgula) para confirmar.
3. Repita para adicionar mais endereços. Para remover um e-mail, clique no **x** ao lado dele.
4. Clique em **Salvar** para gravar a configuração com as notificações definidas.

> **Dica:** É possível cadastrar múltiplos endereços de e-mail. Os alertas são enviados automaticamente sempre que o motorista registrar um item como não conforme durante a realização do checklist.

**Apagar configurações**

Remove permanentemente uma ou mais configurações da lista.

Como usar:

1. Marque a caixa de seleção à esquerda das configurações que deseja apagar. Para selecionar todas, use a caixa no cabeçalho da tabela.
2. Clique no ícone de lixeira na barra acima da tabela.
3. Confirme a exclusão na janela de confirmação exibida.

> **Dica:** A exclusão é permanente. Os veículos que estavam vinculados à configuração apagada deixarão de receber o checklist correspondente.

---

#### Campos e Filtros

| Campo / Filtro | O que faz |
|---|---|
| **Nome** | Identifica a configuração de checklist; use um nome que indique o tipo de operação ou veículo |
| **Tipo** | Define o equipamento que os motoristas utilizarão: Teclado KNOV (terminal físico) ou Smartphone / Tablet (aplicativo) |
| **Mensagem (item)** | Nome do item de verificação que será exibido ao motorista durante o checklist |
| **Código (item)** | Número sequencial gerado automaticamente para cada item; atualizado ao reordenar |
| **Impeditivo** | Indica se o item não conforme impede o prosseguimento da operação |
| **Documentos / Imagens** | Quantidade de arquivos de referência anexados ao item (visível somente para Smartphone / Tablet) |
| **E-mail** | Endereços que receberão alertas de itens não conformes |
| **Informações (detalhe do item)** | Texto explicativo exibido ao motorista como orientação para o item |
| **Foto obrigatória para conforme** | Exige que o motorista tire uma foto quando marcar o item como conforme |
| **Foto obrigatória para não conforme** | Exige que o motorista tire uma foto quando marcar o item como não conforme |

[↑ Voltar ao Índice](index.md#índice)

---

