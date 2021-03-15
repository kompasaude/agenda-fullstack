# agenda-fullstack

> Tempo estimado do desafio: 2 horas

Bem-vindo ao teste técnico para se juntar ao time incrível de fullstacks da AssinaSaúde!

O desafio de hoje é construir um sistema de agendamentos de telemedicina simplificado.

> A telemedicina é um processo avançado para monitoramento de pacientes, troca de informações médicas e análise de resultados de diferentes exames. Estes exames são avaliados e entregues de forma digital, dando apoio para a medicina tradicional. A telemedicina já é utilizada em todo mundo, de forma segura e legalizada, estando de acordo com a legislação e as normas médicas. - [portaltelemedicina.com.br](https://portaltelemedicina.com.br/blog/telemedicina-o-que-e-e-como-funciona)

Na Assina Saúde, somos apaixonados por sistemas rápidos e experiências incríveis de saúde.
Para o seu teste, escolhemos essa tarefa pois esse é um típico desafio que você encontrará trabalhando conosco.

Nós sinceramente esperamos que você se divirta com esse desafio e talvez até aprenda algo novo! Happy coding!

### Seu desafio

A tarefa é implementar uma API Rest e um cliente que interaja com essa API.

> Nós **fortemente** preferimos que você use Django e React, mas caso não seja possível, considere utilizar frameworks semelhantes como Ruby on Rais, Laravel, Vue ou Angular.

Seguem as especificações das telas:

#### Agenda

![Agenda](/Agenda.png?raw=true "Agenda")

Na tela de agenda, o usuário pode:

- Visualizar todas as consultas presentes e futuras
- Agendar uma nova consulta, que direciona para a tela de Agendamento.

#### Agendamento

![Agendamento](/Agendamento.png?raw=true "Agendamento")

Na tela de cadastro, o usuário tem 4 campos para preencher, de acordo com as seguintes especificações:

- Especialidade: o usuário seleciona apenas um de uma listagem de especialidades que vem da API Rest.
- Profissional: o usuário seleciona apenas um de uma listagem de profissionais que vem da API Rest. Eles devem ser filtrados de acordo com a especialidade selecionada.
- Data: o usuário seleciona apenas um de uma das datas que o profissional atende. Somente as datas em que o profissional possui agenda disponível devem ser selecionáveis.
- Horário: o usuário seleciona apenas um de um dos horários que o profissional atende naquela data. Somente os horários em que o profissional atende devem ser selecionáveis.

Ao clicar em "Agendar", o sistema deve armazenar a requisição na API e avançar para a tela de confirmação do agendamento.

#### Confirmação de agendamento

![Confirmacao](/images/Confirmacao.png?raw=true "Confirmação")

Na tela de confirmação, o usuário pode visualizar os dados do agendamento que ele acabou de criar.
