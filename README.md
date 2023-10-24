O Projeto Academico Invetech FUABC busca aprimorar o gerenciamento de ativos de tecnologia em seu parque tecnológico, composto por diversas unidades básicas de saúde.
O objetivo deste projeto é criar uma plataforma de inventário de ativos e abertura de chamados de TI abrangente e intuitiva, que permitirá monitorar, acompanhar e gerenciar eficientemente todos os recursos tecnológicos em suas unidades. 

Objetivo do Projeto: 
O projeto visa desenvolver e implementar uma plataforma de inventário de ativos de TI + sistema de chamados que atenda às necessidades específicas da TI. 
A plataforma permitirá o registro, acompanhamento e gerenciamento de hardware, software, licenças e outros ativos tecnológicos em todas as unidades básicas de saúde mais abertura de chamados para os analistas darem o devido suporte. 
1.	Registro de Ativos: Possibilidade de registrar e categorizar todos os ativos de TI, incluindo computadores, servidores, dispositivos móveis, software e licenças. 
2.	Sistema de Chamados: A capacidade de abrir chamados e acompanhamento dele, permitindo uma gestão e resolução de problema mais eficaz. 
3.	Gestão de Licenças: Acompanhamento de licenças de software, datas de expiração e conformidade de licenciamento. 
4.	Relatórios Personalizados: Geração de relatórios personalizados para avaliar o uso de ativos, custos de manutenção e necessidades de atualização. 
5.	Alertas e Notificações: Notificações automáticas de eventos críticos, como vencimento de licenças ou manutenção necessária. 
6.	Segurança de Dados: Implementação de medidas de segurança robustas para proteger informações confidenciais. Benefícios Esperados. 
A plataforma de inventário de ativos do parque tecnológico proporcionará diversos benefícios, incluindo maior visibilidade e controle sobre os ativos de TI. 
7.	Otimização de custos por meio de uma gestão eficiente de ativos.
8.	Melhoria na segurança de dados e conformidade de licenciamento. 
9.	Facilitação da tomada de decisões informadas com base em dados precisos. 

Instalação 

## REQUIREMENTS:


+ Web-server with Apache (***not tested in others servers***) + PHP + MySQL (or MariaDB):
    
    - PHP at least from version **7.4** with:
        - PDO
        - pdo_mysql
        - mbstring
        - openssl
        - imap
        - curl
        - iconv
        - gd
        - ldap
    
    - MySQL at least version 5.6 or MariaDB(at least version 10.2):

    - For integration (through API) or to enable the opening of tickets by email:
         - Apache must allow URL rewriting (to direct API routes via htaccess);
         - The "mod_rewrite" module must be enabled in Apache;


Ederson Alves da Silva


