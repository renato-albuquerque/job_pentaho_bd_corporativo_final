# Projeto Unidade 02 | PENTAHO | Data Analytics | Digital College Brasil

Desenvolvimento de projeto para automatizar carga de dados no DW, utilizando JOB no PENTAHO.<br>
Tecnologias utilizadas: SQL / PostgreSQL / Pentaho.<br>

Instituição: [Digital College Brasil](https://digitalcollege.com.br/) (Fortaleza/CE) <br>
Curso: Data Analytics (Turma 18) <br>
Instrutora: [Nayara Wakweski](https://github.com/NayaraWakewski) <br>

## Etapas de Desenvolvimento (Summary)
1. Entendimento macro do projeto. Através do Pentaho (ktr's & job's), carregar dados do STAGE para o DW, PostgreSQL `(bd corporativo_final)`".
2. Criar bd STAGE.
3. Criar estrutura física do bd STAGE.
4. Criar tabelas no bd STAGE.
5. Conectar base de dados `corporativo_final` e `stage` no PENTAHO.
6. Desenvolver o processo de ETL para carregar o STAGE. Criar os fluxos (ktr's) no PENTAHO para cada tabela (produto, pessoa_fisica, nota_fiscal, item_nota_fiscal).
7. Desenvolver processo de ETL para carregar o Data Warehouse. Criar o job no PENTAHO.





## 3. Tabelas bd STAGE, estrutura física (_Imagem ilustrativa_).
![screenshot](/images/estrut_fis_bd_stage.png) <br>

## 4. Conectar base de dados `corporativo_final` e `stage` no PENTAHO.
![screenshot](/images/conexao_bds_postgres_pentaho.png) <br>

### Transformações no PENTAHO (ktr's).

## 5. Execução da sequência de STEPS no Pentaho, tabela `produtos`.
