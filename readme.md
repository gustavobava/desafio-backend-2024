# Desafio: Sistema de Pagamento Simplificado

Neste desafio, voc� ser� respons�vel por desenvolver um sistema de pagamento simplificado em PHP. O sistema permitir� que usu�rios comuns e lojistas realizem transfer�ncias de dinheiro entre si.

## Orienta��es

- Crie um reposit�rio no GitHub para a resolu��o do desafio.
- Deixe claro e exemplificado como executar o script/aplica��o.
- Pode fazer utiliza��o de um framework.

## Objetivo

Desenvolver um sistema de pagamento simplificado que permita a transfer�ncia de dinheiro entre usu�rios comuns e lojistas.

## Requisitos

Aqui est�o os requisitos principais para o funcionamento do sistema:

- Cadastro de usu�rios: Ambos os tipos de usu�rios (comuns e lojistas) devem fornecer nome completo, CPF/CNPJ, e-mail e senha. CPF/CNPJ e e-mails devem ser �nicos no sistema, permitindo apenas um cadastro por CPF ou endere�o de e-mail.
- Transfer�ncias de dinheiro: Usu�rios comuns podem enviar dinheiro para lojistas e entre si. Lojistas s� recebem transfer�ncias e n�o enviam dinheiro para ningu�m.
- Valida��o de saldo: Antes de efetuar uma transfer�ncia, o sistema deve validar se o usu�rio possui saldo suficiente em sua carteira.
- Consulta a servi�o externo autorizador: Antes de finalizar uma transfer�ncia, o sistema deve consultar um servi�o externo autorizador. Utilize este [mock](https://run.mocky.io/v3/ac35c88f-f627-42c5-9105-6e83a943a8df) para simular a autoriza��o.
- Transa��es revers�veis: Toda transfer�ncia deve ser tratada como uma transa��o, revertendo em caso de inconsist�ncia e devolvendo o dinheiro para a carteira do usu�rio remetente.
- Notifica��o de pagamento: Ap�s o recebimento de um pagamento, tanto o usu�rio quanto o lojista devem receber uma notifica��o por e-mail ou SMS. Utilize este [mock](https://run.mocky.io/v3/6d58afc4-07f7-4f9c-a378-a2b6f6faa0c4) para simular o envio de notifica��es.

## Avalia��o

- Boas pr�ticas: Ser�o avaliadas habilidades b�sicas de cria��o de projetos backend, como conhecimentos sobre REST, uso do Git, capacidade anal�tica e apresenta��o de c�digo limpo e organizado.
- Conhecimentos intermedi�rios: Ader�ncia a recomenda��es de implementa��o (PSRs), aplica��o de SOLID, identifica��o e aplica��o de Design Patterns, documenta��o e descri��o do projeto, implementa��o e conhecimentos sobre testes de unidade e integra��o, e boas no��es de bancos de dados relacionais.
- Diferenciais: Uso de Docker, cobertura de testes consistente, uso de Design Patterns, proposta de melhoria na arquitetura, consist�ncia nas escolhas e argumenta��o, dom�nio das solu��es apresentadas, modelagem de dados, manutenibilidade do c�digo, tratamento de erros, uso de container de inje��o de depend�ncias cuidados com seguran�a e arquitetura.

## Boas pr�ticas

- Tente seguir as PSRs se estiver utilizando PHP. Caso contr�rio, siga as boas pr�ticas da comunidade da linguagem ou framework escolhido.

Esse desafio dever� testar suas habilidades de desenvolvimento backend e sua capacidade de criar solu��es escal�veis, seguras e bem estruturadas. Boa sorte!
