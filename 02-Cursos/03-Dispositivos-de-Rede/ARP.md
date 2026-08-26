# Protocolo ARP (Address Resolution Protocol)

O **ARP** é um protocolo do conjunto TCP/IP utilizado para mapear endereços **IPv4 (Camada 3)** em endereços **MAC físicos (Camada 2)**.

O **ARP** tem duas funções principais: 
- manter uma tabela de mapeamentos de endereços IPv4 para MAC e
- determinar os endereços MAC de endereços IPv4 conhecidos.
  
### Como Funciona:
1. **Solicitação ARP:** Quando um dispositivo precisa enviar dados na rede local (LAN), ele faz um envio em *broadcast* perguntando qual MAC pertence ao IP de destino.
2. **Resposta ARP:** O dispositivo dono do IP responde diretamente (*unicast*) informando seu endereço MAC.
3. **Cache ARP:** As informações obtidas são salvas temporariamente na memória RAM de cada dispositivo (Cache ARP), otimizando o tráfego e evitando consultas repetidas.

---
[Acessar conteúdo no NetAcad](https://www.netacad.com/pt/launch?id=952d8553-2bca-40d5-b00f-b5474df91ef0&tab=curriculum&view=68f59559-9312-5667-bde3-67b3d1a96f0e)
