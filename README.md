## Desafio de Projeto: **Processando e Transformando Dados com Power BI** 👩‍💻

Projeto desenvolvido durante o bootcamp *Coding The Future Squadio - Python Data Analytics*, oferecido pela [Digital Innovation One](https://www.dio.me/) no período de março a maio de 2024.

### Descrição do Projeto 📝

Este repositório contém o resultado do desafio proposto pela DIO para aprimorar habilidades de coleta, obtenção e transformação de dados com Power BI e MySQL na Azure.

### Requisitos do Desafio ✅

- Criar uma instância do MySQL na Azure;
- Criar um banco de dados a partir de uma base disponibilizada no GitHub;
- Integrar o Power BI com a instância do MySQL;
- Verificar problemas na base a fim de realizar a transformação dos dados.

### Diretrizes para a transformação dos dados 📌

- Verificar cabeçalhos e tipos de dados;
- Modificar valores monetários para o tipo double preciso;
- Separar colunas complexas;
- Verificar a existência de valores nulos;
- Mesclar as colunas de *Nome* e *Sobrenome* para obter o nome completo dos colaboradores;
- Realizar a junção dos colaboradores e respectivos nomes dos gerentes;
- Mesclar as consultas *employee* e *departament*;
- Mesclar os nomes de departamentos e localização;
- Eliminar as colunas desnecessárias;
- Agrupar os dados a fim de saber quantos colaboradores existem por gerente;
- Verificar se há colaborador sem gerente;
- Verificar se há departamento sem gerente;
- Verificar o número de horas dos projetos.

#### OBS 🔎

No Power Query temos as opções *Atribuir* e *Mesclar* que podem ser usadas para combinar dados de duas tabelas ou mais. Entretanto, é importante destacar que os recursos funcionam de maneiras diferentes e é importante saber a diferença entre eles para escolher a melhor opção em cada situação.

O **Mesclar** combina as tabelas com base em colunas comuns e diferentes tipos de junções podem ser escolhidas, semelhante ao uso do *join* em SQL.

Já o **Atribuir** combina as tabelas verticalmente, isto é, acrescenta as linhas de uma tabela ao final da outra, promovendo um empilhamento dos dados. Para isso, é necessário que as tabelas tenham a mesma estrutura.

Nas transformações realizadas no projeto, sempre que foi necessário fazer a combinação de tabelas utilizou-se a opção *Mesclar*, visto que o objetivo era agrupar os dados de tabelas diferentes com base em uma coluna comum entre elas. Esta opção foi usada para combinar **employee** e **departament**, **dept_locations** e **departament**, bem como para juntar colaboradores e gerentes.
