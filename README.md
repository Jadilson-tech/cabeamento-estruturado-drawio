# 🧠 Projeto de Cabeamento Estruturado – Pequena Empresa

> 📌 Implementação de infraestrutura de rede estruturada com foco em organização, desempenho e escalabilidade.

---

## 📖 Introdução

Este projeto apresenta a implementação de uma rede de cabeamento estruturado para uma empresa de pequeno porte, contemplando:

* 🖥️ Duas salas de informática (6 computadores cada)
* 🏢 Áreas administrativas
* ☕ Área de convivência

🎯 **Objetivo:** Garantir organização, desempenho, escalabilidade e padronização da rede.

---

## 🏗️ Estrutura Física da Rede

Ambientes planejados:

* 🚪 Entrada de Facilidades
* 🖥️ Sala de Equipamentos
* 🔌 Sala de Telecomunicações
* 💻 Sala de Informática 1
* 💻 Sala de Informática 2
* ☕ Sala de Reuniões e Alimentação
* 🚻 WC

---

## 🌐 Entrada de Facilidades

📡 Recebimento do link de internet via **fibra óptica (ISP)**

**Componentes:**

* 📦 Caixa de Terminação Óptica (CTO)
* 🔄 ONU/ONT (Fibra → Ethernet)

➡️ Conversão para cabo de rede e envio ao roteador.

---

## 🖥️ Sala de Equipamentos

**Dispositivos:**

* 🌐 Roteador
* 🔥 Firewall
* 🔀 Switch (24 portas)
* 🗄️ Servidor

### 🔁 Fluxo da rede:

```bash
ONU → Roteador → Firewall → Switch → Servidor
```

### 🔌 Cabeamento:

* Tipo: UTP Cat6
* Cor: 🔴 Vermelho
* Uso: conexões internas (patch cords)

---

## 🔗 Backbone (Vertical)

Interligação entre salas principais:

* Tipo: Fibra Óptica
* Cor: 🟡 Amarelo
* Espessura: Grossa

🚀 Alta velocidade + baixa interferência

---

## 🧩 Sala de Telecomunicações

Equipamentos:

* 🔀 Switch secundário
* 🧱 Patch Panel

📌 Responsável por distribuir o cabeamento horizontal.

---

## 🔌 Cabeamento Horizontal

* Tipo: UTP Cat6
* Cor: 🔴 Vermelho
* Conexão dedicada por ponto

✔️ Melhor desempenho
✔️ Organização
✔️ Sem compartilhamento indevido

---

## 💻 Área de Trabalho

Cada sala contém:

* 🖥️ 6 computadores
* 🔌 Tomadas RJ45 duplas

📌 Cada ponto possui:

* 2 portas
* 2 cabos independentes

📈 Preparado para expansão futura

---

## 📡 Rede Wireless

📍 Local: Sala de reuniões

* 📶 Access Point
* 🔌 Ligado ao switch
* 📡 Wi-Fi para dispositivos móveis

💡 Suporte opcional: **PoE**

---

## 🎨 Padronização de Cores

| Cor         | Função         |
| ----------- | -------------- |
| 🔵 Azul     | Internet (ISP) |
| 🟡 Amarelo  | Backbone       |
| 🔴 Vermelho | Rede interna   |

---

## ✅ Conclusão

Este projeto garante:

✔️ Organização da rede
✔️ Facilidade de manutenção
✔️ Escalabilidade
✔️ Alto desempenho

🚀 Infraestrutura moderna baseada em **Cat6 + Fibra Óptica**

---

## 📂 Arquivos do Projeto

* 📄 Projeto em PDF
* 🖼️ Diagrama em PNG
* 🧩 Arquivo editável (.drawio)

---

