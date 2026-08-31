# Novidades

Registro do que foi adicionado ou alterado no sistema, tela a tela.

---

## 31/08/2026

**Gestão de Campo — Mapa Online**

- Novo **Painel de Status** recolhível à esquerda do mapa, com as 10 situações dos veículos e a contagem **selecionados / frota** em cada linha.
- Clicar em uma situação filtra o mapa por ela; várias situações podem ser combinadas. Botões flutuantes para mostrar os rótulos por extenso e para limpar o filtro.
- Veículos que mudam de situação passam a ser atualizados individualmente no mapa, sem recarregar toda a frota — o botão de atualização automática deixou de ser necessário.
- Novas opções **Reenviar Bloqueio** e **Reenviar Desbloqueio** no menu do veículo, liberadas após o intervalo configurado na conta, enquanto o comando ainda estiver aguardando confirmação.

**Gestão de Campo — Quadro de Avisos**

- Os alertas de parada foram separados em dois filtros distintos: **Parada em andamento** e **Alerta crítico de parada** (fim de ciclo). Antes os dois compartilhavam o mesmo rótulo.
- Avisos com câmera cadastrada mas sem transmissão localizada passam a exibir um aviso de câmeras não encontradas, mantendo os dados do evento visíveis.

**Gestão de Campo — Quadro de Avisos Telemetria**

- Novo filtro **Sem comunicação** em **Eventos Gerados pelo Sistema**, para os veículos que deixaram de reportar posição.

**Gestão de Campo — Rotas Percorridas**

- Os marcadores de aviso ao longo da rota voltaram a trazer os dados corretos do evento.

**Manutenção — Preventiva e Corretiva**

- Novos filtros de **Data Inicial** e **Data Final** nas duas telas, com busca, paginação e ordenação processadas no servidor.
- Preventiva: nova coluna **Data de Início da Manutenção**, que é o campo consultado pelo filtro de período.
- Corretiva: datas de início e fim reunidas na coluna **Período**, e a seleção de veículos passou a usar a mesma janela da preventiva.
- A exportação passa a considerar todos os registros filtrados, e não apenas a página exibida, avisando quando o arquivo sai parcial.
- Tipo de horímetro, e-mail de aviso e marcação de repetição voltaram a aparecer nos detalhes e a acompanhar a manutenção quando ela é reportada.

**Abastecimento**

- Nova coluna **Horímetro Reportado** na lista e nas exportações. A leitura não informada aparece como "----" em vez de 0,00.
- A **observação** do abastecimento passou a ser exportada como última coluna nos arquivos PDF e Excel.

**Relatórios — Relatórios Agendados**

- Agendamentos podem ser montados por **grupos de veículos**, além de veículos individuais, com nova coluna **Tipo** na listagem.

---

## 30/07/2026

**Gestão de Campo — Quadro de Avisos**

- Nova coluna **Origem do Alerta** na tabela, indicando se o aviso partiu de um Módulo, do Videomonitoramento ou do Sistema. A tabela pode ser ordenada por essa coluna.
- Avisos de câmera (Hikvision/Jimi) sem vídeo gravado do momento do evento agora exibem a imagem capturada no lugar do player, com opção de download.
- A tabela de avisos não desaparece mais quando a busca não encontra nada — passa a exibir a mensagem "Nenhum registro encontrado".

**Manutenção**

- Importação de peças/itens por planilha: linhas com o campo **Código** vazio são ignoradas automaticamente, o erro de validação é destacado apenas no campo inválido da linha, e agora é possível remover um item da prévia antes de salvar.
- Campo **Tipo** em Manutenção Preventiva passou a usar estratégias de manutenção (Baseada em Uso, Baseada em Tempo, Baseada em Condição, Preditiva, Prescritiva) em vez de categorias de peça.
- Campo **Tipo** em Manutenção Corretiva agora é **Planejada** ou **Não Planejada**.
- A busca por **Oficina** passa a considerar também áreas cadastradas como concessionária.

**Videomonitoramento**

- Veículos sem dados recentes de comunicação aparecem desabilitados na lista de seleção (e um grupo inteiro fica desabilitado quando nenhum veículo dele está comunicando).

---
