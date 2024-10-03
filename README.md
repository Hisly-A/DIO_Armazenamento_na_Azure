# DIO - Armazenamento na Azure
Dominando o Armazenamento na Azure


## Criação de Conta de Armazenamento na Azure

Abra o portal da [`Azure`](https://portal.azure.com), pesquise por **Contas de armazenamento** e clique em **+ Criar**.



Na próxima tela preencha os campos do grupo **Detalhes do projeto**.



Após preencha os campos do grupo **Detalhes da instância**



Repare nas observações sobre o campo **Nome da conta de armazenamento**:



Repare nas opções do campo **Desempenho**: 



Observe também as opções disponíveis no campo **Redundância**: 



Após preencher todas as opções necessárias clique em **Avançar: Avançado**:



Na aba **Avançado** selecione as opções necessárias no grupo **Segurança**:



Preencha os demais campos e clique em **Avançar: Rede**:



Preencha os campos necessários no grupo **Conectividade de rede**:



Após finalizar o preenchimento das informações clique na opção **Avançar: Proteção de dados**.



No grupo **Recuperação** desmarque todas as opções, pois como se trata de um teste não queremos que o blob seja mantido por 7 dias após a exclusão, e assim evitar cobrança:



Clique em **Avançar: Criptografia**:



Na aba **Criptografia** mantenha as opções padrões e clique em **Avançar: Marcas**:



Caso não deseje criar tags, clique em **Avançar: Examinar**:



Nesta última aba clique em **Criar**:



## Recursos da Conta de Armazenamento na Azure

Abra a conta de armazenamento criada:



No menu lateral clique em **Compartilhamentos de arquivos** e após clique em **+ Compartilhamento de arquivos**:



Na próxima tela repare nas opções do campo **Camada**:



Clique na opção **Avançar: Backup**:



Altere as opções pré-definidas de backup caso necessário, e clique em **Avançar: Examinar**:



Na aba **Revisar + criar** clique em **Criar**:



Acesse o recurso criado:



Clique em **Conectar** para verificar as opções diponíveis:



Clique em **Mostrar script** para visualizar o script completo para fazer o acesso a partir de uma máquina:



Repare que a conexão funciona também para *Linux* e *macOS*:



Voltando para a tela inicial da conta de armazenamento clique em **Filas** no menu lateral e em **+ Fila** para criar uma nova:



Informe o nome da fila e clique em **OK**:



Verifique que para a fila de armazenamento criada também foi criada uma URL:



Abra a fila criada e clique em **+ Adicionar mensagem** caso queira adicionar uma mensagem à fila:



De volta à conta de armazenamento, clique em **Tabelas**, **+ Tabela**, informe um nome para a tabela e clique em **OK**:



Verifique que para a tabela também foi criada uma URL:



Verifique as opções disponíveis para configuração da **Política de acesso** à tabela:



A opção **IAM (Controle de acesso)** é para usuários em específico:



A parte de **Contêineres** e **Compartilhamento de arquivos** são as mais utilizadas nas contas de armazenamento:



## Migrações para a Azure

Pesquise na barra de pesquisa por **Migrações para Azure**:



Observe as opções diponíveis:



Na primeira opção clique em **Descobrir, avaliar e migrar**:



Na próxima tela clique em **Criar projeto**:



Preencha as informações necessárias e clique em **Criar**:



Aguarde a criação e após verifique as opções disponíveis:



No menu lateral clique em **Data Box** e veja a descrição das opções disponíveis:



Preencha os campos e clique em **Aplicar**:



Obeserve as opções de tamanhos disponíveis:



Na opção Import/Export Job clique em **Selecionar** e observe as opções disponíveis na tela que se abre:



Repare também no aviso de que o Azure Data Box não está disponível para a assinatura selecionada:



26


## Links utilizados

- https://learn.microsoft.com/pt-br/training/modules/describe-cloud-service-types/2-describe-infrastructure-service
