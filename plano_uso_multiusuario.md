# Plano de Uso Multiusuário e Governança

Este plano define as regras de acesso, agendamento e manutenção do **Condomínio de Laboratórios do CECH**, garantindo o caráter multiusuário exigido pela **FINEP/UFS**.

## 1. Comitê Gestor

O condomínio será gerido por um comitê rotativo composto por:
*   **1 Coordenador Geral** (Docente)
*   **1 Responsável Técnico** (TI)
*   **1 Representante Discente** (Pós-Graduação)

**Mandato:** 12 meses, permitida uma recondução.

## 2. Regras de Acesso à Infraestrutura

### 2.1. Acesso Físico
*   As salas funcionarão das **08:00 às 22:00**, de segunda a sexta-feira.
*   O acesso fora do horário comercial deve ser solicitado com **48h de antecedência** via formulário.

### 2.2. Acesso aos Recursos Computacionais (Cluster)
*   Cada grupo de pesquisa terá uma **Quota de Recursos** (CPU/RAM) garantida no cluster Docker.
*   Recursos ociosos poderão ser alocados dinamicamente para "Jobs" pesados (ex: renderização de vídeo) mediante agendamento na fila de processamento.

## 3. Política de Segurança e Backup

1.  **Backup 3-2-1:**
    *   Cópia local no SSD do servidor.
    *   Cópia diária no **NAS Central (40TB)**.
    *   Cópia semanal desconectada (Cold Storage/Nuvem).
2.  **Rede:**
    *   Uso obrigatório de **VPN** para acesso remoto às ferramentas de gestão.
    *   Segmentação de tráfego por VLANs (Pesquisa, Visitante, Adm).

## 4. Agendamento

O agendamento de uso exclusivo de equipamentos específicos (ex: Câmeras, Kits IoT) será feito via **Google Calendar** compartilhado do condomínio.

