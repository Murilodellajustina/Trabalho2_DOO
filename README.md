# Trabalho2_DOO

Para conseguir executar o programa, você precisará de 3 software:
  -Apache Netbeans
  -MySQL Workbench
  -XAMPP Control Panel
  ![image](https://github.com/user-attachments/assets/93710229-5bc3-4c36-a63d-8979e230beff)

  Apos instalar os softwares, e o arquivo do programa, você terá que abrir o banco de dados do programa no MySQL, iniciar uma conexão com o Netbeans via o XAMPP, e inicializar a conexão no Netbeans por meio de um arquivo .jar, que também foi disponibilizado aqui.
  ![image](https://github.com/user-attachments/assets/c8f54068-a663-4297-8a5a-dc5564d0a9d0)

  Depois de estabelecer conexão, ai sim você poderá inicializar o projeto, utilizando a seta verde contida na parte superior da tela:
  
  ![image](https://github.com/user-attachments/assets/718f1a40-c2e9-43e0-b734-ed5d5a84dd13)

  Após isso, o programa inicializará, e você irá se deparar com a tela principal:

  ![Captura de tela 2025-06-24 202955](https://github.com/user-attachments/assets/1a10eeb4-5f79-4f32-bbb4-f6877f7195f7)

  Nesta tela, você tera acesso a 2 campos, cadastro e paciente.
  
  ![image](https://github.com/user-attachments/assets/b7397283-9af2-4da5-ba0c-0cc710d725a1)

  No campo Cadastro, você tera acesso a 2 telas, "Paciente" e "Editar Registro".

  ![Captura de tela 2025-06-24 203110](https://github.com/user-attachments/assets/9f6ec8b3-bfdf-4508-9ad7-2e5e3498204e)

  Na tela paciente, o usuario terá a disponibilidade de cadastrar um novo paciente ao banco de dados, com a opção de adicionar o nome, o CNS, a data de nascimento, e a data da DUM (Data da ultima menstruação). Ele tem acesso a 2 botões, sendo o cadastrar, que como o nome já diz, irá cadastrar, e o botão cancelar, que é responsável pela limpeza dos campos. Neste campo também existe uma tabela que é responsável por apresentar todos os pacientes já existentes no banco, assim mostrando se o paciente que ele cadastrou foi adicionado realmente ou não.

  Vale destacar, que todas as datas devem ser cadastradas no modelo americano (yyyy-MM-dd) por conta de complicações no modelo do banco de dados.
  
  ![Captura de tela 2025-06-24 203815](https://github.com/user-attachments/assets/5efb2d31-02af-4b39-848a-c32c74605881)

  Na tela editar registros, de começo o usuário tem acesso apenas ao campo de digitar o nome do paciente, e do botão buscar, os botões alterar e excluir só se tornam acessíveis caso o paciente exista, do contrario eles permanecem inativos. 

  ![Captura de tela 2025-06-24 204232](https://github.com/user-attachments/assets/1ce4f76e-fcfb-4217-88d0-541ea9ebb9e2)

  Com o paciente encontrado, os botões se tornam ativos. 
  
  ![Captura de tela 2025-06-24 204411](https://github.com/user-attachments/assets/aa575a83-d998-4bec-b485-ac463a4a449a)

  Caso o usuário deseje alterar o paciente, novos campos serão mostrados, com a opção de mudar o CNS, data de nascimento e data da DUM, (o campo nome não permite alteração, pois o banco procura o paciente através do nome). 

  ![Captura de tela 2025-06-24 204515](https://github.com/user-attachments/assets/f4633a1d-e48c-4c4f-b961-d9dcb01ab987)

  Caso o usuário aperte o botão excluir ira aparecer um pop-up, para a confirmação de exclusão, caso o usuário selecione “Yes”, o cadastro sera excluído.
  
  ![Captura de tela 2025-06-24 204833](https://github.com/user-attachments/assets/b8d137cd-3cc3-442d-8ca5-6f89cf34c64a)

  Caso clique em “Paciente”, o usuário terá duas opções, “Semanas”:
  
  ![Captura de tela 2025-06-24 203704](https://github.com/user-attachments/assets/030420b9-c097-4824-ba8a-39ff8a644956)

  Na tela semanas  o usuário tem a opção do campo de busca, onde ele deve colocar o nome da paciente que deseja buscar, e o botão buscar. Ao apertar o botão, caso a paciente exista, o sistema mostrara automaticamente a quantidade de semanas que a paciente se encontra na data atual, com base na data da DUM, que existe em seu cadastro. 

  ![Captura de tela 2025-06-24 205254](https://github.com/user-attachments/assets/a5c16a03-ea5f-453a-adaf-57fc66f33fbf)

  Na tela Referencia, voce tem a disponibilidade de calcular as semanas de uma paciente que não esteja cadastrada, assim apenas informando a data de referencia, a quantidade de semanas de gestação que a paciente estava nesta data, e a quantidade de dias de gestação (Caso a data de referencia seja a DUM, basta colocar 0 e 0 respectivamente nos campos).
  
  ![Captura de tela 2025-06-24 205825](https://github.com/user-attachments/assets/f31c06db-bd6d-4639-9c8c-613cad89503c)

