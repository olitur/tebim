# TEBIM
{% include "index.md" %}

## Tutoriels
### Principes du BIM
{% include "tutoriels/index-tutoriels.md" %}

### Avantages
{% include "tutoriels/avantages-bim.md" %}

### Inconvénients
{% include "tutoriels/inconvenients-bim.md" %}

### Flux de production
{% include "tutoriels/flux-production-bim.md" %}


## Manuels
{% include "manuels/index-manuels.md" %} 

### BIM isolé (niveaux 0 & 1)
{% include "manuels/maquette-simple-bim0+1.md" %}

### BIM collaboratif (niveau 2)
{% include "manuels/maquette-elaboree-bim2.md" %}

## Compléments

###Concepts BIM
{% include "complements/notions/index-notions.md" %}


### Définition BIM
{% include "complements/notions/definition-BIM.md" %}


### Convention BIM
{% include "complements/notions/convention-BIM.md" %}

### Niveaux BIM
{% include "complements/notions/notions_niveaux-bim.md" %}

### Implications au Futur
{% include "complements/notions/implications-au-futur-bim.md" %}

##Références BIM
{% include "complements/references/index-references.md" %}

### Normes BIM
{% include "complements/references/norme-bim-bim.md" %}


<!-- 
pandoc .\TEBIM-all.md -o .\TEBIM-all.pdf --from markdown -N --variable mainfont="Myriad Pro" --pdf-engine=xelatex --template=eisvogel.tex 

pandoc --defaults defaults.yaml -H chapter-breaks.tex -o .\TEBIM-all.pdf --from markdown -N --variable mainfont="Myriad Pro" --pdf-engine=xelatex 

-->