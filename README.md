# Projeto Unidade 02 | PENTAHO | Data Analytics | Digital College Brasil

Desenvolvimento de aplicação de JOB no PENTAHO para carregar o Data Warehouse.<br>
Tecnologias utilizadas: SQL / PostgreSQL / Pentaho.<br>

Instituição: [Digital College Brasil](https://digitalcollege.com.br/) (Fortaleza/CE) <br>
Curso: Data Analytics (Turma 18) <br>
Instrutora: [Nayara Wakweski](https://github.com/NayaraWakewski) <br>

## Etapas de Desenvolvimento (Summary)
1. Entendimento macro do projeto. Através do Pentaho (ktr's & job's), carregar dados do STAGE para o DW, PostgreSQL `(bd corporativo_final)`".
2. Criar bd STAGE.
3. Criar estrutura física do bd STAGE.
4. Conectar base de dados `corporativo_final` e `stage` no PENTAHO.
5. Desenvolver o processo de ETL para carregar o STAGE. Criar os fluxos (ktr's) no PENTAHO para cada tabela (produtos, vendendor, nota_fiscal, item_nota_fiscal).





## 3. Tabelas bd STAGE, estrutura física.
![screenshot](/images/estrut_fis_bd_stage.png) <br>

## 4. Conectar base de dados `corporativo_final` e `stage` no PENTAHO.
![screenshot](/images/conexao_bds_postgres_pentaho.png) <br>

## 5. Execução da sequência de STEPS no Pentaho, tabela `produtos`.
