# LungCancer
Tratamento de dados:
usámos diagnosticos com nodulos a cima de 3mm com label;
apagamos da base de dados tudo o que nao tinha nodulos com label ou pacientes com diagnostico que não tinha nódulos a cima de 3mm;
link original: https://wiki.cancerimagingarchive.net/pages/viewpage.action?pageId=1966254
não há um paciente com mais que 2 nodulos com diagnostico, logo todas as imagens de nodulos a seguir ao segundo foram apagados;



Milestones:

DONE:

download das imagens
tratar as imagens para ficar só a area do tumor
eliminar as imagens desncessárias e explorar pyradiomics para fazer a tabela.
Criar features table:

NEXT:


Cortar pacientes que não têm diagnostico
Explorar modelos e resultados.

TODO
Miguel:
[X] - PDF da ética
[X] - Preparar setup para o vídeo
[ ] - Editar comentários do Notebook

Champ
[X] - Implemntar Neural Networks
[ ] - Data Augmentation

Vaz 
[X] - Implementar SVM
[ ] - Outliers e possivelmente eliminados

Richie
[X] - Funções F1, AUC e ConfusionMatrix

