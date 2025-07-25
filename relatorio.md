### S.O. 2025.1 - Atividade 2.01  
# Relatório de visita a [DIGTI](https://portal.ifrn.edu.br/institucional/tecnologia-da-informacao/)

#### - **Disciplina:** Sistemas Operacionais 
#### - **Curso**: Tecnologia em Análise e Desenvolvimento de Sistemas
#### - **Aluno:** Josephy Cruz Araújo
#### - **Data da Visita:** 27/06/2025
#### - **Local Visitado:** Diretoria de Gestão de Tecnologia da Informação (DIGTI) – IFRN Campus Natal-Central

---
## **1. Introdução**  
A visita técnica à Diretoria de Gestão de Tecnologia da Informação (DIGTI) do Instituto Federal do Rio Grande do Norte (IFRN) foi realizada como parte das atividades da disciplina de Sistemas Operacionais (SO), com o objetivo de integrar os conhecimentos teóricos discutidos em sala de aula com as práticas adotadas em um ambiente corporativo de TI de grande escala.

A DIGTI é responsável por gerenciar toda a infraestrutura de Tecnologia da Informação e Comunicação (TIC) dos campi do IFRN, incluindo serviços críticos como redes, servidores, segurança da informação, desenvolvimento de sistemas e suporte técnico. Durante a visita, os servidores Tarso Latorraca (Diretor da DIGTI) e Lucas Silva apresentaram a estrutura, os desafios e as soluções implementadas, permitindo uma compreensão aprofundada de como os conceitos de gerência de processos, sistemas distribuídos, autenticação e virtualização são aplicados na prática.

---

## **2. Descrição do Ambiente Visitado** 
A DIGTI é responsável por coordenar os serviços de Tecnologia da Informação e Comunicação (TIC) em todos os campi do IFRN. Durante a visita, foram apresentados os seguintes aspectos:

### **2.1. Equipe e Funções: **
A equipe é multidiciplinar, composta por profissionais de TI, Redes, Engenharia da Computação e de Software. Dentre as funções desempenhadas pela equipe, destacam-se: 
  - Administradores de Sistemas: Gerenciam servidores físicos/virtuais, Active Directory e serviços de autenticação;
  - Suporte Técnico: Atendem chamados, oferecendo suporte a usuários e manutenção de equipamentos;
  - Analistas de Redes: Responsáveis pela infraestrutura lógica e física de redes, VoIP e segurança.

### **2.2. Estrutura Organizacional: **
A DIGTI é composta por setores especializados, que foram destacados conforme os slides apresentados:

- Gestão da Segurança da Informação:
  - Implementação da Política de Segurança da Informação e Comunicação (POSIC), alinhada à Lei Geral de Proteção de Dados (LGPD).
  - Controle de acesso físico e lógico, resposta a incidentes cibernéticos e campanhas de conscientização.

- Governança em TIC:
  - Elaboração do Plano Diretor de TIC (PDTIC), que define as prioridades estratégicas da área.
  - Gestão de dados abertos e indicadores de desempenho.

- Gestão de Serviços de TIC: 
  - Portfólio de serviços organizado em catálogos (ex.: GLPI para chamados técnicos).
  - Suporte técnico aos usuários, administração de e-mail institucional (Exchange) e telefonia VoIP.

- Infraestrutura de TIC:
  - Datacenter com servidores físicos, virtuais (VMware) e ambientes em nuvem.
  - Active Directory (AD), LDAP e Single Sign-On (SSO) para autenticação centralizada.
  - Monitoramento em tempo real com Zabbix para garantir disponibilidade.

- Desenvolvimento de Sistemas:
  - SUAP (Sistema Unificado de Administração Pública): plataforma modular para gestão acadêmica e administrativa.
  - Integrações com sistemas externos (e-MEC, SEI, SCDP) via APIs.
  - Versionamento de código com Git (repositórios institucionais).

---

## **3. Aprendizados e Destaques**  

### **3.1. Relação entre Teoria e Prática**
  - Gerência de Processos e Recursos:
    - A virtualização de servidores (VMware) exemplificou como um hypervisor aloca recursos de CPU, memória e disco entre máquinas virtuais, tema estudado em SO.
    - O Active Directory demonstrou na prática a gerência de usuários, grupos e permissões, essencial para administração de sistemas.

  - Segurança e Autenticação:
    - A implementação de Single Sign-On (SSO) e LDAP mostrou como a autenticação centralizada melhora a segurança e a usabilidade.
    - A Política de Segurança (POSIC) reforçou a importância de controles de acesso, criptografia e resposta a incidentes, tópicos discutidos em aulas sobre proteção de sistemas.

  - Redes e Monitoramento:
    - O uso do Zabbix para monitoramento de redes e servidores ilustrou a aplicação de ferramentas de gerência de desempenho, relacionadas a conceitos de escalabilidade e disponibilidade.

### **3.2. Ferramentas e Técnicas Inovadoras**
  - SUAP como Plataforma Integrada:
    - Desenvolvido internamente, o SUAP utiliza módulos acadêmicos e administrativos, demonstrando a aplicação de sistemas distribuídos.
    - A integração com APIs de sistemas governamentais (e-MEC, SEI) mostrou a importância de interoperabilidade.

  - Gestão de Incidentes com GLPI:
    - O sistema de chamados técnicos evidenciou a organização de filas de atendimento e Service Level Agreements (SLAs), conceito relevante para administração de sistemas.

### **3.3. Desafios Enfrentados pela Equipe de TI**
  - Escalabilidade:
    - A necessidade de atender mais de 20 campi exige balanceamento de carga e infraestrutura robusta.

  - Segurança vs. Usabilidade:
    - Equilibrar políticas rígidas de segurança (ex.: autenticação multifator) com a facilidade de uso para professores e alunos.

  - Atualização Tecnológica:
    - Manter sistemas legados (ex.: módulos antigos do SUAP) compatíveis com novas tecnologias.  

---

## **4. Considerações Finais**  
A visita à DIGTI proporcionou uma visão holística da operação de TI em uma grande instituição pública, reforçando a aplicação prática dos conceitos de Sistemas Operacionais. Durante a visita, foi possível perceber a cultura de melhoria contínua dentro da diretroria e que o Plano de Dados Abertos do IFRN demonstra transparência e alinhamento com as melhores práticas de governo digital.
Dentro os aprendizados, em especial, destaco:
  - A integração entre teoria (SO) e prática (gestão de servidores, redes e segurança).
  - A importância da governança em TIC para o alinhamento estratégico.
  - O papel crítico do SUAP na gestão acadêmica e administrativa do IFRN.

Espero que em próximas visitas consigamos ter uma maior demonstração de gerenciamento de containers (Docker/Kubernetes), cada vez mais utilizado em ambientes de TI, além da visita técnica ao datacenter para entender a estrutura física (racks, refrigeração, no-breaks).

---
