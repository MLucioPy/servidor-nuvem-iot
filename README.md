# Sistema Supervisório IoT - Câmara Fria Industrial ❄️

Projeto desenvolvido para a disciplina de **Plataformas de Prototipação para Internet das Coisas** do curso de Pós-graduação em IoT.

**Professor:** Marcos Aparecido Chaves Ferreira  
**Aluno:** Moisés  

## 📋 Sobre o Projeto
Este repositório contém a documentação, fluxos e códigos de um sistema completo de monitoramento e controle bidirecional para uma câmara fria, utilizando arquitetura de nuvem (Servidor, Apache, Node-RED). O sistema foca em padrões da Indústria 4.0, implementando painéis SCADA e banco de dados relacional.

## 🛠️ Tecnologias e Arquitetura
* **Hardware:** ESP32, Sensores de Temperatura/Umidade
* **Servidor em Nuvem:** AWS (Amazon Web Services), Apache
* **Protocolo de Comunicação:** MQTT (QoS 1)
* **Backend & Interface SCADA:** Node-RED (Dashboard 2.0)
* **Banco de Dados:** MySQL (com técnica de *Report by Exception* para otimização de gráficos)

## 📁 Estrutura do Repositório
* `/node-red`: Arquivos JSON com os fluxos exportados do servidor.
* `/esp32`: Código-fonte em C++ para o microcontrolador (em breve).
* `/docs`: Imagens do dashboard, diagramas e prints do banco de dados.

## 🚀 Funcionalidades Implementadas
- [x] Monitoramento em tempo real de Temperatura e Umidade.
- [x] Gráficos históricos imunes a dados corrompidos.
- [x] Controle remoto bidirecional do ventilador via MQTT.
- [x] Ajuste de Set-Point variável via interface web.
- [x] Interface de navegação multi-páginas (Home, Indicações, Histórico).
