# Sistema Supervisório IoT - Câmara Fria Industrial ❄️

Projeto desenvolvido para a disciplina de **Plataformas de Prototipação para Internet das Coisas** do curso de Pós-graduação em IoT.

**Professor:** Marcos Aparecido Chaves Ferreira  
**Aluno:** Moisés Moreira

---

# 📋 Sobre o Projeto
Este repositório contém a documentação, fluxos e códigos de um sistema completo de **monitoramento e controle bidirecional para uma câmara fria**, utilizando arquitetura em nuvem com servidor Linux, servidor web e plataforma de automação.

O sistema foi desenvolvido seguindo conceitos de **Indústria 4.0**, integrando dispositivos IoT, comunicação MQTT, armazenamento em banco de dados e uma interface supervisória SCADA acessível via navegador.

---

# 🌐 Acesso ao Sistema

## Fluxo do Node-RED
Interface administrativa da plataforma Node-RED:

https://gaf-iot.duckdns.org/

---

## Dashboard Supervisório
Interface gráfica para monitoramento e controle do sistema:

https://gaf-iot.duckdns.org/dashboard/home

O dashboard foi desenvolvido utilizando **Node-RED Dashboard 2.0**, permitindo acesso remoto através de navegador web.

---

# 🛠️ Tecnologias e Arquitetura

### Hardware
- ESP32
- Sensores de Temperatura e Umidade

### Servidor em Nuvem
- AWS (Amazon Web Services)
- Apache Web Server

### Comunicação
- Protocolo MQTT (QoS 1)

### Backend e Interface SCADA
- Node-RED
- Dashboard 2.0

### Banco de Dados
- MySQL

Implementado utilizando a técnica **Report by Exception**, que otimiza o armazenamento e melhora a visualização de gráficos históricos.

---

# 📁 Estrutura do Repositório

/node-red  
Arquivos JSON contendo os fluxos exportados do Node-RED.

---

/esp32  
Código fonte em C++ para o microcontrolador ESP32.

---

/docs  
Imagens do dashboard, diagramas da arquitetura e prints do banco de dados.

---

# 🚀 Funcionalidades Implementadas

- Monitoramento em tempo real de **Temperatura e Umidade**
- Gráficos históricos protegidos contra **dados corrompidos**
- Controle remoto **bidirecional do ventilador via MQTT**
- Ajuste remoto de **Set-Point de temperatura**
- Interface SCADA com **navegação multi-páginas**
- Sistema hospedado em **servidor em nuvem**

---

# 📊 Interface do Sistema

O dashboard supervisório permite:

- Visualizar temperatura e umidade em tempo real
- Controlar o ventilador da câmara fria
- Ajustar set-point de temperatura
- Consultar histórico de dados em gráficos

Tudo acessível através de navegador web.

---

# 📚 Objetivo Acadêmico

Este projeto tem como objetivo demonstrar a aplicação prática de conceitos de **Internet das Coisas (IoT)**, **computação em nuvem** e **sistemas supervisórios industriais**, integrando dispositivos físicos com plataformas de software para monitoramento e controle remoto.
