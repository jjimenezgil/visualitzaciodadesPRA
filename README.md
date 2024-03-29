# PRA Visualització de dades

## En que consisteix la PRA de l'assignatura de Visualització de Dades?
Per a la PRA final de l'assignatura s'han utilitzat les dades del "Cens de persones desaparegudes durant la Guerra Civil", 
disponibles al Portal de dades obertes de la Generalitat de Catalunya (https://analisi.transparenciacatalunya.cat/Legislaci-just-cia/Cens-de-persones-desaparegudes-durant-la-Guerra-Ci/u2ix-2jr6/about_data). 
S'ha utilitzat Streamlit (programat en Python) per generar una sèrie de visualitzacions sobre aquestes dades i intentar 
respondre algunes preguntes que ens haviem plantejat prèviament. El projecte consta de l'estructura següent:

* visualitzaciodadesPRA (repository): arrel del projecte.
  * data (folder): on es guarden les dades que nutreixen les visualitzacions del projecte.
  * other (folder): s'hi emmagatzema el fitxer .rmd (codi R) que es va utilitzar per dur a terme la neteja prèvia de les dades.
  * src (folder): conté el projecte de Streamlit amb el codi Python, concretament el de la pàgina d'inici (Inici.py).
      * pages (folder): conté la resta de pàgines del projecte.
  * LICENSE.md (file): llicència open source del projecte.
  * README.md (file): fitxer amb el detall i estructura del projecte.
  * requirements.txt (file): fitxer amb els requeriments (llibreries) del projecte. És important que estigui situat a l'arrel per a que
    l'aplicació es desplegui correctament al servidor de Streamlit.

## Com visualitzar el projecte?
L'app Streamlit del projecte és accessible de manera pública i sense necessitat de registre a la següent URL:
https://visualitzaciodadespra-personesdesaparegudesguerracivil.streamlit.app
