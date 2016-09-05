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

Funcionários da Clínica

## Atores de Negócio

Paciente, Atendente, Médico, Administrador e Sistema de Cartões.

## Atividades de Negócio

Agendamento de consultas online, atendimento pessoal personalizado para as consultas médicas (oftalmologista, cardiologista, otorrinolaringologista, dermatologista, ginecologista, urologista, endocrinologista, gastroenterologista, oncologista, neurologista, ortopedista, angiologista, nutricionista e psiquiatria).


## Regras de Negócio

RN01 - Todos os campos do cadastro de pacientes são obrigatórios.

RN02 - As informações sobre os pacientes devem seguir as normas instituídas pelo CREMESP.

RN03 - Todos os funcionários deverão preencher o termo de confidencialidade de informações.

RN04 - O cadastro poderá ser atualizado quando houver alteração de dados de funcionários ou de pacientes. Todos os campos poderão ser alterados, exceto RG e CPF.

RN05 - Pacientes menores de dezoito anos, deverão ser cadastrados somente por seus responsáveis.

RN06 – Pagamentos devem ser efetuados com dinheiro ou cheque.

RN07 – Qualquer cancelamento de consulta por parte do cliente deverá ter um aviso de até   48 horas de antecedência. Caso contrário, uma multa será aplicada.  

RN08 - O Médico pode cancelar uma consulta marcada com até dois dias úteis antes da data da consulta. 

RN09 – A clínica deve manter convênios com UNIMED, SAMED, BRADESCO SAÚDE, AMIL, SULAMÉRICA SAÚDE, GOLDEN CROSS e CRUZ AZUL.

RN010 - Planos de Saúde devem estar registrados na ANS (Agência Nacional de Saúde Suplementar), que regula o setor.

RN011 - O paciente não poderá marcar duas consultas no mesmo horário.

RN012 - O paciente não poderá realizar o pedido de um exame sem guia médico

RN013 - O atendente só poderá cadastrar um paciente que tenha o CPF e RG em mãos

RN014 - O paciente deve estar cadastrado para realizar um pedido para consulta médica

RN015- Em caso de emergência, o paciente não precisará marcar uma consulta

RN016 - Para cada diagnóstico o histórico médico do paciente será atualizado

RN017 - O paciente pode marcar consultas com um ou mais médicos, obedecendo RN017.

RN018 - Um médico pode realizar consultas com um ou mais pacientes

RN019 - Cada consulta é realizada com apenas um médico.

RN020 - Somente o administrador poderá cadastrar novos médicos e atendentes.

RN021 - O Administrador não poderá desmarcar consultas de pacientes


## Requisitos
RF01 - Deverá permitir emissão de relatório de agendamentos de consultas médicas.

RF02 - Deverá permitir alteração da senha de acesso.

RF03 - Deverá permitir o cadastro de pacientes.

RF04 - Deverá permitir o registro de agendamento de consulta.

RF05 - Deverá permitir cadastro de medicamentos.

RF06 - Deverá permitir cadastro de exames complementares.

RF07 - Deverá permitir a geração de receitas.

RF08 - Deverá permitir a geração laudos.

RF09 - Deverá permitir a consulta a prontuários dos pacientes.

RF010 - Deverá permitir atualização do prontuário.

RF011 - Deverá permitir o cadastro de clínicas médicas.

RF012 - Deverá permitir o cadastro de usuário do sistema.

RF013 - Deverá permitir o cadastro de profissionais médicos.

RF014 - Deverá permitir o cadastro de planos de saúde, convênios e parceiros. Consulte RN09.

RF015 - Deverá permitir o cadastro de cargos dos funcionários da clínica.

RF016 - Deverá permitir o acesso do Sistema PayPal para pagamentos através de cartões.

RF017 - As senhas de acesso dos pacientes, médicos, funcionários e administradores devem ter no mínimo 8 caracteres, entre números e letras.

RF018 - O administrador não deve ter restrições ao sistema e deverá atribuir grau de acesso a cada usuário do sistema.

RF019 - Para utilizar o sistema, o usuário deverá efetuar o login.

RF020 - Todo usuário cadastrado deverá receber o status ATIVO, caso não seja mais permitido o acesso, passará para o status INATIVO

RF021 - O Sistema deverá permitir o cadastro de parceiros e fornecedores.

RF022 - Caso um paciente cancele uma consulta, o sistema enviará o cancelamento ao Médico, e já realoca os horários livres para possíveis novas consultas.

RF023 - Caso o médico cancele uma consulta, o sistema envia uma mensagem de cancelamento ao Paciente que terá prioridade na marcação de uma próxima consulta.


## Requisitos Não Funcionais

RNF01 - O sistema deverá ser desenvolvido para plataforma Web, acessível por meio de qualquer navegador.

RNF02 - O sistema deverá possuir controle de acesso por usuário e senha.

RNF03 - As senhas devem ser armazenadas criptografadas no banco de dados.

RNF04 - O sistema deverá realizar todas as funcionalidades de inserção, busca, entre outros num tempo considerado aceitável, para evitar esperas pelo lado do utilizador.

RNF05 - O sistema deverá realizar log de acesso.

RNF06 - O sistema deve estar disponível de segunda às sexta-feira das 08:00 às 19:00 e no sábado das 08:00 às 12:00. 

RNF07 – O sistema deverá disponibilizar acesso às informações seguindo normas instituídas pelo CREMESP.

RNF08 - O banco de dados utilizado deve ser ORACLE.

RNF09 - O Web Server deve ser SQL Server Express.

RNF010 - Os dados informados no campo usuário e senha deverão ser validados junto ao cadastro de usuário no banco de dados.

##Diagrama de Atividade

###[Agenda da consultas](https://drive.google.com/open?id=0B_CGtlMvgSccc0V1OXNYTkxPdlE)

###[Cadastro de exames](https://drive.google.com/open?id=0B_CGtlMvgSccY09WYmRGaXBacnM)

###[Cadastro de medicamentos](https://drive.google.com/open?id=0B_CGtlMvgSccV1ZuS2VkdkxPaUk)

###[Cadastro de pacientes](https://drive.google.com/open?id=0B_CGtlMvgScceUFDU19UaHBBR1k)

##Diagrama de Caso de Uso

###[Caso de uso](https://drive.google.com/open?id=0B_CGtlMvgSccSXhOMnp0UG5tb1E)


##Protótipo Visual

###[Página Inicial - Administrador](https://drive.google.com/open?id=0B_CGtlMvgSccVU1TX3E1elJZdEE)

###[Página Inicial - Atendente](https://drive.google.com/open?id=0B_CGtlMvgSccQnBXOVpiUFRIOEE)

###[Página Inicial - Médico](https://drive.google.com/open?id=0B_CGtlMvgSccMnRiYjFKUkptQ1k)

###[Página Inicial - Paciente](https://drive.google.com/open?id=0B_CGtlMvgSccV2Z0RHQ5ZVhxdFk)
