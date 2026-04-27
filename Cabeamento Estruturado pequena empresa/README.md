# RELATÓRIO DE PROJETO DE CABEAMENTO ESTRUTURADO – PEQUENA EMPRESA

1. Introdução
Este projeto apresenta a implementação de uma rede de cabeamento estruturado para uma empresa de pequeno porte, contemplando duas salas de informática com seis com-putadores cada, além de áreas administrativas e de convivência. O objetivo é garantir organização, desempenho, escalabilidade e padronização da infraestrutura de rede.

2. Estrutura Física da Rede
A empresa foi dividida nos seguintes ambientes:
•	Entrada de Facilidades
•	Sala de Equipamentos
•	Sala de Telecomunicações
•	Sala de Informática 1
•	Sala de Informática 2
•	Sala de Reuniões e Alimentação
•	WC
Cada ambiente foi planejado de forma a atender às necessidades de conectividade e or-ganização do cabeamento estruturado.

3. Entrada de Facilidades
Neste ambiente ocorre a chegada do link de internet proveniente da operadora, utili-zando fibra óptica (Link ISP). Os seguintes componentes foram utilizados:
•	Caixa de Terminação Óptica (CTO)
•	ONU/ONT (conversor de fibra óptica para Ethernet)
A partir da ONU, o sinal é convertido para cabo metálico (Ethernet) e encaminhado ao roteador.

4. Sala de Equipamentos
A Sala de Equipamentos centraliza os principais dispositivos da rede:
Roteador
Firewall
Switch principal (Layer 2 – 24 portas)
Servidor
O fluxo de conexão segue a seguinte ordem:
ONU → Roteador → Firewall → Switch → Servidor
O cabeamento utilizado neste ambiente é do tipo UTP Cat6, representado na cor verme-lha, com espessura fina, caracterizando conexões internas (patch cords).

5. Cabeamento Backbone (Vertical)
O backbone interliga a Sala de Equipamentos à Sala de Telecomunicações.
Tipo: Fibra Óptica
Cor: Amarelo
Espessura: Grossa
Esse enlace é responsável por transportar grandes volumes de dados com alta veloci-dade e baixa interferência, sendo essencial para a comunicação entre os pontos centrais da rede.

6. Sala de Telecomunicações
Neste ambiente foram instalados:
Switch secundário (Layer 2)
Patch Panel
O switch recebe o backbone e distribui o sinal para o patch panel, que organiza as cone-xões do cabeamento horizontal.

7. Cabeamento Horizontal
O cabeamento horizontal conecta a Sala de Telecomunicações às áreas de trabalho.
Tipo: UTP Cat6
Cor: Vermelho
Espessura: Fina
Cada ponto de rede possui cabeamento dedicado, garantindo melhor desempenho e evi-tando compartilhamento indevido de conexão.

8. Área de Trabalho (Salas de Informática)
Cada sala de informática possui:
6 computadores
Tomadas RJ45 duplas distribuídas estrategicamente
Foram utilizadas tomadas com duas portas RJ45, permitindo conectar dois dispositivos por ponto. Cada porta possui um cabo exclusivo até o patch panel, totalizando dois ca-bos por tomada.
Também foram previstos pontos adicionais para expansão futura.

9. Rede Wireless (Access Point)
Foi implementado um Access Point na sala de reuniões e alimentação, com o objetivo de fornecer acesso Wi-Fi para dispositivos móveis, como notebooks e smartphones.
Conexão: UTP Cat6
Ligação: Switch da Sala de Telecomunicações
Função: Disponibilizar rede sem fio restrita à área comum
Opcionalmente, o equipamento pode operar com tecnologia PoE (Power over Ethernet).

10. Padronização de Cores
Para facilitar a identificação dos tipos de conexão, foi adotado o seguinte padrão:

Azul: Link de Internet (ISP)
Amarelo: Backbone (Fibra Óptica)
Vermelho: Cabeamento interno (UTP Cat6)
Essa padronização contribui para organização, manutenção e identificação rápida da re-de.

11. Conclusão
O projeto atende aos princípios do cabeamento estruturado, proporcionando:
Organização física e lógica da rede
Facilidade de manutenção
Escalabilidade para expansão futura
Alto desempenho e confiabilidade
A utilização de padrões como Cat6, backbone em fibra óptica e segmentação por ambi-entes garante uma infraestrutura moderna e adequada para uma pequena empresa.
