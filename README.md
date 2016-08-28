# SistemaClinicaMedica

FACULDADE DE TECNOLOGIA DE MOGI DAS CRUZES
ANÁLISE E DESENVOLVIMENTO DE SISTEMAS
DISCIPLINA DE ENGENHARIA DE SOFTWARE II 

Lucas Júlio

Marco Antonio

Paulo Henrique



CLÍNICA MÉDICA

1.  Clínica Médica:
Realiza atendimento referente a uma ou diversas  especialidades, proporciona assistência   à prevenção, tratamento e recuperação de saúde, mediante atendimento médico, de acordo com sua especialidade.

2. Funcionamento:
Deve manter registro de todos os seus pacientes, bem como de seus funcionários. Além disso, na clínica ocorre a marcação de consultas, exames e outros procedimentos.  Logo que estas sejam marcadas o médico deverá realizar a consulta no período devidamente agendado, podendo solicitar exames e receitar medicamentos para os pacientes que ali foram atendidos.

2. Trabalhadores de Negócio:

Funcionários da Clínica

2. Atores de Negócio
Paciente, Atendente, Médico e Administrador.

3. Atividades de Negócio
Agendamento de consultas online, atendimento pessoal personalizado para as consultas médicas (oftalmologista, cardiologista, otorrinolaringologista, dermatologista, ginecologista, urologista, endocrinologista, gastroenterologista, oncologista, neurologista, ortopedista, angiologista, nutricionista e psiquiatria).

4. Regras de Negócio
RN01 - Senhas devem ter no mínimo oito caracteres, entre números e letras.

RN02 - Todos os campos do cadastro de pacientes são obrigatórios.

RN03 - As informações sobre os pacientes devem seguir as normas instituídas pelo CREMESP.

RN04 - Todos os funcionários deverão preencher o termo de confidencialidade de informações.

RN05 - O administrador não deve ter restrições ao sistema e deverá atribuir grau de acesso a cada usuário do sistema.

RN06 - O cadastro poderá ser atualizado quando houver alteração de dados de funcionários ou de pacientes. Todos os campos poderão ser alterados, exceto RG e CPF.

RN07 - Os dados informados no campo usuário e senha deverão ser validados junto ao cadastro de usuário no banco de dados. 

RN08 - Para utilizar o sistema, o usuário deverá efetuar o login.

RN09 - Todo usuário cadastrado deverá receber o status ATIVO, caso não seja mais permitido o acesso, passará para o status INATIVO

RN10 - Pacientes menores de dezoito anos, deverão ser cadastrados somente por seus responsáveis.

RN11- Fornecedores e parceiros devem possuir cadastro no sistema.

RN12 - Pagamentos podem ser efetuados com dinheiro, cheque ou cartões de crédito.

RN13 – Qualquer cancelamento de consulta por parte do cliente deverá ter um aviso de até   48 horas de antecedência. Caso contrário, uma multa será aplicada.

RN14 – A clínica deve manter convênios com UNIMED, SAMED, BRADESCO SAÚDE, AMIL, SULAMÉRICA SAÚDE, GOLDEN CROSS e CRUZ AZUL, os quais deverão estar cadastrados no sistema.

RN15 - Planos de Saúde devem estar registrados na ANS (Agência Nacional de Saúde Suplementar), que regula o setor.

RN16 - O paciente não poderá marcar duas consultas no mesmo horário.

RN17 - Somente o atendente poderá cadastrar novos pacientes

RN18 - O paciente não poderá realizar o pedido de um exame sem guia médico

RN19 - O atendente só poderá cadastrar um paciente que tenha o CPF e RG em mãos

RN20 - O paciente deve estar cadastrado para realizar um pedido para consulta médica

RN21 - Em caso de emergência, o paciente não precisará marcar uma consulta

RN22 - Para cada diagnóstico o histórico médico do paciente será atualizado

RN23 - O paciente pode marcar consultas com um ou mais médicos, obedecendo RN16.

RN24 - Um médico pode realizar consultas com um ou mais pacientes

RN25 - Cada consulta é realizada com apenas um médico.

RN26 - Somente o administrador poderá cadastrar novos médicos e atendentes.

RN27 - O Administrador não poderá desmarcar consultas de pacientes

5. Proposta de Solução
Um sistema que permita:
 - Um prontuário eletrônico onde o médico possa acessar as informações de seus pacientes de onde estiver, de maneira totalmente segura. 
- Otimizar tempo da equipe evitando ligações, reduzindo custos de telecomunicação, lembrando o paciente por e-mail ou SMS.
 - Agenda organizada, com um módulo simples, que permita gerenciar de forma rápida e organizada todos os atendimentos da clínica.
 - A agenda que permita gerenciar simultaneamente o atendimento de no mínimo 10 médicos de maneira simples, organizada e eficiente.
-   Migrar o cadastro, bem como prontuários médicos de pacientes de outras clinicas para o sistema.
- Suporte Técnico para resolver as questões mais frequentes de uso da solução, presencialmente ou mesmo online.

6. Requisitos
RF01 - Deverá permitir emissão de relatório de agendamentos de consultas médicas;
RF02 - Deverá permitir alteração da senha de acesso;
RF03 - Deverá permitir o cadastro de pacientes;
RF04 - Deverá permitir o registro de agendamento de consulta;
RF05 - Deverá permitir cadastro de medicamentos;
RF06 - Deverá permitir cadastro de exames complementares;
RF07 - Deverá permitir a geração de receitas;
RF08 - Deverá permitir a geração laudos.;
RF09 - Deverá permitir a consulta a prontuários dos pacientes.
RF10 - Deverá permitir atualização do prontuário....
RF11 - Deverá permitir o cadastro de clínicas médicas.
RF12 - Deverá permitir o cadastro de usuário do sistema.
RF13 - Deverá permitir o cadastro de profissionais médicos.
RF14 - Deverá permitir o cadastro de planos de saúde, convênios.
RF15- Deverá permitir o cadastro de cargos dos funcionários da clínica.

RNF01 - O sistema deverá ser desenvolvido para plataforma Web, acessível por meio de qualquer navegador.
RNF02 - O sistema deverá possuir controle de acesso por usuário e senha.
RNF03 - As senhas devem ser armazenadas criptografadas no banco de dados.
RNF04 - O sistema deve ter tempo de resposta em consultas de no máximo 5 segundos com a rede funcionando   em condições normais.
RNF05 - O sistema deverá realizar log de acesso.
RNF06 - O sistema deve estar disponível de segunda às sexta-feira das 08:00 às 19:00 e no sábado das 08:00 às 12:00. 
RNF07 – O sistema deverá disponibilizar acesso às informações seguindo normas instituídas pelo CREMESP.
RNF08 - O banco de dados utilizado deve ser ORACLE.
RNF09 - O Web Server deve ser SQL Server Express.
