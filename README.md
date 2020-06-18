# agendamentos-gobarber-nodejs
Nesse repositório vai ficar armazenado o início do back-end do projeto principal do Bootcamp GoStack da RocketSeat.
Como projeto principal, após apresentar as principais tecnologias e ferramentas que serão utilizados ao longo do Bootcamp, é iniciado o projeto principal do GoStack. Uma aplicação web e mobile para
provedores e clientes de barbearia. Nesse repositório em específico vai ficar a parte inicial do projeto que tem como função criar um agendamento para uma barbearia, listar agendamentos que estão cadastrados e também, retornar erros
caso o cliente queira agendar uma reserva em um horário já reservado. O back-end é construído com NodeJs e Typescript, seguindo patterns de **SoC** e **SRP**, **DRY**, e também uso de eslint, para controle de padrão de código.
A divisão de pastas segue em: **Model**: Para modelar os dados da aplicação, identificar o tipo das variáveis que vão ser utilizadas, os **Repositories**: Que são responsáveis por
modificar os dados, ou seja, dentro dos repositories temos as funções que criam, listam, excluem e editam as variáveis, geralmente temos um repository pra cada model.
**Services**: Para as regras de negócio, que são métodos específicos demais para a rota lidar, então abstraímos e colocamos dentro de uma pasta chamada Services, seguindo os princípios de Separation of Concerns e Single Responsability Principle.
