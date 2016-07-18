# pacotes

Versões do meu pacote BayesSemLagrimas, feito para ajudar a turma da disciplina Estatística Bayesiana da Universidade Estadual de Maringá.

Todas as simulações e resultados são obtidos através do pacote *BRugs* que por sua vez, faz uso do software *OpenBUGS*, portanto, quanto ao item

**Nas questões práticas utilize exclusivamente a livraria BRugs do R;**

Fica plenamente satisfeito.

Qualquer coisa entrar em contato por <bruno.albuquerque1990@gmail.com>

#Instalção

## Atualizar para a última versão do R, da pra fazer facilmente com o código:
if(!require(installr)) {
install.packages("installr"); require(installr)} #load / install+load installr

updateR() 

## Instale a última versão do RStudio: <https://www.rstudio.com/products/rstudio/download/>

##Instalar OpenBUGS baixar em <http://www.openbugs.net/w/Downloads>

##Baixar *BRugs_0.8-6* e *BayesSemLagrimas_x.x* 

dar setwd() na pasta onde vc baixou os pacotes

install.packages("BRugs_0.8-6.zip", repos = NULL, type = "win.binary")

install.packages(c('coda','ggplot2','data.table','knitr','rmarkdown'),dependencies = T)

install.packages("BayesSemLagrimas_1.1.tar.gz", repos = NULL, type = "source")



