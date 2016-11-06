# SistemaClinicaMedica

FACULDADE DE TECNOLOGIA DE MOGI DAS CRUZES
ANÁLISE E DESENVOLVIMENTO DE SISTEMAS
DISCIPLINA DE ENGENHARIA DE SOFTWARE II 

Lucas Julio

Marco Antonio

Paulo Henrique



# CLÍNICA MÉDICA

## Clínica Médica:

Realiza atendimento referente a uma ou diversas  especialidades, proporciona assistência   à prevenção, tratamento e recuperação de saúde, mediante atendimento médico, de acordo com sua especialidade.

## Funcionamento:

Deve manter registro de todos os seus pacientes, bem como de seus funcionários. Além disso, na clínica ocorre a marcação de consultas, exames e outros procedimentos.  Logo que estas sejam marcadas o médico deverá realizar a consulta no período devidamente agendado, podendo solicitar exames e receitar medicamentos para os pacientes que ali foram atendidos.

## Problema:

* Atendentes geralmente possuem um grande número de atribuições. Agendamento de consultas, acompanhar pacientes, gestão da agenda do médico além de dar total suporte ao profissional de saúde.

* Pacientes não conseguem agendar suas consultas de forma fácil, prática e rápida.

* Dificuldades de gerenciar as faltas e encaixes para que não existam horários vagos.

* O acesso aos documentos da clínica, cadastros, bem como prontuários de pacientes ainda são organizados em fichários e pastas suspensas.

* Dificuldades para acessar o cadastro, bem como prontuários médicos de pacientes que migram de outras clinicas.

* Administração não consegue identificar se a clínica está ou não, obtendo lucro ou prejuízo, ou mesmo dando conta de pagar os custos para sua operação.

* Pagamentos são efetuados apenas com dinheiro ou cheque.

## Proposta de Solução

* Um sistema que permita:

* Um prontuário eletrônico onde o médico possa acessar as informações de seus pacientes de onde estiver, de maneira totalmente segura.

* Otimizar tempo da equipe evitando ligações, reduzindo custos de telecomunicação, lembrando o paciente por e-mail ou SMS.

* Agenda organizada, com um módulo simples, que permita gerenciar de forma rápida e organizada todos os atendimentos da clínica.

* A agenda que permita gerenciar simultaneamente o atendimento de no mínimo 10 médicos de maneira simples, organizada e eficiente.

* Migrar o cadastro, bem como prontuários médicos de pacientes de outras clinicas para o sistema.

* Suporte Técnico para resolver as questões mais frequentes de uso da solução, presencialmente ou mesmo online.

## Trabalhadores de Negócio:

Atendente, Médico, Administrador e Operadora de Cartões

## Atores de Negócio

Paciente, Atendente, Médico, Administrador e Operadora de Cartões

## Atividades de Negócio

Agendamento de consultas online, atendimento pessoal personalizado para as consultas médicas (oftalmologista, cardiologista, otorrinolaringologista, dermatologista, ginecologista, urologista, endocrinologista, gastroenterologista, oncologista, neurologista, ortopedista, angiologista, nutricionista e psiquiatria).


## Regras de Negócio

RN01 - Senhas devem ter no mínimo oito caracteres, entre números e letras.

RN02 - Todos os campos do cadastro de pacientes são obrigatórios.

RN03 - As informações sobre os pacientes devem seguir as normas instituídas pelo CREMESP.

RN04 - Todos os funcionários deverão preencher o termo de confidencialidade de informações.

RN05 -  Administrador e médicos não devem ter restrições ao sistema.

RN06 - O cadastro poderá ser atualizado quando houver alteração de dados de funcionários ou de pacientes. Todos os campos poderão ser alterados, exceto RG e CPF.

RN07 - Os dados informados no campo usuário e senha deverão ser validados junto ao cadastro de usuário no banco de dados. 

RN08 - O sistema deverá suportar processamento multiusuário, ou seja, vários usuários poderão utilizar o sistema simultaneamente

RN09 - Pacientes menores de dezoito anos, deverão ser cadastrados somente por seus responsáveis.

RN10- Fornecedores e parceiros devem possuir cadastro no sistema.

RN11 - Pagamentos podem ser efetuados com dinheiro, cheque ou cartões de débito ou crédito.

RN12 – Qualquer cancelamento de consulta por parte do cliente deverá ter um aviso de até   48 horas de antecedência. Caso contrário, uma multa será aplicada.  O sistema envia o cancelamento ao Médico, e já realoca os horários livres para possíveis novas consultas.

RN13 - O Médico pode cancelar uma consulta marcada com até dois dias úteis antes da data da consulta. O sistema envia uma mensagem de cancelamento ao Paciente que terá prioridade na marcação de uma próxima consulta.

RN14 – Convênio com UNIMED, SAMED, BRADESCO SAÚDE, AMIL, SULAMÉRICA SAÚDE, GOLDEN CROSS e CRUZ AZUL, os quais deverão estar cadastrados no sistema.

RN15 - Planos de Saúde devem estar registrados na ANS (Agência Nacional de Saúde Suplementar), que regula o setor.

RN16 - O paciente não poderá marcar duas consultas no mesmo horário.

RN17 – Administrador, médico e atendente poderão cadastrar novos pacientes

RN18 - O paciente não poderá realizar o pedido de um exame sem guia

RN19 - O atendente só poderá cadastrar um paciente que tenha o CPF e RG em mãos

RN20 - O paciente deve estar cadastrado para realizar um pedido para consulta médica

RN21 - Em caso de emergência, o paciente não precisará marcar uma consulta

RN22 - Para cada diagnóstico o histórico médico do paciente será atualizado

RN23 - O paciente pode marcar consultas com um ou mais médicos, obedecendo RN16.

RN24 - Um médico pode realizar consultas com um ou mais pacientes

RN25 - Cada consulta é realizada com apenas um médico.

RN26 - Somente o administrador poderá cadastrar novos médicos e atendentes.

RN27 - O Administrador não poderá desmarcar consultas de pacientes


## Requisitos Funcionais

RF01 - Deverá permitir emissão de relatório de agendamentos de consultas médicas.

RF02 – Deverá solicitar ao usuário para efetuar o login.

RF03 - Deverá permitir alteração da senha de acesso.

RF04 - Deverá permitir o cadastro de pacientes.

RF05 - Deverá permitir o registro de agendamento de consulta.

RF06 - Deverá permitir cadastro de medicamentos.

RF07 - Deverá permitir cadastro de exames complementares.

RF08 - Deverá permitir a geração de receitas.

RF09 - Deverá permitir a geração laudos.

RF10 - Deverá permitir a consulta a prontuários dos pacientes.

RF11 - Deverá permitir atualização do prontuário

RF12 - Deverá permitir o cadastro de clínicas médicas.

RF13 - Deverá permitir o cadastro de usuário do sistema.

RF14 - Deverá permitir o cadastro de profissionais médicos.

RF15 - Deverá permitir o cadastro de planos de saúde, convênios.

RF16- Deverá permitir o cadastro de cargos dos funcionários da clínica.

RF17- Deverá permitir o acesso do Sistema PayPal para pagamentos através de cartões.



## Requisitos Não Funcionais

RNF01 - O sistema deverá ser desenvolvido para plataforma Web, acessível por meio de qualquer navegador.

RNF02 - O sistema deverá possuir controle de acesso por usuário e senha.

RNF03 - As senhas devem ser armazenadas criptografadas no banco de dados.

RNF04 - O sistema deverá realizar todas as funcionalidades de inserção, busca, entre outros num tempo considerado aceitável, para evitar esperas pelo lado do utilizador

RNF05 - O sistema deverá realizar log de acesso.

RNF06 - O sistema deve estar disponível de segunda às sexta-feira das 08:00 às 19:00 e no sábado das 08:00 às 12:00. 

RNF07 – O sistema deverá disponibilizar acesso às informações seguindo normas instituídas pelo CREMESP.

RNF08 - O banco de dados utilizado deve ser MySQL.

RNF09 -  O sistema deve ter capacidade para recuperar os dados perdidos da última operação que realizou em caso de falha. 

RNF10 - O sistema deve fornecer facilidades para a realização de backups dos arquivos do sistema.

RNF11 -  O sistema deve possuir senhas de acesso e identificação para diferentes tipos de usuários.


##Diagrama de Atividade

###[Agenda da consultas](/Diagrama-de-Atividade/Agendas de consultas.jpg)

###[Cadastro de exames](/Diagrama-de-Atividade/Cadastro de exames.jpg)

###[Cadastro de medicamentos](/Diagrama-de-Atividade/Cadastro de medicamentos.jpg)

###[Cadastro de pacientes](/Diagrama-de-Atividade/Cadastro de pacientes.jpg)

##Diagrama de Caso de Uso

###[Caso de uso](/Diagrama-Caso-de-Uso/UseCase Clinica.jpg)

###[Documentação caso de uso](/Diagrama-Caso-de-Uso/Documentação casos de uso.docx)

##Protótipo Visual

###[Página Inicial - Administrador](/Prototipo/Tela administrador.jpeg)

###[Página Inicial - Atendente](/Prototipo/Tela atendente.jpeg)

###[Página Inicial - Médico](/Prototipo/Tela medico.jpeg)

###[Página Inicial - Paciente](/Prototipo/Tela paciente.jpeg)


##Diagrama de Classes

###[Diagrama Classes - Clinica](/Diagrama-de-classe/diagrama.jpg)
