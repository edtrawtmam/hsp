# hsp
## Repositório de desenvolvimento do HSPmol e da pesquisa de curso

Este repositório serve para o desenvolvimento da plataforma HSPmol. A plataforma é uma aplicação web baseada em Python-Flask para a gestão de coleções de substâncias e a interpretação de compatibilidade entre elas a partir das suas propriedades. O principal conjunto de propriedades utilizado para inferir a compatibilidade entre as substâncias são os Parâmetros de Solubilidade de Hansen (HSP).
Até agora não há um release do HSPmol disponível, no entanto, noa parte das funções da plataforma já estão disponíveis em uma versão pré-release no formato colab, no arquivo HSPmol.ypnb na raíz deste repositório.
A plataforma HSPmol pretende auxiliar o usuário, organizando coleções de substâncias que terão sua compatibilidade analisada. As substâncias presentes na coleção poderão ter determinados seus parâmetros de solubilidade de Hansen (HSP) através de mais de um método e para isso o usuário poderá contar com a busca de propriedades e susbstâncias em bases de dados eletrônicas, além de modelo de machine learning. A produção de gráficos e relatórios comparativos das propriedades das substâncias subsidiará o trabalho de seleção de conjuntos soluto-solventes que atendam os pré-requisitos propostos em cada projeto de coleção. Com isso se pretende otimizar o trabalho do pesquisador, reduzindo o custo e o consumo de reagentes e seus descartes decorrentes dos ensaios em bancada, promovendo a química verde e o planejamento dos experimentos em laboratório.
Este trabalho está em andamento!

######################################################
HSP_git é o master oculto do projeto de aplicativo HSP
A execução do aplicativo acontece na linha de comando:
Para executar a aplicação: $ python3 hsp.py runserver

Na instalação:
Para inicializar os bancos de dados e criar as pastas necessários pra isso: $ python3 hsp.py db init

Para migração da base de dados e criar os arquivos. Cria a tabela "alembric": $ python3 hsp.py db migrate

Para criar as tabelas da base de dados: $ python3 hsp.py db upgrade

Toda vez que houver alteração na estrutura do banco de dados
é necessário repetir os comandos migrate e upgrade
######################################################
