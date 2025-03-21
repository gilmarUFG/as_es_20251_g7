# Matriz de Mapeamento entre Requisitos Funcionais e Não Funcionais

## Requisitos Funcionais (RF)

1. **RF1 - Login e autenticação de usuários**
   - O sistema deve permitir que os usuários se registrem, façam login e acessem suas contas.
   
2. **RF2 - Cadastro de clientes**
   - O sistema deve permitir que novos clientes se cadastrem e adicionem informações pessoais, como nome, e-mail e telefone.
   
3. **RF3 - Busca e filtragem de hotéis**
   - O sistema deve permitir aos usuários buscar hotéis com base em diferentes critérios, como localização, preço, avaliações, etc.

4. **RF4 - Reserva de hotel**
   - O sistema deve permitir que os usuários façam reservas de quartos em hotéis, com informações sobre datas, tipo de quarto, número de hóspedes e outros detalhes.

5. **RF5 - Pagamento no aplicativo**
   - O sistema deve permitir que os usuários façam pagamentos pelas reservas diretamente no aplicativo, com suporte a diferentes métodos de pagamento.

6. **RF6 - Histórico de reservas**
   - O sistema deve manter um histórico de todas as reservas feitas pelo usuário, permitindo visualização e gerenciamento.

7. **RF7 - Notificação de confirmação de reserva**
   - O sistema deve enviar uma notificação por e-mail ou SMS para o usuário confirmando a reserva do hotel.

8. **RF8 - Alteração de reserva**
   - O sistema deve permitir que os usuários alterem os detalhes de suas reservas, como datas, tipo de quarto, etc.

9. **RF9 - Avaliação de hotel**
   - O sistema deve permitir que os usuários avaliem o hotel após a estadia, deixando feedback sobre sua experiência.

10. **RF10 - Suporte ao cliente**
    - O sistema deve fornecer um canal de suporte ao cliente, para resolver dúvidas ou problemas dos usuários.

11. **RF11 - Sistema de fidelidade**
    - O sistema deve permitir que os usuários acumulem pontos ou benefícios a cada reserva, os quais podem ser usados para obter descontos ou outros benefícios.

12. **RF12 - Recomendações personalizadas**
    - O sistema deve sugerir hotéis aos usuários com base nas preferências e comportamento anterior deles.

13. **RF13 - Chat ao vivo com o hotel**
    - O sistema deve permitir que os usuários conversem com o hotel em tempo real, para esclarecer dúvidas sobre reservas ou serviços.

14. **RF14 - Promoções e ofertas especiais**
    - O sistema deve permitir que os hotéis publiquem e os usuários visualizem promoções especiais, como descontos ou pacotes exclusivos.

---

## Requisitos Qualidade (RQ)

1. **RQ1 - Desempenho**
   - O sistema deve ser capaz de processar todas as operações (busca, reservas, pagamentos, etc.) rapidamente, sem impactar a experiência do usuário. A latência deve ser minimizada, garantindo uma resposta rápida mesmo com grande número de usuários simultâneos.

2. **RQ2 - Segurança**
   - O sistema deve proteger as informações pessoais dos usuários, como dados de login, informações de pagamento e histórico de reservas, através de criptografia e outras técnicas de segurança. A segurança deve ser priorizada, especialmente nas funcionalidades de pagamento e armazenamento de dados pessoais.

3. **RQ3 - Usabilidade**
   - O sistema deve ser fácil de usar e intuitivo, garantindo que qualquer usuário consiga realizar operações sem dificuldades. A navegação entre telas deve ser simples e direta, com design claro e funcional.

4. **RQ4 - Escalabilidade**
   - O sistema deve ser capaz de lidar com um aumento significativo no número de usuários e transações sem comprometer o desempenho. Isso inclui garantir que as funcionalidades, como busca e reserva, funcionem bem com grandes volumes de dados e interações simultâneas.

5. **RQ5 - Disponibilidade**
   - O sistema deve estar disponível 24/7, com tempo de inatividade mínimo. Isso é particularmente importante para garantir que as funcionalidades essenciais, como login, reserva e pagamento, estejam sempre acessíveis aos usuários.

6. **RQ6 - Manutenibilidade**
   - O sistema deve ser fácil de manter e atualizar, com um código bem estruturado e documentação clara. Isso facilita a adição de novas funcionalidades, a correção de bugs e a adaptação a novos requisitos sem grandes esforços.

7. **RQ7 - Conformidade com regulamentações**
   - O sistema deve estar em conformidade com leis e regulamentações aplicáveis, como a Lei Geral de Proteção de Dados (LGPD) ou o Regulamento Geral de Proteção de Dados da União Europeia (GDPR). Além disso, deve seguir as normas de segurança exigidas para o processamento de transações financeiras (como PCI-DSS).

---

## Matriz de Mapeamento entre Requisitos Funcionais e Não Funcionais

| **Requisitos Funcionais / Requisitos Não Funcionais** | **RQ1 - Desempenho** | **RQ2 - Segurança** | **RQ3 - Usabilidade** | **RQ4 - Escalabilidade** | **RQ5 - Disponibilidade** | **RQ6 - Manutenibilidade** | **RQ7 - Conformidade com regulamentações** |
|-------------------------------------------------------|----------------------|----------------------|------------------------|--------------------------|----------------------------|----------------------------|-------------------------------------------|
| **RF1 - Login e autenticação de usuários**            | Médio                | Alta                 | Alta                   | Médio                    | Alta                       | Médio                      | Alta                                      |
| **RF2 - Cadastro de clientes**                        | Médio                | Alta                 | Alta                   | Médio                    | Alta                       | Médio                      | Alta                                      |
| **RF3 - Busca e filtragem de hotéis**                 | Alta                 | Média                | Alta                   | Alta                     | Alta                       | Médio                      | Médio                                     |
| **RF4 - Reserva de hotel**                            | Alta                 | Alta                 | Alta                   | Alta                     | Alta                       | Médio                      | Alta                                      |
| **RF5 - Pagamento no aplicativo**                     | Médio                | Alta                 | Alta                   | Médio                    | Alta                       | Médio                      | Alta                                      |
| **RF6 - Histórico de reservas**                       | Médio                | Alta                 | Alta                   | Médio                    | Alta                       | Médio                      | Médio                                     |
| **RF7 - Notificação de confirmação de reserva**       | Baixo                | Média                | Alta                   | NI                       | Alta                       | Baixo                      | Médio                                     |
| **RF8 - Alteração de reserva**                        | Médio                | Alta                 | Alta                   | Médio                    | Alta                       | Médio                      | Médio                                     |
| **RF9 - Avaliação de hotel**                          | Baixo                | Média                | Alta                   | NI                       | Alta                       | Baixo                      | Médio                                     |
| **RF10 - Suporte ao cliente**                         | Médio                | Alta                 | Alta                   | Médio                    | Alta                       | Médio                      | Médio                                     |
| **RF11 - Sistema de fidelidade**                      | Médio                | Média                | Alta                   | Médio                    | Alta                       | Médio                      | Médio                                     |
| **RF12 - Recomendações personalizadas**               | Alta                 | Média                | Alta                   | Alta                     | Alta                       | Médio                      | Médio                                     |
| **RF13 - Chat ao vivo com o hotel**                   | Médio                | Alta                 | Alta                   | Médio                    | Alta                       | Médio                      | Médio                                     |
| **RF14 - Promoções e ofertas especiais**              | Médio                | Média                | Alta                   | Médio                    | Alta                       | Médio                      | Médio                                     |

---

## Explicações Detalhadas

### **Requisitos Funcionais (RF)**

- **RF1 - Login e autenticação de usuários**:
  - Permite que os usuários se registrem e façam login no sistema, o que envolve a verificação de credenciais e o gerenciamento de sessões.
  
- **RF2 - Cadastro de clientes**:
  - Permite que os usuários se cadastrem, fornecendo dados pessoais, como nome, e-mail, e telefone, para poderem realizar reservas.

- **RF3 - Busca e filtragem de hotéis**:
  - O sistema oferece funcionalidades de busca e filtragem, permitindo que o usuário encontre hotéis com base em critérios como localização, preço, e avaliações.

- **RF4 - Reserva de hotel**:
  - O usuário pode selecionar um hotel, escolher datas e tipo de quarto, e finalizar a reserva.

- **RF5 - Pagamento no aplicativo**:
  - Permite que os usuários efetuem pagamentos diretamente pelo aplicativo, com diferentes formas de pagamento, como cartão de crédito, débito ou outros métodos.

- **RF6 - Histórico de reservas**:
  - O sistema mantém um histórico das reservas passadas do usuário, permitindo-lhe visualizar detalhes de suas reservas anteriores.

- **RF7 - Notificação de confirmação de reserva**:
  - O sistema envia uma notificação ao usuário confirmando sua reserva, seja por e-mail ou mensagem de texto.

- **RF8 - Alteração de reserva**:
  - Os usuários podem alterar reservas feitas, incluindo ajustes nas datas, tipo de quarto ou outras condições.

- **RF9 - Avaliação de hotel**:
  - Após a estadia, os usuários podem avaliar o hotel com base na sua experiência, o que ajuda outros clientes na escolha de acomodações.

- **RF10 - Suporte ao cliente**:
  - O sistema oferece suporte ao cliente para resolver problemas ou tirar dúvidas, com opções como chat ou formulário de contato.

- **RF11 - Sistema de fidelidade**:
  - Permite que os usuários acumulem pontos ou recompensas em cada reserva, podendo resgatar benefícios ou descontos.

- **RF12 - Recomendações personalizadas**:
  - O sistema usa dados de comportamento anterior do usuário para sugerir hotéis que atendam às suas preferências.

- **RF13 - Chat ao vivo com o hotel**:
  - O sistema oferece uma funcionalidade de chat em tempo real, permitindo que os usuários se comuniquem diretamente com o hotel para tirar dúvidas ou ajustar detalhes de sua reserva.

- **RF14 - Promoções e ofertas especiais**:
  - O sistema oferece a possibilidade de divulgar promoções e descontos para os usuários, permitindo-lhes aproveitar ofertas exclusivas.

### **Requisitos Qualidade (RQ)**

- **RQ1 - Desempenho**:  
  - O sistema precisa garantir uma resposta rápida, especialmente para funcionalidades como busca de hotéis e processamento de pagamentos.

- **RQ2 - Segurança**:  
  - A segurança é crucial, já que o sistema lida com dados pessoais sensíveis e transações financeiras. Técnicas como criptografia devem ser utilizadas para proteger esses dados.

- **RQ3 - Usabilidade**:  
  - O sistema deve ser intuitivo, com uma interface amigável que permita que qualquer usuário, mesmo sem experiência prévia, consiga navegar facilmente pelas funcionalidades.

- **RQ4 - Escalabilidade**:  
  - O sistema deve ser capaz de crescer, acomodando mais usuários e transações sem comprometer o desempenho, o que é especialmente importante em períodos de pico.

- **RQ5 - Disponibilidade**:  
  - O sistema deve estar disponível o tempo todo, com mínima interrupção de serviço, para garantir que os usuários possam acessar as funcionalidades essenciais em qualquer momento.

- **RQ6 - Manutenibilidade**:  
  - O código do sistema deve ser bem estruturado e fácil de manter, permitindo atualizações, correções e a adição de novas funcionalidades sem grandes dificuldades.

- **RQ7 - Conformidade com regulamentações**:  
  - O sistema deve seguir as normas legais e regulatórias, como a LGPD (Lei Geral de Proteção de Dados) no Brasil e as regulamentações de pagamento (como PCI-DSS), garantindo que os dados dos usuários sejam tratados de forma legal e segura.
