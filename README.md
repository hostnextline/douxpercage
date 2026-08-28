# Doux Perçage

Site vitrine une page de **Doux Perçage** — académie de perçage et service de
perçage, à Montréal. Nour Jeha, fondatrice.

En ligne : <https://hostnextline.github.io/douxpercage/>
Version précédente archivée : <https://hostnextline.github.io/douxpercage/v1/>

## Le formulaire

Il n'est **pas branché**. La constante `ENDPOINT_FORMULAIRE`, dans le script en
bas de `index.html`, est vide : tant qu'elle l'est, le formulaire le dit
clairement et renvoie vers le téléphone. Il n'affiche jamais un faux succès.
Renseignez une URL qui accepte un POST JSON `{prenom, telephone, but, type}`
et il fonctionne.

## Les médias

`assets/hero.mp4` est le tournage réel du studio, retravaillé : sous-titres
anglais recadrés, fondu enchaîné de 1,2 s pour boucler sans couture, audio
retiré. Il est chargé après le premier rendu, jamais en mouvement réduit ni en
économiseur de données, et n'apparaît qu'au premier événement `playing` — le
poster reste visible si la lecture échoue.

`og.html` sert uniquement à régénérer la carte de partage.

## Contenu

Un seul fichier autonome, `index.html` : styles et script inclus, aucun build,
aucune dépendance externe. Aucun témoin, aucun traceur, aucun appel à un
domaine tiers.
