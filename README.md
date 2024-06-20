Projeto de Gerenciamento de Funcionários
Descrição
Este projeto é uma aplicação simples em Java para gerenciar informações de funcionários. Ele permite adicionar, pesquisar e listar funcionários, fornecendo um menu interativo para o usuário.

Estrutura do Projeto
Project: Contém a classe principal Main que inicializa e executa o programa.
Project.utility: Contém a classe Utility com métodos utilitários para o menu e operações com funcionários.
entity: Contém as classes Pessoa e Funcionario que representam os dados dos funcionários.

Funcionalidades
Adicionar Funcionário: Permite adicionar um novo funcionário ao sistema.
Pesquisar Funcionário: Permite buscar um funcionário pelo seu ID.
Sair: Encerra o programa.

Requisitos
Java 8 ou superior
IDE para Java (Eclipse, IntelliJ, NetBeans, etc.) ou ambiente de linha de comando configurado para Java

Estrutura de Classes
Project.Main
A classe principal que contém o método main. Ela inicializa um scanner para entrada do usuário e uma lista de funcionários. O loop principal do programa exibe um menu com três opções e executa a ação selecionada.

Project.utility.Utility
Contém métodos utilitários:

menu(): Exibe o menu e retorna a escolha do usuário.
cadastrarFuncionario(): Solicita as informações do funcionário ao usuário e retorna um objeto Funcionario.
acharFuncionario(List<Funcionario> func, Integer id): Busca e exibe informações de um funcionário pelo ID.

entity.Pessoa
Classe base que representa uma pessoa com os seguintes atributos:

id: ID do funcionário
nome: Nome do funcionário
idade: Idade do funcionário
email: Email do funcionário
telefone: Telefone do funcionário
alergia: Alergias do funcionário
condicaoMedica: Condições médicas do funcionário

entity.Funcionario
Classe que herda de Pessoa e pode conter métodos específicos para Funcionario.

Este projeto está licenciado sob a MIT License.















