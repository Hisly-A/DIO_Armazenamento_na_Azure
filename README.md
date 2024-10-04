# DIO - Armazenamento na Azure
Dominando o Armazenamento na Azure


## Criação de Conta de Armazenamento na Azure

Abra o portal da [`Azure`](https://portal.azure.com), pesquise por **Contas de armazenamento** e clique em **+ Criar**.

![AZ06-01](https://github.com/user-attachments/assets/061596e3-1e6d-4367-9e3a-c15face1b510)

![AZ06-02](https://github.com/user-attachments/assets/aa8eeca4-32ea-42e5-9f8c-808be866ff50)

Na próxima tela preencha os campos do grupo **Detalhes do projeto**.

![AZ06-03](https://github.com/user-attachments/assets/9f416219-0c4a-4c72-a585-79803e8a6096)

Após preencha os campos do grupo **Detalhes da instância**

![AZ06-04](https://github.com/user-attachments/assets/a2e2d11e-0a7c-4d58-91f5-d11aefe75d82)

Repare nas observações sobre o campo **Nome da conta de armazenamento**:

![AZ06-05](https://github.com/user-attachments/assets/286a5521-7f79-480c-ad96-9c1c864735b8)

Repare nas opções do campo **Desempenho**: 

![AZ06-06](https://github.com/user-attachments/assets/77e21d77-487e-4fd4-967d-99fe39cece90)

Observe também as opções disponíveis no campo **Redundância**: 

![AZ06-07](https://github.com/user-attachments/assets/fb473c30-4192-44da-8385-57ee93aa73c6)

Após preencher todas as opções necessárias clique em **Avançar: Avançado**:

![AZ06-08](https://github.com/user-attachments/assets/eb7e8602-a130-4c14-8467-45b2a9884eec)

Na aba **Avançado** selecione as opções necessárias no grupo **Segurança**:

![AZ06-09](https://github.com/user-attachments/assets/c786e968-7813-491e-9f35-acf84fdeb249)

Preencha os demais campos e clique em **Avançar: Rede**:

![AZ06-10](https://github.com/user-attachments/assets/1d183a33-d62e-4b84-b28e-de0a2a46e05d)

Preencha os campos necessários no grupo **Conectividade de rede**:

![AZ06-11](https://github.com/user-attachments/assets/bb12c5ad-72e9-402d-a76d-131b2d4916dd)

Após finalizar o preenchimento das informações clique na opção **Avançar: Proteção de dados**.

![AZ06-12](https://github.com/user-attachments/assets/bc855b54-48e7-4589-b331-f5ca71c259bc)

No grupo **Recuperação** desmarque todas as opções, pois como se trata de um teste não queremos que o blob seja mantido por 7 dias após a exclusão, e assim evitar cobrança:

![AZ06-13](https://github.com/user-attachments/assets/aebba213-7dc1-4eff-8d0d-786ba3b37a73)

Clique em **Avançar: Criptografia**:

![AZ06-14](https://github.com/user-attachments/assets/9690c108-7425-438c-903d-554d45a31ccf)

Na aba **Criptografia** mantenha as opções padrões e clique em **Avançar: Marcas**:

![AZ06-15](https://github.com/user-attachments/assets/036186e3-1b7d-4e0b-84fe-6f6a45733a8c)

Caso não deseje criar tags, clique em **Avançar: Examinar**:

![AZ06-16](https://github.com/user-attachments/assets/c125c637-4e58-4787-bec6-242eb9fe9dbf)

Nesta última aba clique em **Criar**:

![AZ06-17](https://github.com/user-attachments/assets/458c6256-a5bd-41bf-91a2-48b0b1707321)


## Recursos da Conta de Armazenamento na Azure

Abra a conta de armazenamento criada:

![AZ06-18](https://github.com/user-attachments/assets/11734755-c811-43cb-80fd-a87082b6a7e8)

No menu lateral clique em **Compartilhamentos de arquivos** e após clique em **+ Compartilhamento de arquivos**:

![AZ06-19](https://github.com/user-attachments/assets/e72a8aad-5ac6-4cee-9376-21d39d4de8f5)

Na próxima tela repare nas opções do campo **Camada**:

![AZ06-20](https://github.com/user-attachments/assets/4fb2044e-6940-4775-a5b7-62e95b816ea2)

Clique na opção **Avançar: Backup**:

![AZ06-21](https://github.com/user-attachments/assets/aeb91998-592b-4f05-8a03-e268b34dd677)

Altere as opções pré-definidas de backup caso necessário, e clique em **Avançar: Examinar**:

![AZ06-22](https://github.com/user-attachments/assets/0bca965b-c438-4470-9f4d-6e2df99f7c62)

Na aba **Revisar + criar** clique em **Criar**:

![AZ06-23](https://github.com/user-attachments/assets/ebbe229f-8556-4eba-99a6-80f695b89235)

Acesse o recurso criado:

![AZ06-24](https://github.com/user-attachments/assets/de9d3f28-f9dc-43dc-9da7-368dc886ead2)

Clique em **Conectar** para verificar as opções diponíveis:

![AZ06-25](https://github.com/user-attachments/assets/8582f1d9-ec24-4599-a29f-06c0f30eca64)

Clique em **Mostrar script** para visualizar o script completo para fazer o acesso a partir de uma máquina:

![AZ06-26](https://github.com/user-attachments/assets/9fc137eb-ac59-4713-93ab-a393eb20d21d)

![AZ06-27](https://github.com/user-attachments/assets/99e2ffe6-cbf9-43a4-92ca-73dfbd2201e9)

Repare que a conexão funciona também para *Linux* e *macOS*:

![AZ06-28](https://github.com/user-attachments/assets/4ded87be-4e61-419c-a239-3a1752bd7d88)

Voltando para a tela inicial da conta de armazenamento clique em **Filas** no menu lateral e em **+ Fila** para criar uma nova:

![AZ06-29](https://github.com/user-attachments/assets/0548dbe4-9dba-46fc-b73a-fd149f6427c4)

Informe o nome da fila e clique em **OK**:

![AZ06-30](https://github.com/user-attachments/assets/0634ee5b-4276-4b69-9fea-bc4e9fec7d2d)

Verifique que para a fila de armazenamento criada também foi criada uma URL:

![AZ06-31](https://github.com/user-attachments/assets/c2abfbb5-e0cf-42ec-bb3c-d4e1c8ef7034)

Abra a fila criada e clique em **+ Adicionar mensagem** caso queira adicionar uma mensagem à fila:

![AZ06-32](https://github.com/user-attachments/assets/2e7cbb8e-ccad-4bc4-a193-1bd93e400801)

De volta à conta de armazenamento, clique em **Tabelas**, **+ Tabela**, informe um nome para a tabela e clique em **OK**:

![AZ06-33](https://github.com/user-attachments/assets/c39158f9-65ce-4620-a692-0b2f56858d56)

Verifique que para a tabela também foi criada uma URL:

![AZ06-34](https://github.com/user-attachments/assets/4d68d652-9b5f-4d24-9eed-b20e275fe984)

Verifique as opções disponíveis para configuração da **Política de acesso** à tabela:

![AZ06-35](https://github.com/user-attachments/assets/eb7617e9-0f3c-474c-8aaf-a7620fa572dd)

A opção **IAM (Controle de acesso)** é para usuários em específico:

![AZ06-36](https://github.com/user-attachments/assets/c844e36a-2834-4d5e-bca6-f6730eda9193)

A parte de **Contêineres** e **Compartilhamento de arquivos** são os recursos mais utilizados nas contas de armazenamento:

![AZ06-37](https://github.com/user-attachments/assets/05c5f81c-dd21-4e07-822d-75a3888ed1aa)

![AZ06-38](https://github.com/user-attachments/assets/41a8ec19-832e-4182-9deb-08f144b7a897)


## Migrações para a Azure

Pesquise por **Migrações para Azure**:

![AZ06-39](https://github.com/user-attachments/assets/5541e459-43f2-493f-a37e-2a5ad80956ba)

Observe as opções diponíveis:

![AZ06-40](https://github.com/user-attachments/assets/5c5154ad-6a49-480b-91f9-d8f735c01098)

Na primeira opção clique em **Descobrir, avaliar e migrar**:

![AZ06-41](https://github.com/user-attachments/assets/836b475a-e0ed-47eb-8cfc-361863f53384)

Na próxima tela clique em **Criar projeto**:

![AZ06-42](https://github.com/user-attachments/assets/4f1f1ec2-af18-4346-ba4c-e9fd9a3b9e6f)

Preencha as informações necessárias e clique em **Criar**:

![AZ06-43](https://github.com/user-attachments/assets/4b0d59c5-7cf6-4e26-a848-ecd8f9e4dd77)

Aguarde a criação e após verifique as opções disponíveis:

![AZ06-44](https://github.com/user-attachments/assets/2dfb9bee-0363-401a-8d58-d461b9746f83)

![AZ06-45](https://github.com/user-attachments/assets/b339307f-9bfd-45ec-b1f4-9218a5184f4b)

No menu lateral clique em **Data Box** e veja a descrição das opções disponíveis:

![AZ06-46](https://github.com/user-attachments/assets/ebad785a-cbcf-48d3-bb0e-ccccad6f4ab9)

Preencha os campos e clique em **Aplicar**:

![AZ06-47](https://github.com/user-attachments/assets/88a578d7-37ea-4a81-aabe-31d60bb8f224)

Obeserve as opções de tamanhos disponíveis:

![AZ06-49](https://github.com/user-attachments/assets/5262934a-7b6b-4142-af6b-996ad9cd46ae)

Na opção Import/Export Job clique em **Selecionar** e observe as opções disponíveis na tela que se abre:

![AZ06-51](https://github.com/user-attachments/assets/129baab3-75e2-4bc5-8fbc-cd3e2ba41340)

![AZ06-50](https://github.com/user-attachments/assets/cc77544f-223b-4392-9ff8-1a13cb6d8e88)

Repare também no aviso de que o Azure Data Box não está disponível para a assinatura selecionada:

![AZ06-52](https://github.com/user-attachments/assets/d9df0206-07be-421b-a816-0123dda38d09)


## AzCopy

Para verificar informações sobre o serviço AzCopy acesse o seguinte link: https://learn.microsoft.com/en-us/azure/storage/common/storage-use-azcopy-v10?tabs=dnf

De acordo com a documentação do link indicado, o AzCopy é um utilitário de linha de comando que você pode usar para copiar blobs ou arquivos de ou para uma conta de armazenamento. E ele funciona também com outros Sistemas Operacionais além do Windows.

![AZ06-53](https://github.com/user-attachments/assets/103322fd-e47f-4362-b8e3-899091361b5d)

Baixe a versão compatível com seu sistema operacional:

![AZ06-54](https://github.com/user-attachments/assets/7ef1527d-3c8b-48c6-b0ea-c00f6c0e414d)

Após baixar, abra a pasta onde o arquivo foi salvo e descompacte:

![AZ06-55](https://github.com/user-attachments/assets/effc65d5-8ab8-40d9-9fa6-09b20e3811f1)

Abra a conta de armazenamento, vá para **Contêineres** e clique em **+ Contêiner** para criar um novo:

![AZ06-56](https://github.com/user-attachments/assets/8485a995-2477-4c22-85d8-827f84adc400)

Abra o Contêiner criado e clique em **Tokens de acesso compartilhado**:

![AZ06-57](https://github.com/user-attachments/assets/c4dd3dc3-e343-49e9-bfb5-3c9dd41cd8db)

No campo **Permissões** selecione todas as opções:

![AZ06-58](https://github.com/user-attachments/assets/70e25cc8-8500-4412-8f78-072b696f0c12)

![AZ06-59](https://github.com/user-attachments/assets/46d48a3b-52f8-496c-bfc1-c59c8369fa46)

E após clique em **Gerar token SAS e URL**:

![AZ06-60](https://github.com/user-attachments/assets/8642655f-61c5-442f-a719-e2480b05fca3)

Copie a informação *URL de SAS do blob*:

![AZ06-61](https://github.com/user-attachments/assets/fb375c0c-a9da-43ef-afd4-343c4778714f)

Retorne à documentação do Azure e copie o seguinte comando destacado abaixo:

![AZ06-62](https://github.com/user-attachments/assets/f340f2ac-7da9-4e2c-a3e9-8ad7e32bd9ba)

Neste comando substitua os locais indicados pelo local onde está o arquivo que deseja mover para o Azure e pela URL de SAS do blob gerada.

![AZ06-63](https://github.com/user-attachments/assets/7efd0afb-0d93-4a2f-ba21-d0267862855f)

No prompt de comando execute os seguintes comandos:

![AZ06-64](https://github.com/user-attachments/assets/56dc3797-7ae9-4aa4-9455-070e8101edab)

Ao final da execução confira se a quantidade de arquivos copiados condiz com a quantidade de arquivos da pasta que foi copiada:

![AZ06-65](https://github.com/user-attachments/assets/693ce7b8-478d-472a-b466-a0d435796702)

Voltando ao contêiner, verifique os arquivos copiados:

![AZ06-66](https://github.com/user-attachments/assets/b114d0d4-75ab-4b01-89f4-aad515f97b00)


## Gerenciador de Armazenamento do Microsoft Azure

Acesse o seguinte endereço para verificar mais informações sobre este produto: https://azure.microsoft.com/pt-br/products/storage/storage-explorer

Este serviço permite gerenciar seus recursos de armazenamento em nuvem do Azure a partir da área de trabalho.

![AZ06-67](https://github.com/user-attachments/assets/0d9f8681-1a5a-45dc-89b5-66500673e8c5)

Realize o download da versão compatível com sua máquina:

![AZ06-68](https://github.com/user-attachments/assets/97af67cc-8dc5-4d40-806d-b97c8b6f79ee)

Após a instalação abra o aplicativo:

![AZ06-69](https://github.com/user-attachments/assets/8b0910f4-89bc-425d-831a-a22717f0c744)

Na tela **Selecionar um Recurso** clique na opção **Assinatura**:

![AZ06-70](https://github.com/user-attachments/assets/01a86130-13fa-4f89-9d9d-90668375a1f1)

Na próxima tela selecione **Azure** e clique em **Avançar**:

![AZ06-71](https://github.com/user-attachments/assets/bce14223-f4ac-4f1b-810b-00f4cd22df15)

Realize a autenticação no portal do Azure:

![AZ06-72](https://github.com/user-attachments/assets/bf74d8f6-94b1-40c0-be06-f16a0f1749c1)

Verifique no aplicativo a conexão com sua conta do Azure:

![AZ06-73](https://github.com/user-attachments/assets/12141973-2baa-4463-a02c-af347ce0c4cb)

Repare que ele trouxe todos os recursos que estão presentes na conta do Azure, fazendo uma validação, e permitindo que as cópias de arquivos sejam feitas do desktop diretamente para o Azure:

![AZ06-74](https://github.com/user-attachments/assets/f28b0329-f4bb-4728-a6f9-e0ae3de7c909)

![AZ06-75](https://github.com/user-attachments/assets/101ee622-12d1-454e-bfb9-be6ee52ec35e)

A principal diferença entre o Gerenciador de Armazenamento e o AzCopy, é que ele apresenta uma interface mais visual aos usuários, mas por trás ele também utiliza o AzCopy. Já o AzCopy é a interação com o portal do Azure por meio de comandos, o que o torna mais prático.


## Links utilizados

- https://learn.microsoft.com/en-us/azure/storage/common/storage-use-azcopy-v10?tabs=dnf

- https://azure.microsoft.com/pt-br/products/storage/storage-explorer

- https://azure.microsoft.com/pt-br/get-started/azure-portal/
