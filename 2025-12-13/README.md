# Anniversaire de Samuel

Le superbe livret de dinosaures vient de [Blogue à part](https://blogueapart.com/2021/02/20/mes-petites-fiches-informatives-sur/), et dont 3 pages ont été supprimées pour réduire le nombre d'impressions (pour 9 enfants au total).

La dernière étape de la casse au trésor est un safari dans le Jurassic Park (le champs de l'autre côté de la route) et nous avions mis de la musique pour le trajet (`Jurassic Park • Main Theme • John Williams.mp4`) puis des sons de dinosaures lorsque nous étions dans les hautes herbes (`99 type of dinosaurs sound effects family of dinosaurs.mp4`). Les enfants étaient dans la remorque tirée par le RAV4... :)

## Itinéraire

1. Aquarium (mosasaure)
2. Bambous (tricératops)
3. Herbe de la pampa (parasaurolophus)
4. Cascade (stégosaure, avec affiches de distance sur le trajet)
5. Cabane (ankylodaure)
6. Marre (brachiosaure)
7. Serre avec les poules (vélociraptor)
8. Balles de paille (ptérodactyle)
9. Grange (tyrannosaure)
10. Au fond du champs (spinosaure)

## Création du Livret

```shell
pdftk 'mes fiches dinosaures.pdf' cat 1 3-21 24 output '/tmp/dinosaures.pdf'
gs -o 'livret-dinosaures.pdf' -sDEVICE=pdfwrite -dPDFSETTINGS=/prepress '/tmp/dinosaures.pdf'
```
