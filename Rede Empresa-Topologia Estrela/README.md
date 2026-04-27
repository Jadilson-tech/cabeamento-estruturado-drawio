# Projeto de Cabeamento Estruturado - Ambiente Corporativo

Este projeto apresenta a infraestrutura de rede para uma empresa composta por cinco salas, com foco em alta disponibilidade, segurança e conformidade com as normas **ANSI/TIA/EIA**.

---

## 📊 Topologia da Rede
A topologia adotada é a **Estrela Hierárquica**, onde todos os dispositivos são conectados a um ponto central.

### Vantagens:
* **Facilidade de manutenção:** Falhas são isoladas rapidamente.
* **Desempenho:** Melhor tráfego de dados.
* **Escalabilidade:** Expansão sem grandes alterações estruturais.

---

## 🛠️ Subsistemas do Cabeamento

### 1. Área de Trabalho (Work Area)
Atendimento a 5 salas, cada uma configurada com:
* 5 Computadores por sala (Total de 25 pontos).
* 1 Access Point por sala (Conectividade Wi-Fi 6).
* Periféricos: Impressoras multifuncionais, Telefonia IP e Câmeras IP.
* **Cabo:** UTP Categoria 6 (Cat6) para taxas de até 1 Gbps.

### 2. Cabeamento Horizontal
Responsável pela interligação entre as salas e a Sala de Telecomunicações (TR).
* Utilização de **Patch Panels** de 48 portas.
* Distância máxima de 90 metros conforme normas técnicas.

### 3. Salas Técnicas (ER e TR)
* **Sala de Equipamentos (ER):** Abriga o Switch Core (Camada 3), Servidores de Arquivo/Backup, Firewall de borda e No-break (UPS).
* **Sala de Telecomunicações (TR):** Concentra os cabos das áreas de trabalho e conecta-se ao Backbone.
* **Backbone:** Interligação via **Fibra Óptica Multimodo** para garantir imunidade a ruídos e alta velocidade.

---

## 📋 Lista de Materiais (BOM)

| Item | Especificação | Quantidade |
| :--- | :--- | :--- |
| Cabo UTP | Cat6 (Caixas de 305m) | 4 Caixas |
| Fibra Óptica | Multimodo OM3 | 50 Metros |
| Switch Core | Gerenciável Camada 3 | 1 Unidade |
| Switch Acesso | 48 Portas PoE (Camada 2) | 1 Unidade |
| Firewall | Hardware Dedicado | 1 Unidade |
| No-break | UPS 3kVA | 1 Unidade |

---

## 🔒 Planejamento Lógico e Segurança

### Segmentação de VLANs:
* **VLAN 10:** Dados (Estações de Trabalho).
* **VLAN 20:** Voz (Telefonia IP).
* **VLAN 30:** Wi-Fi (Visitantes e Dispositivos Móveis).
* **VLAN 40:** CFTV (Câmeras de Segurança).

### Acesso Seguro:
* **VPN (Rede Privada Virtual):** Implementada para permitir acesso remoto seguro para funcionários externos com autenticação criptografada.

---

## 🧪 Testes e Certificação
Para garantir a qualidade da rede, todos os enlaces passam por:
1. **Certificação:** Uso de certificador (ex: Fluke) para testes de NEXT e atenuação.
2. **Identificação:** Etiquetagem completa de cabos, tomadas e portas seguindo padrão de administração.

---

## 📂 Arquivos do Projeto
* [/src](./src): Contém o arquivo original do **Draw.io** para edição.
* [/img](./img): Diagramas exportados em PNG.
* [/docs](./docs): Relatório técnico em PDF.

---
**Desenvolvido por:** [Jadilson José Tavares]
