Vamos criar um DataFactory:

![criarDF](screens/createDataFactory.jpg)

Vamos criar um StorageAccount (para podermos copiar para lá dados):

![criarStorage](screens/CreateStorage.jpg)


Criar um dataset para obtermos informação de algures:

![criarDS](screens/createDataset_Rest.jpg)

Apontar para um link com resultados, como por exemplo:
[https://jsonplaceholder.typicode.com/posts](https://jsonplaceholder.typicode.com/posts)

![apontarRest](screens/createDataset.jpg)


Adicionar um pedido get a este URL:

![get](screens/addGet.jpg)


Agora adicionamos um dataset para conectar à storage account:

![dsblob](screens/createDSBlob.jpg)

E adicionarmos o linked service:

![adddflinked](screens/adddfstorageLinkedservice.jpg)

