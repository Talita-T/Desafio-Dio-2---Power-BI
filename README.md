# DESAFIO DE PROJETO - MÓDULO 3
Após a criação da instância no Azure, criação do banco de dados e integração ao Power BI, foi realizada a transformação dos dados:

- Alterado o nome dos cabeçalhos e colocado o valor salarial em decimal fixo;
- Acrescentado valores aos campos nulos, como por exemplo, a área que aparecia Colaborador sem Gerente;
- Dividida a coluna de endereço (rua, número, cidade, estado);
- Removidas colunas desnecessárias;
- Mescladas as tabelas employee e dependent, e excluindo as linhas com valores nulos (colaboradores que não possuiam dependentes);
- Mescladas as colunas de Departament + Departament Location + Project, para que fosse colocados os exatos locais dos projetos, pois possuiam projetos diferentes para o mesmo local, como também possuia o mesmo departamento em vários locais;
- Mesclada a coluna acima citada com Employee e Woks_on, para saber a divisão de colaboradores e gerentes pelos projetos;
- Unidas as colunas de Departament Location e Departament Name, unidas, também, as colunas de nome e sobrenome dos colaboradores, utilizando um espaço como separador;
- Alterado os ID Manager pelo nome dos mesmos, para melhor identificação e organizada as linhas de forma crescente pelo nome do gerente;
- Foi escolhido o método Mescla, pois ele une tabelas acrescentando novas colunas, apartir de uma coluna em comum, ficando mais fácil a separação, análise e exclusão de dados. A opção atribuir acrescentaria linhas às colunas existentes que fossem iguais e colunas com valores nulos, se a mesma não existisse nas duas tabelas, o que poderia ser incomodo e de difícil análise dos dados.
</p>
<img src="https://github.com/Talita-T/Desafio-Dio-2---Power-BI/blob/main/Desafio_de_Projeto_2/Tabela_1.png">
</p>
<img src="https://github.com/Talita-T/Desafio-Dio-2---Power-BI/blob/main/Desafio_de_Projeto_2/Tabela_2.png">
</p>

## ANÁLISE

Pro fim foi feita a análise dos dados em gráficos, como observado a baixo:
</p>

<img src="https://github.com/Talita-T/Desafio-Dio-2---Power-BI/blob/main/Desafio_de_Projeto_2/Relatório.png">
