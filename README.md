# projeto-azure-storage

O serviço de Storage do Azure é onde encontramos as opções de armazenamento na nuvem da Microsoft.
Temos quatro opções dentro das contas de armazenamento do azure:
* File
* Queue
* Table
* Blob

Neste Laboratório será feito:
- [ ] Criação de conta de armazenamento no Azure
- [ ] Criação dos quatro tipos de conta de armazenamento
- [ ] Vizualização e manipulação através do Storage Explorer

## Criando uma conta de armazenamento do Azure.
Crie a conta de armazenamento do Azure com a Redundância LRS e o tier como HOT.
O acesso deixarei como público.
![2024-10-20 (10)](https://github.com/user-attachments/assets/96da7cc3-99a9-4bb0-aad4-dbd1d01e097f) [^1].
[^1]: Tela do Storage criada.

## Criação dos quatro tipos de conta de armazenamento
#### Criação do Blob Storage
Na tela da conta de armazenamento, clique em containers
![2024-10-20 (11)](https://github.com/user-attachments/assets/284c75e1-0a49-47e8-8dc9-328eef3c1113)

![2024-10-21](https://github.com/user-attachments/assets/edd2f616-3cc2-4c45-b82b-099f716663b8)

![2024-10-21 (1)](https://github.com/user-attachments/assets/d30c8a1f-3833-48b9-bcbd-25f107b83a39)

Acesse o Blob criado e adicione imagens ou arquivos nele.

#### Criação File Storage
No menu de Data Storage, selecione File Shares. Em seguida entre na opção File Share.
![2024-10-21 (2)](https://github.com/user-attachments/assets/7e2c0bd0-307a-4019-bd22-3bae1be27bf7)
Depois de criado teremos a seguinte tela:
![2024-10-21 (3)](https://github.com/user-attachments/assets/5f5a2629-aab0-4f06-be8a-a7475611b8d6)

#### Criação Queues
Esse é o serviço de armazenamento de mensagens. Com ele se pode criar e gerenciar mensagens.
No menu de Data Storage, selecione a opção Queues. Depois selecione a opção Queue.
![2024-10-21 (4)](https://github.com/user-attachments/assets/c8e64fcf-e16e-45c2-a60c-b6edc2e47602)
Se quiser, pode adicionar mensagens ou só crie o Queue.

#### Criação Table
Esse serviço é de armazenamento de dados não relacionais(NoSQL)

No menu de Data Storage, vá em Tables e depois aperte em Table para  criar.
![2024-10-22](https://github.com/user-attachments/assets/aa2dc2cb-7201-4a56-b296-f4d32a8671c5)

#### Vizualização e manipulação através do Storage Explorer.
O Storage Explorer é uma ferramenta que os usuários podem se conectar em contas de armazenamento e lá eles acessam os Blobs, queues, File Storages e as Tables.
O Storage Explorer é uma ótima ferramenta de gerenciamento e visualização de dados em uma interface gráfica para os usuários.
Para usar essa ferramenta, faça o download.
[página para download do Storage Explorer](https://azure.microsoft.com/pt-br/products/storage/storage-explorer/?msockid=0c2b86104ea56df802b9973c4f336c62)
O Storage Explorer pode se conectar a uma conta de armazenamento através da chave da conta de armazenamento mas aqui eu conectei através do SAS(Assinatura de acesso compartilhado), evitando assim compaartilhar a chave da conta e trazedo mais segurança pois posso designar um tempo em que uuma pessoa possa acessar essa conta de armazenamento r o que a pessoa pode modificar ou não na conta.
![2024-10-24](https://github.com/user-attachments/assets/833b8f7c-4068-4471-a5b7-989d05216c9e)
![2024-10-24 (1)](https://github.com/user-attachments/assets/38739c14-99c1-473d-916b-09e14749a084)
