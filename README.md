# Bem vindo à DEVinHouse <img width="180px" alt="Philips" src="ExerciciosM03S08/images/logo-phil.png"/>
## Módulo 03 - Semana 08

Repositório criado para a elaboração dos 6 exercícios referentes a PL/SQL dessa semana. <br>

Para visualizar os exercícios, <a href="https://github.com/GeorgeEnriqueBravo/DEVinHouse-Modulo03-Semana07/archive/refs/heads/main.zip" target="_blank">
    clique aqui
</a>
para baixa-los. <br>

Após o download, extraia os arquivos zipados e abra o arquivo `exercicios_Modulo03_Semana08.sql`,  localizado na pasta ExerciciosM03S08 utilizando o `Oracle SQL Develover`. Caso você não possua ele, você pode baixar ele grátis diretamente do site oficial <a href="https://www.oracle.com/database/sqldeveloper/technologies/download/" target="_blank">
    clicando aqui
</a>.

---

# Lista de exercícios <img width="75px" alt="Philips" src="ExerciciosM03S08/images/lista.png"/>
### [M3S08] Ex 1 - Criar uma Função para calcular desconto

Criar uma função que calcule o desconto do produto, passar os parâmetros código do produto e aplicarDesconto boolean.

Regra:
- Fazer um select bucando o valor do produto
- Se a parametro aplicarDseconto for igual verdadeiro aplicar desconto de 10%

### [M3S08] Ex 2 - Criar uma view chamada ApenasLeituraProdutoPreco

Criar uma View que retorne os dados ID, utilizando a configuração de apenas leitura, utilizar o comando WITH READ ONLY.

### [M3S08] Ex 3 - Criar uma view chamada BuscarProduto

Nesta view deve utilizar o comando WITH CHECK OPTION, com o seguinte regra:

Produto entre 100 e 200 não poderá ser Atualizado ao efetuar o update na view BuscarProduto.

### [M3S08] Ex 4 - Crie uma tabela de Log

Criar uma tabela de log com as colunas:
- ID NUMBER
- Campo VARCHAR2(100)
- ValorAntigo VARHCAR2(100)
- NomeTabela VARCHAR2(100)

### [M3S08] Ex 5 - Criar um trigger after na tabela Produto

A trigger deve efetuar o INSERT na tabela de LOG dos campos alterados.

### [M3S08] Ex 6 - Criar um trigger before na tabela ProdutoPreco

Essa trigger deve logar apenas os dados deletados da tabela ProdutoPreco.

---

# O que é DEVinHouse?
DEVinhouse é uma jornada de aceleração da carreira com: grade curricular direcionada, professores do mercado, prática constante, interação frequente com as houses parceiras de cada turma, simulação do dia-a-dia DEV e vagas exclusivas que são abertas pelas Houses durante a jornada.

No DEVinHouse você vira um desenvolvedor Fullstack em 9 meses, ao longo de 900 horas de conteúdo, divididas em três módulos de 3 meses cada, com intervalo de uma semana entre cada um. Aproximadamente 25 horas de dedicação por semana entre aulas, atividades e vivências.

__1º módulo:__ Front-End – JavaScript e Angular <br/>
__2º módulo:__ Back-End – Java, Spring e SQL <br/>
__3º módulo:__ Full-Stack – Scrum, DevOps, Clean Code e Design Patterns <br/>
__Ferramentas__ – GitHub, Trello e Slack

---

# Tecnologias Utilizadas <img width="35px" alt="🌐" src="ExerciciosM03S08/images/tag.gif"/>
Nos exercícios dessa semana foram utilizadas as seguintes tecnologias:
<div style="display: inline_block">
    <img align="center" alt="Oracle" src="https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=black"/>
    <img align="center" alt="Oracle" src="https://img.shields.io/badge/PLSQL-F80000?style=for-the-badge&logo=oracle&logoColor=black"/>
    <img align="center" alt="Trello" src="https://img.shields.io/badge/Trello-0052CC?style=for-the-badge&logo=trello&logoColor=white"/>
    <img align="center" alt="GitHub" src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"/>
</div>



