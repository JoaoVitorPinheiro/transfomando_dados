# transfomando_dados
desafio do modulo de Power Bi sobre transformar dados e criar um relatório.
para realizar esse desafio foi criado um repositorio no azure para integrar os dados como o Power Bi onde foi usado o power shell para criar as tabelas e colocar os dados, logo em seguida foi feito a integração com o MYSQL para carregar esses dados no POWERBI para assim começar as tranfomaçoes dos dados. 

Nesse desafio foi usado a função mesclar pois ela pega uma determinada informação e junta com a outra, ou seja, se você está querendo comparar informações entre colunas de outra tabela ela irá juntar e comparar essas informações, contudo se você usar o combinar informações ela irá simplesmente colocar os dados da outra tabela como se fosse uma continuação da mesma, e nesse desafio isso ia resultar em vários dados nulos.

Para unir o departament e o dept_locations foi usado o mesclar pois ele possibilita uma uniao com as informações comparando os dados.

<img width="527" alt="cap1" src="https://github.com/JoaoVitorPinheiro/transfomando_dados/assets/143013466/7ec8cc74-18fd-43d3-a9b0-63be5151003f">

Se fosse usar a função combinar ia gerar uma tabela com vários dados nulos pois nessa função ele pega os valores das duas tabelas e simplesmente coloca junto da outra tabela sem fazer uma comparação dos dados.

<img width="636" alt="cap2" src="https://github.com/JoaoVitorPinheiro/transfomando_dados/assets/143013466/819cbc45-9a76-45d1-a05b-387b1cd254c4">

Relatório criado para analisar quais cidades tem a maior quantidade de salário por colaborador onde ele mostra o quanto o colaborador recebe e qual departamento ele corresponde.  

<img width="610" alt="cap3" src="https://github.com/JoaoVitorPinheiro/transfomando_dados/assets/143013466/aa4861b0-2165-466b-9634-f3170f99b7b9">
