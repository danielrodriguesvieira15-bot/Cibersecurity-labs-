LAB 01 — Investigação de Conexões no Windows

Área: Segurança Defensiva
Formação: Cibersegurança
Objetivo: SOC Analyst Júnior

1. Objetivo

Investigar conexões de rede utilizando ferramentas nativas do Windows.

2. Ferramentas utilizadas

* Windows PowerShell
* ipconfig
* netstat
* tasklist

3. Atividades realizadas

Identificação do IP

Comando: ipconfig

Resultado: IPv4 identificado com sucesso.

Investigação de conexões

Comando: netstat -ano

Resultado: Identificadas diversas entradas TCP e UDP.

Identificação de processo

PID identificado: 1344.

Comando: tasklist /FI "PID eq 1344"

Resultado: Aguardando confirmação do nome do processo.

4. Conhecimentos adquiridos

* Identificação de IPv4.
* Protocolos TCP e UDP.
* Investigação de conexões.
* Identificação de PID.
* Fundamentos de análise de processos.

5. Conclusão

O laboratório proporcionou uma primeira experiência prática com ferramentas de investigação de rede do Windows, desenvolvendo conhecimentos fundamentais para atividades de análise e monitoramento de segurança.

6. Próximas atividades

* Confirmar o processo associado ao PID 1344.
* Adicionar evidências visuais.
* Aprofundar a análise de conexões.
