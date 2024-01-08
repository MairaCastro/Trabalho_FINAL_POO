## Sobre o Projeto
Sistema de gerenciamento de estudantes para o projeto final da disciplina de Programação Orientada a Objetos (POO) do curso de Desenvolvimento Full Stack do Serratec. 


## Tecnologias utilizadas
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql)
![PGAdmin](https://img.shields.io/badge/PGAdmin-336791?style=for-the-badge&logo=pgadmin&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=java)
![Eclipse](https://img.shields.io/badge/Eclipse-2C2255?style=for-the-badge&logo=eclipse)

## Requisitos
Crie um sistema de gerenciamento de estudantes.

Passo 1: Definir as Classes

- Crie uma classe principal chamada “SistemaGerenciamentoEstudantes” que
será responsável por iniciar o programa e interagir com o usuário pelo
console.

- Crie uma classe “Estudante” para representar os dados de cada estudante,
com atributos como nome, ID e curso, e métodos construtores, getters e
setters.


Passo 2: Implementar a Classe de Banco de Dados

- Crie uma classe “BancoDeDados” para lidar com a conexão e operações no
banco de dados, configurando a conexão no construtor da classe.

- Implemente métodos na classe “BancoDeDados” para adicionar, editar,
remover e listar estudantes no banco de dados.


Passo 3: Implementar o Menu do Usuário

- Crie uma classe “Menu” que interaja com o usuário pelo console, usando a
classe Scanner para ler as entradas do usuário e System.out.println para
imprimir as saídas.

- Implemente um menu de opções que permita ao usuário escolher entre
“Adicionar Estudante”, “Editar Estudante”, “Remover Estudante”, “Listar
Estudantes” e “Sair”.

- Para cada opção do menu, implemente métodos que usem as classes
“Estudante” e “BancoDeDados” para realizar as operações correspondentes.


Passo 4: Tratamento de Exceções

- Implemente tratamento de exceções nas operações de banco de dados,
capturando exceções como falhas na conexão ou consultas mal-sucedidas, e
fornecendo feedback adequado ao usuário em caso de erros.


Passo 5: Organização em Pacotes

- Organize seu código em pacotes, colocando a classe “Estudante” em um
pacote chamado “model”, a classe “BancoDeDados” em um pacote chamado
“data”, e a classe “Menu” em um pacote chamado “view”.

## Desenvolvedores
<ul>
    <li><a href="https://github.com/MairaCastro">Maíra Castro</a></li>
    <li><a href="https://github.com/Nimai360">Nimai Marchiori</a></li>
    <li>Adriane</li>
    <li><a href="https://github.com/DkDiguim">Rodrigo Rocha</a></li>
    <li><a href="https://github.com/WFrauches89">Wanderson Frauches</a></li>
    <li>Ramon Matos</li>
  </ul>
