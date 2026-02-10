# Proposta de Implantação: Condomínio de Laboratórios Multiusuários - CECH (UFS)

Este repositório centraliza a documentação técnica, o planejamento de infraestrutura e o detalhamento orçamentário para a criação do **Condomínio de Laboratórios do Centro de Educação e Ciências Humanas (CECH)** da Universidade Federal de Sergipe. A proposta é submetida em conformidade com o **Edital 01/2026**.

## 1. Visão Geral e Governança

O projeto visa a integração de 07 grupos de pesquisa do CECH em uma estrutura tecnológica unificada. A estratégia central baseia-se na **Arquitetura de Virtualização de Alta Densidade**, onde recursos de processamento e armazenamento são compartilhados via um CPD (Centro de Processamento de Dados) único, otimizando o teto orçamentário de R$ 350.000,00.

### 👥 Equipe de Gestão (Funções Obrigatórias)

* **Assistente de Atas de Registro de Compras:** Miguel Lucas Santana Freire
* **Contador/Tesoureiro:** Kauã Nascimento Santos
* **Coordenador da Submissão:** José Wallas Cruz da Silva

---

## 2. Roteiro de Documentação (Indexação do Projeto)

Para fins de auditoria e análise técnica pela comissão avaliadora, o projeto está estruturado nos seguintes arquivos:

* **[Relatório de Atas Vigentes](./relatorio_ata_condominio_cech.md)**: Detalhamento técnico dos itens selecionados, IDs do PNCP e notas técnicas de ajuste por laboratório.
* **[Plano de Uso Multiusuário](./plano_uso_multiusuario.md)**: Regras de governança, agendamento de recursos e protocolos de compartilhamento da infraestrutura.
* **[Relatório de Colaboração](./relatorio_colaboracao_cech.md)**: Registro quantitativo de interações no GoogleGroups para validação do engajamento dos membros.
* **[Orçamento e Topologia](./Condomínio_lab_CECH.pdf)**: Documento consolidado contendo a planilha de custos e o mapa físico da rede.

---

## 3. Laboratórios Integrantes e Infraestrutura Digital

Abaixo, a relação dos laboratórios que compõem o condomínio, seus respectivos técnicos responsáveis e os endereços para validação das instâncias AWS:

| Laboratório | Técnico Responsável (GitHub) | Repositório Oficial | IP de Validação (AWS) |
| --- | --- | --- | --- |
| **Balbucios: gaguejar uma infância** | [Miguells10](https://github.com/Miguells10) | [Link Repo](https://github.com/DCOMP-UFS/2025-2-lab-t1-projeto-lab-site-Miguells10) | `(http://18.212.0.203/)` |
| **GEPPIP (Processos Identitários e Poder)** | [Matagim](https://github.com/Matagim) | [Link Repo](https://github.com/DCOMP-UFS/2025-2-lab-t1-projeto-lab-site-Matagim) | `(http://50.19.48.165/)` |
| **GEPPESI (Educação, Saúde e Inclusão)** | [joarrhur-dcomp](https://github.com/joarrhur-dcomp) | [Link Repo](https://github.com/DCOMP-UFS/2025-2-lab-t1-projeto-lab-site-joarrhur-dcomp) | `(http://50.19.173.1:8080/)` |
| **Arte, Diversidade e Contemporaneidade** | [luanprata-tech](https://github.com/luanprata-tech) | [Link Repo](https://github.com/DCOMP-UFS/2025-2-lab-t1-projeto-lab-site-luanprata-tech.git) | `(http://54.196.223.137:8080/)` |
| **Oficina de Filosofia Medieval e Neoplatonismo** | [gbasttos](https://github.com/gbasttos) | [Link Repo](https://github.com/DCOMP-UFS/2025-2-lab-t1-projeto-lab-site-gbasttos) | `[http://54.83.117.20]` |
| **OBSERVAE (Expressão Religiosa, Imagem e Som)** |[wallassilva](https://github.com/wallassilva) | [Link Repo](https://github.com/DCOMP-UFS/2025-2-lab-t1-projeto-lab-site-wallassilva)| '(http://50.19.19.110:8080/)'|
| **Escrevivências de Mulheres Negras em Diáspora** | [aliciasnts](https://github.com/aliciasnts) | [Link Repo](https://github.com/DCOMP-UFS/2025-2-lab-t1-projeto-lab-site-aliciasnts) | http://3.234.214.192/ |
---

## 4. Justificativa de Infraestrutura Compartilhada

A viabilidade do projeto sustenta-se na centralização de serviços críticos em um cluster de virtualização:

1. **Processamento:** Cluster de servidores Core i9 operando instâncias Docker para hospedagem de aplicações e bancos de dados.
2. **Segurança:** Implementação de Firewall/Gateway unificado e segmentação de rede por VLANs via Switch Gerenciável.
3. **Armazenamento:** Sistema NAS de 4 baias para salvaguarda digital e redundância de dados de todos os grupos participantes.

