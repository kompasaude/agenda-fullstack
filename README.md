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

> Aqui na Assina, nós usamos Django e React, mas caso você não seja muito familiar com elas, considere utilizar frameworks semelhantes como Ruby on Rails, Laravel, Vue ou Angular.
> Nenhuma rota precisa de autenticação!

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

![Confirmacao](/Confirmacao.png?raw=true "Confirmação")

Na tela de confirmação, o usuário pode visualizar os dados do agendamento que ele acabou de criar.

### Especificações da API

Sinta-se à vontade para implementar a API como você quiser, lembrando de sempre seguir boas práticas de código e as especificações RESTful.

### Enviando o seu projeto

1. Faça o upload do código para o Github
2. Envie o link do repositório para feliciano@assinasaude.com.br, com instruções de como rodar o projeto e quaisquer outras informações que você achar importante mencionar.
Por exemplo:

> Para rodar o projeto, executar npm install e npm start. Não pude concluir a parte X, mas com mais tempo eu a implementaria usando a biblioteca Y.

3. Tudo pronto! Agora entraremos em contato assim que avaliarmos a sua submissão.

### Critérios de Avaliação

1. **Corretude**: o seu código deve ser correto, isso é, ele deve fazer tudo que o desafio te propôs.
Não vamos testar cada caso especial, mas casos que podem ser razoavelmente esperados durante o uso normal do sistema não devem ter bugs triviais.

2. **Design / Usabilidade**: O design de cada solução deve ser no mínimo funcional e obedecer aos padrões estabelecidos nas screenshots acima.

3. **Performance**: As suas soluções não devem travar o navegador por nenhum período de tempo sob situações de uso normal.

4. **Qualidade do código**: O seu código deve respeitar algumas regras básicas de qualidade como de-duplicação e deve evitar o máximo de mau cheiros de código possível.
Sua submissão também se destaca se você utilizar uma ferramenta como o ESLint para manter o estilo consistente em todos os arquivos.

### Critérios opcionais:

Você só precisa se preocupar com esses critérios se tiver tempo extra, mas você definitivamente vai se destacar!

1. **Responsividade**: Vamos testar prioritariamente em dispositivos móveis, mas se você garantir que o seu layout fique agradável no desktop, mais pontos pra você!

2. **Testes Unitários**: [Código sem testes é código quebrado por design](https://jacobian.org/2009/apr/15/django-apps-with-buildout/). Se você escrever testes para os casos mais básicos de uso, com certeza terá bastante destaque!

3. **Histórico de commits**: Não estamos preocupados com o horário de cada commit, mas gostaríamos que seus commits seguissem uma ordem lógica e tivessem mensagens descritivas de cada alteração que ocorreu.

4. **Tratamento de erros**: Tratar o que acontece quando a API está indisponível ou a internet do usuário caiu é parte importantíssima para usabilidade. Pontos extras se exibir uma mensagem amigável quando ocorrerem erros na comunicação com a API.

5. **Animações**: Adoramos utilizar animações para tornar a experiência mais agradável e responsiva. Se você utilizar transações de tela e microanimações, vamos mostrar seu projeto pra todo mundo no escritório.

6. **Sua criatividade**: Sinta-se encorajado para adicionar quaisquer outras features que você quiser, contanto que você as mencione quando enviar seu projeto (para que possamos procurar por elas!).

### Problemas ou dúvidas?

[Abra uma nova issue](/issues)!
