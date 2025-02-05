# Projeto Unidade 02 | PENTAHO | Data Analytics | Digital College Brasil

Desenvolvimento de projeto para automatizar carga de dados no Data Warehouse, utilizando o PENTAHO (Job).<br>
Tecnologias utilizadas: SQL / PostgreSQL / Pentaho (PDI).<br>

Instituição: [Digital College Brasil](https://digitalcollege.com.br/) (Fortaleza/CE) <br>
Curso: Data Analytics (Turma 18) <br>
Instrutora: [Nayara Wakweski](https://github.com/NayaraWakewski) <br>

## Etapas de Desenvolvimento (Summary)
1. Entendimento macro do projeto. Através do Pentaho (ktr's & job's), carregar dados do STAGE para o DW, PostgreSQL `(bd corporativo_final)`".
2. Criar bd STAGE.
3. Conectar base de dados `corporativo_final` e `stage` no PENTAHO.
4. Criar estrutura física do bd STAGE.
5. Desenvolver o processo de ETL para carregar o bd STAGE (Tabelas e dados). Criar os fluxos (ktr's) no PENTAHO para cada tabela (produtos, pessoa_fisica, nota_fiscal, item_nota_fiscal).
6. Desenvolver processo de ETL para carregar o Data Warehouse. Criar o job no PENTAHO.



## 3. Conectar base de dados `corporativo_final` e `stage` no PENTAHO.
![screenshot](/images/conexao_bds_postgres_pentaho.png) <br>

## 4. Tabelas bd STAGE, estrutura física (_Imagem ilustrativa_).
![screenshot](/images/estrut_fis_bd_stage.png) <br>

### *** Transformações no PENTAHO (ktr's). ***

## 5. Processo de ETL bd STAGE (Transformações no Pentaho & Carga no PostgreSQL, tabelas: produtos, pessoa_fisica, nota_fiscal, item_nota_fiscal). 

bd stage, tabela public.produtos
![screenshot](/images/ktr_produtos.png) <br>
![screenshot](/images/stage_produtos.png) <br>

bd stage, tabela public.pessoa_fisica
![screenshot](/images/ktr_pessoa_fisica.png) <br>
![screenshot](/images/stage_pessoa_fisica.png) <br>

bd stage, tabela public.nota_fiscal
![screenshot](/images/ktr_nota_fiscal.png) <br>
![screenshot](/images/stage_nota_fiscal.png) <br>

bd stage, tabela public.item_nota_fiscal
![screenshot](/images/ktr_item_nota_fiscal.png) <br>
![screenshot](/images/stage_item_nota_fiscal.png) <br>

### *** Job no PENTAHO ***.

## 6. Desenvolver processo de ETL para carregar o Data Warehouse. Criar o job no PENTAHO.
