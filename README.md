# SOC & Blue Team Lab

Projeto pessoal criado para colocar em prática conceitos de **Segurança da Informação**, principalmente nas áreas de SOC e Blue Team.

A ideia é montar um laboratório do zero, gerar alguns cenários de segurança e acompanhar o que acontece desde a geração do evento até sua identificação e investigação.

## O que quero praticar

Neste laboratório, vou trabalhar principalmente com:

* Monitoramento de máquinas Windows;
* Coleta e análise de logs;
* Identificação de atividades suspeitas;
* Criação e teste de regras de detecção;
* Investigação de alertas;
* Análise de evidências;
* Uso do MITRE ATT&CK para entender as técnicas utilizadas.

## Tecnologias

* Windows
* Linux / Kali Linux
* Wazuh
* Sysmon
* GitHub
* MITRE ATT&CK

## Como o laboratório funciona

A ideia é ter uma máquina Windows sendo monitorada e um servidor responsável por receber e analisar os eventos.

```text
Windows
   │
   │ Eventos
   ▼
 Sysmon
   │
   ▼
 Wazuh
   │
   ▼
Alertas
   │
   ▼
Investigação
   │
   ▼
Evidências
```

Conforme o projeto avançar, vou documentar a configuração do ambiente, os testes realizados, os alertas encontrados e como cada situação foi investigada.

## Cenários que serão testados

O laboratório será utilizado para simular situações controladas, como:

* Execução de processos;
* Tentativas de autenticação;
* Alterações no sistema;
* Atividades relacionadas à rede;
* Comportamentos que possam gerar alertas;
* Investigação de eventos suspeitos.

Todos os testes serão realizados dentro do próprio ambiente de laboratório.

## Estrutura do projeto

A estrutura do repositório será organizada conforme novos testes e etapas forem adicionados.

## Por que estou fazendo este projeto?

Quero sair um pouco da parte apenas teórica e ganhar mais prática com ferramentas e processos utilizados no dia a dia de segurança.

Este laboratório também faz parte do meu portfólio enquanto estudante de **Segurança da Informação**, com foco em:

**SOC | Blue Team | Monitoramento | Detecção | Incident Response**

---

**Status:** 🟡 Em desenvolvimento
