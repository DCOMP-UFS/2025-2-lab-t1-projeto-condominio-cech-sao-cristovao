# Identificação do Projeto de Redes

## Responsável Técnico
**José Wallas Cruz da Silva**

## 1. Resumo Descritivo
Este projeto define a infraestrutura de rede para o **OBSERVAE (Grupo de Pesquisa OBSERVAE)**.

O projeto tem como missão realizar o primeiro mapeamento digital da liturgia em Sergipe, catalogando as transmissões de 50 comunidades religiosas para compor um banco de dados inédito de teologia pública.

O objetivo central é investigar a correlação entre a qualidade da transmissão (latência, resolução, nitidez de áudio) e a manutenção da atenção devocional (experiência de fé).

Para viabilizar essa análise em um cenário de Big Data, a proposta utiliza infraestrutura de alto desempenho para aplicar algoritmos de Inteligência Artificial (Visão Computacional e NLP). Isso permite mensurar estatisticamente como as limitações técnicas impactam a retenção dos fiéis e a recepção da mensagem teológica.

---

## 2. Relação de Hardware e Insumos (Bill of Materials)
Abaixo estão listados os equipamentos adquiridos via Atas de Registro de Preços (ARP) para compor a infraestrutura física do laboratório:

| Item | Qtd. | Especificação / Função no Projeto |
| :--- | :---: | :--- |
| **Rack de Piso 19"** | 01 | Gabinete fechado de alta capacidade para acomodar o Servidor e o Nobreak. |
| **Servidor (Host de Virtualização)** | 01 | Workstation de alto desempenho (Core i9, 64GB RAM) para rodar VMs de Firewall, Banco de Dados e Docker. |
| **Switch Core 24p PoE** | 01 | Switch Gerenciável com tecnologia *Power over Ethernet* para alimentar antenas e telefones sem fontes extras. |
| **Nobreak Senoidal 3000VA** | 01 | Proteção elétrica robusta para sustentar o Rack de Piso. |
| **Workstations (Estações)** | 06 | Desktops Lenovo Neo 50q para os pesquisadores do laboratório. |
| **Access Point Wi-Fi 6** | 01 | Ponto de acesso de alta densidade (Ruckus) para conectividade móvel no laboratório. |
| **Telefones IP (SIP)** | 02 | Terminais para comunicação interna via VoIP, alimentados via PoE. |
| **Cabeamento Estruturado** | - | Cabos UTP Cat6 e Patch Cords certificados para garantir tráfego Gigabit. |

---

## 3. Demonstração do Projeto
O portal do projeto foi implantado utilizando uma instância EC2 na AWS.

* **Acesse o site ao vivo:** http://54.242.172.75