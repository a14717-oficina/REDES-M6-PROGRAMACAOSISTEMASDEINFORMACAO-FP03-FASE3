# REDES-M6-PROGRAMACAOSISTEMASDEINFORMACAO-FP03-FASE3-14717


Sistema de Gestão de Equipamentos e Intervenções

Olá! Bem-vindo(a) ao repositóri

o do nosso Sistema de Gestão de Equipamentos e Intervenções. Este projeto nasceu da necessidade de organizar e otimizar a manutenção de ativos, garantindo que nenhum equipamento seja esquecido e que todas as intervenções sejam devidamente registadas e acompanhadas. Acreditamos que uma gestão eficiente é a chave para a longevidade dos equipamentos e a satisfação dos clientes.

Visão Geral do Projeto
No coração de muitas operações, a gestão de equipamentos e a coordenação de intervenções de manutenção podem ser um verdadeiro desafio. Este sistema foi concebido para simplificar esse processo, oferecendo uma plataforma robusta e intuitiva para:
•
Registar e acompanhar equipamentos: Desde a sua aquisição até ao seu desmantelamento.
•
Gerir intervenções: Planear, executar e registar todas as ações de manutenção, preventivas ou corretivas.
•
Associar clientes e técnicos: Manter um registo claro de quem possui o quê e quem faz o quê.
•
Identificar necessidades: Detetar rapidamente equipamentos que necessitam de atenção ou que estão sem histórico de manutenção.
O nosso objetivo é proporcionar uma ferramenta que não só organize os dados, mas que também forneça insights valiosos para a tomada de decisões, tornando a gestão de ativos mais proativa e menos reativa.
 Funcionalidades Principais
 •
Registo Detalhado de Equipamentos: Armazenamento de informações cruciais como nome, modelo, número de série, data de aquisição e cliente associado.
•
Gestão de Intervenções: Criação, edição e visualização de registos de manutenção, incluindo data, descrição do trabalho, custo e técnico responsável.
•
Base de Dados de Clientes: Gestão de informações de contacto e histórico de equipamentos por cliente.
•
Base de Dados de Técnicos: Registo de técnicos com as suas especialidades e intervenções atribuídas.
•
Relatórios e Consultas: Capacidade de gerar listas de equipamentos, intervenções, e, crucialmente, identificar equipamentos sem intervenções para garantir que nada fica para trás.
Integridade de Dados: Utilização de chaves estrangeiras para assegurar a consistência e validade das relações entre os dados.
 Tecnologias Utilizadas
Este projeto foi desenvolvido com foco na robustez e escalabilidade, utilizando as seguintes tecnologias:
•Base de Dados: SQL (e.g., MySQL, PostgreSQL, SQLite) - para armazenamento e gestão eficiente dos dados.
•Linguagem de Programação: (Assumir uma linguagem, e.g., Python, Java, C#) - para a lógica de negócio e interação com a base de dados.
•
Framework: (Assumir um framework, e.g., Flask/Django para Python, Spring Boot para Java, ASP.NET Core para C#) - para a construção da aplicação web/API.
•
Frontend: (Assumir tecnologias, e.g., HTML, CSS, JavaScript, React/Vue/Angular) - para a interface de utilizador (se aplicável).

 Estrutura da Base de Dados
Para garantir uma organização lógica e eficiente, a nossa base de dados é composta por quatro tabelas principais, cada uma com um propósito bem definido e interligadas por chaves estrangeiras (FKs) para manter a integridade referencial:

1.
Equipamentos: Contém todos os detalhes sobre os ativos que estão a ser geridos.

2.
Intervencoes: Regista cada ação de manutenção realizada, associada a um equipamento e a um técnico.

3.
Clientes: Armazena as informações dos clientes que possuem os equipamentos.

4.
Tecnicos: Guarda os dados dos profissionais responsáveis pelas intervenções.

As chaves estrangeiras são vitais aqui, pois garantem que, por exemplo, uma intervenção esteja sempre ligada a um equipamento existente, e um equipamento a um cliente válido. Isso evita erros e mantém a base de dados limpa e fiável.



