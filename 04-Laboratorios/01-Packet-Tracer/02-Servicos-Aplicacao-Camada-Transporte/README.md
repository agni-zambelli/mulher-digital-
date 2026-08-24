# 🌐 Configurando Serviços de Aplicação e Testando a Comunicação na Rede

## 🎯 Objetivo

Compreender o funcionamento dos serviços de aplicação em uma rede e
observar, na prática, como ocorre a comunicação entre dispositivos
utilizando o Cisco Packet Tracer.

---

## 📚 Conceito — Camada de Transporte

A camada de transporte é responsável por oferecer comunicação entre
aplicações que estão sendo executadas em dispositivos diferentes.

Entre suas principais funções estão:

- Utilização de números de porta para identificar aplicações e serviços.
- Segmentação dos dados para transmissão.
- Controle da comunicação entre origem e destino.
- No TCP, controle de fluxo e mecanismos de confiabilidade.

Os principais protocolos associados à camada de transporte são:

- **TCP (Transmission Control Protocol)**
- **UDP (User Datagram Protocol)**

---

## 🧪 Teste de Comunicação com Ping

Durante o laboratório, foi utilizado o comando **ping** para testar a
conectividade com o servidor da rede.

O teste permite verificar se existe comunicação entre o dispositivo de
origem e o destino e se os pacotes estão conseguindo chegar ao servidor.

### ⚠️ Observação técnica

Embora o laboratório esteja relacionado ao estudo da camada de transporte,
o **ping utiliza ICMP**, e não TCP ou UDP.

Por isso, o ping é utilizado principalmente para verificar a
**conectividade entre dispositivos**, enquanto testes envolvendo portas
e serviços podem ser utilizados para analisar diretamente a comunicação
das aplicações através da camada de transporte.

---

## 🛠️ Ferramenta utilizada

- Cisco Packet Tracer

---

## 🎥 Demonstração prática

Vídeo demonstrando a realização do laboratório no Cisco Packet Tracer:

[▶️ Assistir ao laboratório](https://github.com/user-attachments/assets/967e514e-3008-4779-8aae-224e9fcdf629)

---

## 📌 O que aprendi

- A função da camada de transporte na comunicação entre aplicações.
- A utilização de portas para identificar serviços.
- A diferença entre TCP e UDP.
- A importância dos testes de conectividade em uma rede.
- A utilização do `ping` para verificar comunicação entre dispositivos.
- A diferença entre um teste de conectividade com ICMP e a comunicação
  realizada por TCP ou UDP.

---

## 🚀 Próximos passos

Continuar praticando protocolos e serviços de rede no Cisco Packet Tracer,
aprofundando os conhecimentos sobre comunicação entre dispositivos,
portas, protocolos e troubleshooting.

---

### 🏷️ Tecnologias e conceitos

`Cisco Packet Tracer` `TCP` `UDP` `ICMP` `Ping` `Portas` `Redes`  
