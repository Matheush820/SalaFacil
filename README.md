# SalaFácil - Sistema de Reserva de Salas para Professores da Uninassau

Autor: Matheus Henrique dos Santos - Matrícula: 01675026

# Introdução

O projeto SalaFácil consiste em um sistema que facilita a reserva de salas, permitindo que professores verifiquem a disponibilidade e façam reservas de laboratórios de informática, saúde e outros espaços, de acordo com suas necessidades

# Visão Geral do Projeto
SalaFácil surgiu para solucionar as dificuldades enfrentadas pelos professores da Uninassau na reserva de salas, tornando o processo mais ágil e acessível.

# Capacidades Técnicas
- Reserva de Salas: Professores devem poder reservar salas de informática, saúde, ou outras através de uma interface web intuitiva.

- Carregamento Assíncrono: Uso de chamadas assíncronas (AJAX) para melhorar a performance do front-end e minimizar o tempo de carregamento.

- Proteção Contra CSRF e XSS: Uso de técnicas como tokens CSRF e sanitização de entrada para proteger contra ataques Cross-Site Request Forgery (CSRF) e Cross-Site Scripting (XSS).

- Desempenho Escalável: O código deve ser otimizado para suportar um aumento no número de usuários sem degradação significativa na performance.

-Interface Responsiva: O sistema será acessível via dispositivos móveis e desktops.

# Ferramentas de Desenvolvimento

A SalaFácil incorpora uma série de técnicas avançadas que a torna uma escolha ideal para o seu desenvolvimento

O projeto vem equipado com uma série de ferramentaas de desenvolvimento, essenciais para um projeto com um resultado positivo e funcional
- Front-End: HTML5, CSS3, JavaScript, Bootstrap, React
- Back-End: Python(flask ou Django)
- Banco de Dados: PostgreSQL
- Segurança: Helmet
- Teste: Jest, Postman
- Design: Figma
- Documentação: Markdown(Github), Swagger
- Monitoramento: Sentry
- Gestão de Projetos Ágeis: Jira, Trello ou ClickUp
- Hospedagem e Deploy: AWS, Heroku ou Google Cloud 
- 
# Estrutura de Equipe
Front-End Developers: 1 a 2 pessoas focadas em React.

Back-End Developers: 1 a 2 pessoas focadas em Python (Flask ou Django).

Designers: 1 a 2pessoa responsável por criar o layout e protótipos no Figma.

QA/Testers: 1 pessoa para garantir que as funcionalidades estão corretas e realizar testes com Postman e Jest.

Gerente de Projeto: 1 pessoa para gerenciar o andamento e garantir que todos estejam na mesma página.

# Definições de requisitos

Funcionalidades Principais: O que o sistema precisa fazer? Exemplo: permitir reservas de salas, notificar conflitos de horários, criar contas de professores, etc.

Regras de Negócio: Defina como as reservas funcionarão. Quem pode reservar? Por quanto tempo? Como lidar com conflitos de reservas?

Escopo: Delimite até onde o sistema vai. Evite adicionar muitas funcionalidades extras que não são essenciais inicialmente.

Público-Alvo: Quem vai usar o sistema (neste caso, professores)? Que tipo de experiência eles esperam?

Conflitos de Reserva: Caso duas reservas sejam feitas para o mesmo horário, o sistema deve priorizar a primeira e notificar a outra parte.

Acesso de Usuários: Apenas professores poderão criar reservas, enquanto administradores poderão gerenciar usuários e horários

# Conclusão

O projeto será testado por professores em máquinas virtuais. Este processo é crucial para garantir que o sistema esteja rodando perfeitamente, adquirindo um bom desempenho e usabilidade.

