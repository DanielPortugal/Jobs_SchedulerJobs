# ⏳ Oracle SQL Scripts – Jobs & Scheduler

[![Oracle](https://img.shields.io/badge/Oracle-DB-F80000?logo=oracle&logoColor=white)](https://www.oracle.com/database/)  
📖 Coleção de **scripts SQL para gerenciamento de Jobs e Oracle Scheduler**. Inclui consultas, exemplos de criação e manutenção de jobs no Oracle Database.  

---

## 📑 Sumário

- [🗑️ apagar_job.sql](#-apagar_jobsql)
- [📜 consultar_jobs_antigos.sql](#-consultar_jobs_antigossql)
- [🔎 consultar_scheduler_jobs.sql](#-consultar_scheduler_jobssql)
- [🌐 correcao_timezone_schedulejobs.sql](#-correcao_timezone_schedulejobssql)
- [▶️ executar_schedule_job.sql](#-executar_schedule_jobsql)
- [📥 exemplo_criar_job_baseado_evento.sql](#-exemplo_criar_job_baseado_eventosql)
- [⛓️ exemplo_criar_job_chains.sql](#-exemplo_criar_job_chainssql)
- [📅 exemplo_criar_job_com_schedule_program.sql](#-exemplo_criar_job_com_schedule_programsql)
- [📂 exemplo_criar_job_externo.sql](#-exemplo_criar_job_externosql)
- [📧 exemplo_criar_job_notificacao_email.sql](#-exemplo_criar_job_notificacao_emailsql)
- [⏱️ exemplo_criar_job_simples_baseado_tempo.sql](#-exemplo_criar_job_simples_baseado_temposql)
- [🔐 gerenciar_privilegios_scheduler.sql](#-gerenciar_privilegios_schedulersql)
- [♻️ reativar_job_quebrado.sql](#-reativar_job_quebradosql)

---

## 🗑️ apagar_job.sql
Remove um **job agendado** do Oracle Scheduler.  

---

## 📜 consultar_jobs_antigos.sql
Lista os **jobs antigos** armazenados no banco de dados, incluindo:  
- Data de criação.  
- Última execução.  
- Status atual.  

---

## 🔎 consultar_scheduler_jobs.sql
Consulta todos os **jobs configurados no Oracle Scheduler**, com informações sobre:  
- Programação.  
- Estado.  
- Próxima execução.  

---

## 🌐 correcao_timezone_schedulejobs.sql
Ajusta o **timezone** de jobs no Scheduler após alterações no banco ou no sistema operacional.  

---

## ▶️ executar_schedule_job.sql
Executa manualmente um **job agendado**, sem alterar sua programação original.  

---

## 📥 exemplo_criar_job_baseado_evento.sql
Cria um job **baseado em eventos**, executado quando uma condição específica ocorre no banco.  

---

## ⛓️ exemplo_criar_job_chains.sql
Exemplo de criação de **job chains**:  
- Permite encadear múltiplas tarefas com dependências e condições.  

---

## 📅 exemplo_criar_job_com_schedule_program.sql
Exemplo para criar um job utilizando um **program** e **schedule** predefinidos no Scheduler.  

---

## 📂 exemplo_criar_job_externo.sql
Criação de um job para executar **scripts externos** (fora do banco), como shell scripts ou batch files.  

---

## 📧 exemplo_criar_job_notificacao_email.sql
Exemplo de job que **envia e-mails** de notificação após a execução.  

---

## ⏱️ exemplo_criar_job_simples_baseado_tempo.sql
Exemplo básico para criar um **job baseado em tempo** com agendamento periódico.  

---

## 🔐 gerenciar_privilegios_scheduler.sql
Scripts para **conceder ou revogar privilégios** relacionados ao Oracle Scheduler (ex.: criar, gerenciar ou executar jobs).  

---

## ♻️ reativar_job_quebrado.sql
Reativa um **job quebrado** ou desabilitado no Scheduler, restaurando sua execução automática.  

---

## 🚀 Como usar
📂 Execute os scripts diretamente no **SQL*Plus**, SQLcl, SQL Developer ou qualquer outra ferramenta compatível com Oracle.  

---

## 🛠️ Requisitos
- Oracle Database 11g ou superior.  
- Acesso com privilégios para gerenciamento de jobs (`DBMS_SCHEDULER`).  

---

## 🤝 Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir um **Pull Request** ou relatar problemas via **Issues**.  

---

## 📄 Licença
Este projeto está licenciado sob a [MIT License](LICENSE).  
