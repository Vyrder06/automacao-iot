# Automação Industrial & IIoT — Projeto de Portfólio

Projeto pessoal para unir minha formação em Engenharia de Controle e Automação com programação, construindo um pipeline completo de dados industriais: de um CLP simulado até um dashboard de monitoramento na nuvem.

## Sobre o projeto

A ideia nasceu de uma pergunta simples: como um sensor de fábrica vira uma informação útil na tela de alguém? Este repositório documenta minha resposta prática pra isso, construída passo a passo enquanto estudo.

Minha experiência como Aprendiz em Manutenção Elétrica Industrial (leitura de diagramas, diagnóstico de falhas em painéis e componentes) deu a base do lado "OT" (Operational Technology). Este projeto é onde estou construindo o lado "IT" por cima disso — Python, banco de dados, nuvem e visualização — pra formar o perfil híbrido que estou buscando: automação com dados.

## Pipeline do projeto
CLP simulado → Python (Modbus) → Nuvem (MQTT) → Banco de dados → Dashboard (Power BI)

Cada seta acima é uma fase do projeto, construída e documentada de forma incremental.

## Progresso
- [] Fase 1 — Simulador de sensores em Python + banco de dados (SQLite/PostgreSQL)
 
- [] Fase 2 — Leitura via protocolo Modbus (pymodbus) de um CLP simulado
 
- [] Fase 3 — Envio dos dados via MQTT para a nuvem (AWS IoT Core / Azure IoT Hub)
 
- [] Fase 4 — Dashboard no Power BI com alertas em tempo real
 
- [] Fase 5 — Consolidação final do pipeline completo

## Tecnologias
Camada	Ferramenta
Linguagem	Python
Protocolo industrial	Modbus (pymodbus)
Banco de dados	SQLite / PostgreSQL
Mensageria / Nuvem	MQTT, AWS IoT Core ou Azure IoT Hub
Visualização	Power BI
Versionamento	Git / GitHub
Estrutura do repositório
├── fase1_simulador/     # geração de dados simulados + gravação no banco
├── fase2_modbus/        # leitura via protocolo Modbus
├── fase3_nuvem/         # envio de dados via MQTT para a nuvem
├── fase4_dashboard/     # conexão e configuração do Power BI
└── docs/                # anotações e documentação de apoio

## Status

🚧 Em desenvolvimento — atualizando conforme avanço no meu roteiro de estudos.

## Autor

João Souza — Estudante de Engenharia de Controle e Automação LinkedIn · GitHub
