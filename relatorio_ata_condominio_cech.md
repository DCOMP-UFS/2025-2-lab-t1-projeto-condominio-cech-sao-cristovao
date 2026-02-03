# 📋 Relatório Geral de Atas - Condomínio de Laboratórios CECH

## 1. Introdução

Este documento consolida o levantamento de equipamentos, mobiliários e insumos de rede destinados à montagem dos laboratórios de pesquisa do **Centro de Educação e Ciências Humanas (CECH)**. O objetivo é otimizar o uso do teto orçamentário através da adesão (carona) em Atas de Registro de Preços (ARP) vigentes, garantindo alta performance e conformidade jurídica junto à **UFS**.

Aqui está a sua tabela atualizada com a inclusão do notebook e os dados específicos para você preencher a sua planilha de controle.

### 2. Tabela de Itens Solicitados e Atas Identificadas

| Item Solicitado | Qtd. | ID Ata / PNCP | Responsável (Cadastro/Adesão) |
| --- | --- | --- | --- |
| **Switch 24p (UNIFESSPA)** | 07 | 18657063000180-1-000030/2024 | Miguel Lucas |
| **Switch Gerenciável (Intelbras)** | 01 | 32752798000114-1-000004/2025 | Miguel Lucas (Ata CRT-RN) |
| **Desktop Lenovo Neo 50q** | 32 | 06279103000119-1-000019/2023 | Miguel Lucas |
| **Monitor Positivo 24"** | 38 | 06279103000119-1-000019/2023 | Miguel Lucas |
| **Servidor Core i9 (64GB RAM)** | 03 | 32752798000114-1-000004/2025 | Miguel Lucas (Ata CRT-RN) |
| **Kit Teclado/Mouse (MK295)** | 39 | 32752798000114-1-000004/2025 | Miguel Lucas |
| **Notebook (IdeaPad Slim 3i)** | 02 | 32752798000114-1-000004/2025 | Miguel Lucas (Ata CRT-RN) |
| **Nobreak 3kVA (Embrapa)** | 05 | 00348003000110-1-000499/2025 | Miguel Lucas |
| **AP Wi-Fi 6 (Ruckus R350)** | 06 | 25944455000196-1-000141/2024 | Miguel Lucas |
| **Ar Condicionado 12k BTUs** |	01	| 34023077000107-1-000101/2025 | Miguel Lucas (Ata Itabaiana) |
| **Microcomputador Completo** | 12 | 13075981000188-1-000016/2024 | Kauã Nascimento |
| **Cadeiras Ergonômicas** | 13 | 13031547000104-1-000017/2025 | Kauã Nascimento |
| **HD Externo 10TB** | 03 | 00394494000136-1-000243/2025 | Kauã Nascimento |
| **Cabo Cat6 (305m)** | 02 | 10830301000104-1-000024/2025 | Kauã / José Gabriel |
| **Servidor NAS 4 Baias** | 01 | 76206465000165-1-000046/2025 | José Arthur |
| **Patch Panel 24p Cat6** | 01 | 24365710000183-1-000170/2025 | José Arthur |
| **Mesas 160x60cm** | 04 | 02030715000112-1-000211/2025 | Kauã Nascimento |
| **Rack de Parede 12U** | 01 | 10830301000104-1-000024/2025 | Kauã Nascimento |
| **Rack de Piso 19"** | 04 | 76206473000101-1-000182/2024 | José Arthur |
| **Computador I3 16GB SSD** | 12 | 13650403000128-1-000170/2024 | José Arthur |
| **Telefones IP** | 2 | 92969856000198-1-000518/2024 | José Wallas |

## 3. Detalhamento por Laboratório

### 3.1 Laboratório Balbucios (Miguel Lucas)

**Foco:** Cinema, Educação e Infância (Edição de vídeo e análise etnocartográfica).

| Item Solicitado | Qtd | Especificação Técnica Contemplada | Ata de Referência | Status |
| --- | --- | --- | --- | --- |
| **Workstation de Edição** | 4 | Desktop Lenovo Neo 50q + Monitor Positivo 24" | Ata Lenovo (06279103) | ✅ |
| **Servidores (Media/NAS/Web)** | 4¹ | Microcomputador Core i9, 64GB RAM, RTX 4060 | Ata CRT-RN (Item 07) | ✅ |
| **Switch Camada 2 / Gateway** | 1 | Switch Intelbras S2328G-A (Gerenciável) | Ata CRT-RN (Item 01) | ✅ |
| **Nobreak (UPS 3000VA)** | 1 | Nobreak Senoidal 3kVA | Ata Embrapa | ✅ |
| **Kit Periféricos** | 4 | Kit Logitech MK295 Silencioso | Ata CRT-RN (Item 06) | ✅ |
| **Cabeamento Cat 6** | - | Caixa 305m Cat6 + Patch Cords 1,5m | Ata José Gabriel / Embrapa | ✅ |

> **Nota Técnica ¹:** Os 4 servidores solicitados (Mídia, NAS e 2x Web/DB) serão consolidados via **virtualização** em uma única máquina física (Core i9 com 64GB de RAM), otimizando o espaço no rack e o consumo energético, mantendo alta performance para Docker e processamento de vídeo.

---

### 3.2 Laboratório de Salvaguarda Digital (Alícia)

**Foco:** Salvaguarda Digital, Virtualização (Docker) e Infraestrutura de Dados.

| Item Solicitado | Qtd | Especificação Técnica Contemplada | Ata de Referência | Status |
| --- | --- | --- | --- | --- |
| **Workstations** | 2 | Desktop Lenovo Neo 50q + Monitor Positivo 24" (Dual) | Ata Lenovo (06279103) | ✅ |
| **Servidores (NAS/Web)** | 2¹ | Microcomputador Core i9, 64GB RAM, RTX 4060 | Ata CRT-RN (Item 07) | ✅ |
| **Nobreak Senoidal** | 1 | Nobreak Senoidal 3kVA | Ata Embrapa | ✅ |
| **Kit Periféricos** | 2 | Kit Logitech MK295 Silencioso | Ata CRT-RN (Item 06) | ✅ |
| **Módulos SFP+ (10Gbps)** | - | Módulo Transceiver SFP+ 10Gbps | ARP UFMG (Lote Redes) | 🔍 |
| **Cabeamento Cat 6** | - | Caixa 305m Cat6 + Patch Cords 1,5m | Ata José Gabriel / Embrapa | ✅ |

> **Nota Técnica ¹:** Seguindo a estratégia de consolidação de hardware do condomínio, as funções de **NAS (VLAN 40)** e **Servidor Web/Docker** da Alícia serão executadas como instâncias virtuais de alta disponibilidade dentro do servidor físico central (Core i9), utilizando os 64GB de RAM disponíveis para garantir performance nas operações de salvaguarda.

### 3.3 Laboratório GEPPIP (Kauã Nascimento)

**Foco:** Processos Identitários e Poder (Pesquisa teórica, analítica e documental).

| Item Solicitado | Qtd | Especificação Técnica Contemplada | Ata de Referência | Status |
| --- | --- | --- | --- | --- |
| **Computadores Desktop** | 7 | Microcomputador Completo (Item 03) | 13075981000188-1-000016/2024 | ✅ |
| **Monitores 24"** | 7 | Monitor incluso no kit do microcomputador | 13075981000188-1-000016/2024 | ✅ |
| **Cadeiras Ergonômicas** | 7 | Cadeira de Escritório (Item 01) | 13031547000104-1-000017/2025 | ✅ |
| **Mesas (160x60x74cm)** | 4 | Mesa de trabalho (Ata 211/2025) | 02030715000112-1-000211/2025 | ✅ |
| **HD Externo (10TB)** | 1 | HD Externo (Item 02) | 00394494000136-1-000243/2025 | ✅ |
| **Rack (12U)** | 1 | Rack de Parede 12U (Item 07) | 10830301000104-1-000024/2025 | ✅ |
| **Nobreak 1200VA** | 1 | Nobreak 1200VA (Ata Embrapa) | 00348003000110-1-000499/2025 | ✅ |
| **Filtros de Linha** | 3 | Filtro de linha 6 tomadas | 00508903000188-1-003013/2024 | ✅ |
| **Cabeamento Cat 6** | 1 cx | Caixa de Cabo 305m Cat6 | 10830301000104-1-000024/2025 | ✅ |
| **Switch 24 portas** | 1 | Switch de 24 portas (Item 03 - UNIFESSPA) | 18657063000180-1-000030/2024 | ✅ |
| **Kits Teclado/Mouse** | 7 | Kit Logitech MK295 Silencioso (Item 06) | 32752798000114-1-000004/2025 | ✅ |
| **Wi-Fi (Dual Band)** | 1 | AP Wi-Fi 6 (Ruckus R350) | 25944455000196-1-000141/2024 | ✅ |

### 3.4 Laboratório GEPPESI (José Arthur)

**Foco:** Pesquisa em Educação, Saúde e Inclusão.

| Item Solicitado | Qtd | Especificação Técnica Contemplada | Ata de Referência | Status |
| --- | --- | --- | --- | --- |
| **Computadores Desktop** | 12 | Computador I3 16GB SSD | 13650403000128-1-000170/2024-000004 | ✅ *Ajustado* |
| **Servidores (NAS/Web)** | 1 |  Microcomputador Core i9, 64GB RAM, RTX 4060 | Ata CRT-RN (Item 07) | ✅ |
| **Switch Gerenciável** | 1 | Switch de 24 portas (Item 03 - UNIFESSPA) | 18657063000180-1-000030/2024 | ✅ |
| **Access Point Wi-Fi 6** | 1 | AP Wi-Fi 6 (Ruckus R350) | Ata UFV (Item 04) | ✅ *Ajustado* |
| **Nobreak (UPS)** | 2 | Nobreak 1200VA (Item 08) | 76206473000101-1-000182/2024 | ✅ |
| **Rack de Rede 19”** | 1 | Rack de Piso 19 pol (Item 08) | 76206473000101-1-000182/2024 | ✅ |
| **Patch Panel Cat6** | 1 | Patch Panel 24 portas Cat 6 | 24365710000183-1-000170/2025 | ✅ |
| **Cabeamento Cat 6** | - | Caixa 305m Cat6 | Ata José Gabriel | ✅ |

---

### 📝 Nota Técnica do Assistente de Atas (Miguel Lucas)

> **Parecer de Ajuste Orçamentário:** Para garantir a viabilidade financeira do GEPPESI dentro do limite de R$ 50.000,00, realizou-se um ajuste na quantidade de estações físicas de **15 para 10 unidades**.
> 1. **Justificativa:** Considerando que o laboratório utilizará o **Core i9 centralizado** (Nota Técnica ³), as 10 estações Lenovo atuarão como terminais de alto desempenho, sendo suficientes para a rotatividade dos 16 membros em grupos de pesquisa.
> 2. **Economia Gerada:** Esse ajuste economiza aproximadamente **R$ 20.750,00**, permitindo a aquisição do **NAS de 4 baias** e do **Rack de Piso**, itens fundamentais para a integridade dos dados do laboratório que antes estariam sem saldo para compra. 

### 3.5 Laboratório OBSERVAE (José Wallas)

**Foco:** Expressão Religiosa, Imagem e Som.

| Item Solicitado | Qtd | Especificação Técnica Contemplada | Ata de Referência | Status |
| --- | --- | --- | --- | --- |
| **Workstations** | 6 | Desktop Lenovo Neo 50q + Monitor 24" | Ata Lenovo (06279103) | ✅ |
| **Servidor de Rack** | 1 | Microcomputador Core i9 (Virtualizado) | Ata CRT-RN (Item 07) | ✅ |
| **Switch Core 24p PoE** | 1 | Switch Gerenciável com suporte a PoE | Ata CRT-RN / UNIFESSPA | ✅ |
| **Access Point (Wi-Fi 6)** | **1** | AP Wi-Fi 6 (Ruckus R350) | Ata UFV (Item 04) | ✅ |
| **Nobreak 3000VA** | 1 | Nobreak Senoidal 3kVA | Ata Embrapa | ✅ |
| **Rack de Piso 19"** | 1 | Rack de Piso 19 pol (Item 08) | 76206473000101-1-000182/2024 | ✅ |
| **Telefones IP** | 2 | Telefone IP (SIP) | 92969856000198-1-000518/2024 | ✅ |
| **Cabeamento Cat 6** | - | Caixa 305m Cat6 + Patch Cords 1,5m | Ata José Gabriel / Embrapa | ✅ |

---

### 📝 Nota Técnica do Assistente de Atas (Miguel Lucas)

> **Parecer Técnico:** Após análise da lista enviada pelo coordenador Wallace, o **Assistente de Atas Miguel Lucas** identificou pontos de "over-engineering" (superdimensionamento) que podem comprometer o teto orçamentário de R$ 50 mil:
> 1. **Redundância de Wi-Fi:** O pedido de 4 Access Points Ruckus R350 (totalizando quase **R$ 20.000,00**) é tecnicamente desnecessário para um ambiente de 6 estações. O sinal sofreria interferência co-canal, degradando a performance. Sugere-se a redução para **1 unidade**, que suporta com folga toda a demanda.
> 2. **Excesso de Switches:** A solicitação de 6 switches de borda para 6 computadores é ineficiente. Recomenda-se conectar as estações diretamente ao **Switch Core de 24 portas**, garantindo uma rede mais limpa, rápida e barata.
> 3. **Firewall Físico:** Appliances físicos de Firewall são caros. Sugere-se a implementação de um **Firewall Virtualizado (pfSense/OPNsense)** rodando no servidor Core i9, economizando recursos para os itens pendentes (Telefones IP).

### 3.6 Oficina de Filosofia e Neoplatonismo (Gabriel/Biel)

**Foco:** Pesquisa Filosófica, Gestão de Acervo Digital e Estudos Clássicos.

| Item Solicitado | Qtd | Especificação Técnica Contemplada | Ata de Referência | Status |
| --- | --- | --- | --- | --- |
| **Estações de Trabalho** | 2 | Desktop Lenovo Neo 50q + Monitor 24" | Ata Lenovo (06279103) | ✅ |
| **Laptop de Campo** | 1 | Notebook Lenovo/Dell (Lote 02) | Ata CRT-RN (Item 03/04) | ✅ |
| **Servidores (Rack/Mídia/BD)** | 3¹ | Microcomputador Core i9 (Virtualizado) | Ata CRT-RN (Item 07) | ✅ |
| **Switch L2 / Roteador** | 1 | Switch Intelbras S2328G-A (Gerenciável) | Ata CRT-RN (Item 01) | ✅ |
| **Nobreak 3000VA** | 1 | Nobreak Senoidal 3kVA | Ata Embrapa | ✅ |
| **Rack de Piso 19"** | 1 | Rack de Piso 19 pol (Item 08) | 76206473000101-1-000182/2024 | ✅ |
| **Cabeamento Cat 6** | - | Caixa 305m Cat6 | Ata José Gabriel | ✅ |

---

### 📝 Nota Técnica Oficina de Filosofia:

> **Parecer de Consolidação:** A solicitação de três servidores distintos (Rack, Mídia e Banco de Dados) para a Oficina de Filosofia será atendida através da **instalação de máquinas virtuais (VMs)** nos servidores centrais do condomínio. Esta abordagem garante que o banco de dados de textos clássicos e o acervo de vídeos tenham redundância e backup automatizado, sem a necessidade de gastar o orçamento com três hardwares físicos que ficariam subutilizados. O **Laptop de campo** foi selecionado da Ata do CRT-RN para garantir mobilidade em eventos e pesquisas externas.

### 3.7 Lab. Arte, Diversidade e Contemporaneidade (Luan)

**Foco:** Arte, Diversidade, IoT e Cultura Contemporânea.

| Item Solicitado | Qtd | Especificação Técnica Contemplada | Ata de Referência | Status |
| --- | --- | --- | --- | --- |
| **Desktops Pesquisadores** | 8 | Desktop Lenovo Neo 50q + Monitor 24" | Ata Lenovo (06279103) | ✅ |
| **Kits de IoT** | 10 | Kits de desenvolvimento (ESP32/Sensores) | *Necessário localizar ARP* | 🔍 |
| **Servidor de Banco de Dados** | 1 | Microcomputador Core i9 (Virtualizado) | Ata CRT-RN (Item 07) | ✅ |
| **Switch 24p PoE** | 1 | Switch Gerenciável com suporte a PoE | Ata CRT-RN / UNIFESSPA | ⚠️ |
| **Access Points (Wi-Fi 6)** | 2 | AP Wi-Fi 6 (Ruckus R350) | Ata UFV (Item 04) | ✅ |
| **Nobreak 3kVA** | 1 | Nobreak Senoidal 3kVA | Ata Embrapa | ✅ |
| **Ar Condicionado Inverter** | 1 | 12.000 BTUs Inverter | Ata Itabaiana (34023077000107-1-000101/2025) | ✅ |
| **Rack Padrão 19"** | 1 | Rack de Piso 19 pol (Item 08) | 76206473000101-1-000182/2024 | ✅ |

---

### 📝 Nota Técnica Lab. Arte e Diversidade:

> 1. **Virtualização:** Assim como nos demais laboratórios, o **Servidor de Banco de Dados** será virtualizado no cluster de Core i9, garantindo alta disponibilidade.
> 2. **Rede PoE:** Como o laboratório utilizará dispositivos de **IoT** e **Access Points**, a rede local exige alimentação via PoE (Power over Ethernet).

