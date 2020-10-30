# cdap_etl
Repositório para fins Acadêmicos com Integração de Dados entre o CDAP SandBox e o Google Cloud Platform

Como primeira etapa, é necessário criar a Chave de Autenticação OAuth no GCP, para que possa ser feito o acesso a toda a estrutura do Google Cloud de determinado projeto.

Como estrutura de "VM" foi utilizado o Docker através do docker-compose, que contempla uma instancia do CDAP que conecta no meu perfil pesso do Google Cloud e uma Instância do Mongodb para armazenamento dos twitts.

Os artefatos deste projetos estão descriminados da seguinte forma:

 Diretorios                 Conteúdo

 arquitetura                Arquitetura.pdf

 docker-compose             docker-compose

 notebook                   jupyter-lab de coleta no twitter

 pipelines                  01_carrega_dados_vendas-cdap-data-pipeline.json
                            02_consolida_dados_vendas-cdap-data-pipeline.json
                            03_carrega_dados_twitter-cdap-data-pipeline.json

 scripts                    mongoexport.txt

 sources                    Base_2017_1.csv
                            Base_2018_2.csv
                            Base_2019_3.csv
                            tweets.csv

Desta forma finalizo resumo dos artefatos contidos neste projeto.