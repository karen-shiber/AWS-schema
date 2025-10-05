# AWS-schema

O diagrama neste repositório representa uma arquitetura AWS baseada em EC2, desenvolvida para consolidar os conceitos de gerenciamento de instâncias.
O fluxo é o seguinte:

1 - O ator (usuário) envia um arquivo por meio de uma interface (API ou sistema web).

2 - A instância EC2 recebe o arquivo e o grava em um volume EBS de entrada (D-EBS).

3 - A EC2 processa o arquivo e gera resultados, que são salvos em um segundo volume EBS (E-EBS).

4 - Informações sobre o processo são registradas no banco de dados RDS.

5 - Toda a infraestrutura está hospedada na nuvem AWS.

Essa estrutura reflete a aplicação prática dos conceitos de EC2, EBS e RDS aprendidos no curso, demonstrando a comunicação entre serviços e o gerenciamento eficiente de instâncias.
