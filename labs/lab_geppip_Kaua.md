# Geppip - Processos Identitários e Poder (UFS/CECH)
## Nome do Técnico responsável:
Kauã Nascimento Santos
## Resumo descritivo

A presente proposta descreve a infraestrutura necessária à implantação de um laboratório de pesquisa multiusuário destinado ao Grupo de Estudos e Pesquisa Processos Identitários e Poder (Geppip), vinculado à Universidade Federal de Sergipe (UFS).

Na data de elaboração deste documento, o Geppip é composto por 16 integrantes, sendo 5 pesquisadores e 11 estudantes, desenvolvendo pesquisas de natureza teórica, analítica e documental. Após aferição das pesquisas realizadas pelo grupo, verificou-se não haver necessidade de equipamento de hardware ou software específico, permitindo com foco em estações de trabalho de uso geral.

Considerando o caráter multiusuário e compartilhado do laboratório, assim como o fato de que todos os integrantes do Geppip não utilizam o espaço simultaneamente, já que as pesquisas são realizadas em grupos menores, afinal, os membros fragmentam-se em distintas pesquisas. Com isso m mente, propõe-se a seguinte infraestrutura:

- 7 computadores Desktop (4 cores (8 threads), 8gb, 500gb de armazenamento interno (SSD));
- 7 monitores 24";
- 7 kits de teclado e mouse;
- 7 cadeiras;
- 4 mesas (160x60x74cm);
- 1 HD externo (10TB);
- 1 rack (12U);
- cabos cat6;
- 1 Nobreak 1200VA;
- 3 filtros de linha;
- Switch L2 (24 portas);
- Wi-fi (2.4GHZ - 5GHZ) porta Gigabit Ethernet.

A estrutura proposta permite ampliação robusta para novas estações de trabalho através do switch L2 de 24 portas, contribui para a proteção dos equipamentos contra quedas rápidas de energia, surtos de tensão, picos elétricos e ruídos na rede devido à adoção do nobreak e filtros de linha. 

O acesso à rede institucional e à internet será realizado por meio da integração do switch L2 do laboratório ao switch central do prédio, utilizando as tomadas RJ-45 já existentes, respeitando a arquitetura de rede da UFS e mantendo a segurança e gestão centralizada da rede.

Desse modo, o laboraório configura-se como um ambiente de pesquisa compartilhado, escalável e sólido que atende aos objetivos do edital de implantação de condomínios de laboratórios multiusuários, além de promover um uso consciente dos recursos disponíveis e contribuir para o fortalecimento de atividades de pesquisa. 


## Documentos técnicos

[Dockerfile](Dockerfile)<br>
[Mapa lógico](Mapa_logico_lab_geppip)

## Links do site de demonstração

[Link AWS](http://44.220.130.167)
