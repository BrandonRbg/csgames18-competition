# CS Games 2018 - Compétition mobile

Bienvenue à la **compétition mobile des CS Games 2018**!
[(English below ↓)](#cs-games-2018---mobile-competition)

## Introduction

L'arrivée des pingouins de l'espace a fait tout un émoi dans la communauté locale. Inhabitués aux présences vivantes extra-terrestres, les lieux de cultes ont investi toute leur énergie pour offrir de l'aide à ces nouveaux arrivants. Des efforts de masse ont été déployés pour retrouver les pièces du vaisseau éparpillées partout à travers le pays. Une plateforme de *crowdsourcing* a été créée pour documenter les pièces potentiellement identifiées par les tribus. La banque de données résultante a été partagée publiquement à l'adresse suivante:

<p align="center">
  <strong><a>https://s3.amazonaws.com/shared.ws.mirego.com/competition/mapping.json</a></strong>
</p>

Heureux de cette assistance impromptue, les pingouins ont voulu bénéficier de la technologie disponible à leur portée pour utiliser cette banque de données au maximum. Ils ont commencé à développer une application mobile, appelée **Map Ping**, qui leur permettra de consulter cette liste de pièces et de faciliter leur rappatriement. Malheureusement, leurs jours sont comptés et la technologie étant compliquée pour eux, ils ont besoin d'aide pour compléter leur application et se tournent donc vers vous, les fidèles.

<table>
<thead><tr><th colspan="4">Map Ping</th></tr></thead>
<tbody><tr>
<td><a href="https://user-images.githubusercontent.com/4378424/37754070-5d9eff26-2d76-11e8-9ae2-997a32fae982.png" target="_blank"><img src="https://user-images.githubusercontent.com/4378424/37754070-5d9eff26-2d76-11e8-9ae2-997a32fae982.png" alt="SPLASH"></a></td>
<td><a href="https://user-images.githubusercontent.com/4378424/37754069-5d8ffd46-2d76-11e8-9e1d-0a48df719e89.png" target="_blank"><img src="https://user-images.githubusercontent.com/4378424/37754069-5d8ffd46-2d76-11e8-9e1d-0a48df719e89.png" alt="LIST"></a></td>
<td><a href="https://user-images.githubusercontent.com/4378424/37754068-5d822162-2d76-11e8-8b2c-2850d64b70b1.png" target="_blank"><img src="https://user-images.githubusercontent.com/4378424/37754068-5d822162-2d76-11e8-8b2c-2850d64b70b1.png" alt="MAP"></a></td>
<td><a href="https://user-images.githubusercontent.com/4378424/37754067-5d70fe82-2d76-11e8-9c8c-22609a3fd3b8.png" target="_blank"><img src="https://user-images.githubusercontent.com/4378424/37754067-5d70fe82-2d76-11e8-9c8c-22609a3fd3b8.png" alt="AR"></a></td>
</tr>
<tr>
<td><em>Écran d'acceuil</em></td>
<td><em>Liste de pièces</em></td>
<td><em>Carte de pièces</em></td>
<td><em>Réalité augmentée</em></td>
</tr>
</tbody>
</table>


## Pour débuter

Vous trouverez le code de base du projet **Map Ping** dans les sous-dossiers [`ios/`](https://github.com/mirego/csgames18-competition/tree/master/ios) et [`android/`](https://github.com/mirego/csgames18-competition/tree/master/android) de ce répertoire Github:

<table width="100%">
  <thead>
    <tr>
      <th colspan="2">Applications mobiles</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center"><a href="https://github.com/mirego/csgames18-competition/tree/master/ios" target="_blank"><br><img src="https://cloud.githubusercontent.com/assets/4378424/13625721/90d6d7de-e588-11e5-83d9-b16f14b6cfaa.png" height="100"><br><br>Application iOS</a></td>
      <td align="center"><a href="https://github.com/mirego/csgames18-competition/tree/master/android" target="_blank"><br><img src="https://cloud.githubusercontent.com/assets/4378424/13625718/90ca7e30-e588-11e5-9cd1-7fcc06d4a62a.png" height="100"><br><br> Application Android</a></td>
    </tr>
  </tbody>
</table>

Toutes les instructions pour démarrer les applications de base devraient être couvertes au bout des liens respectifs. Si vous avez besoin d'assistance, n'hésitez pas à nous en faire part.


## Le défi

L'application **Map Ping** prévoit afficher les pièces identifiées et aider les pingouins à les retrouver sur la route. Pour l'instant, la listées dans la [banque de données](https://s3.amazonaws.com/shared.ws.mirego.com/competition/mapping.json) n'est pas connectée et l'affichage est entièrement statique.


### Connexion des données

Votre mission, pour commencer, sera d'abord de connecter les données pour les afficher dans l'application. Chaque pièce retrouvée a été détaillée de plusieurs informations:

- Nom de la pièce
- Composant du vaisseau associé
- Notes d'identification (comment retrouver la pièce)
- Type de pièce
- Coordonnées GPS (lat, long)
- Adresse physique

Certaines composantes n'ont pas de coordonnées GPS et d'autres n'ont pas d'adresse physique. Il sera de votre ressort de retrouver l'un à partir de l'autre si nécessaire, à l'aide d'outils de géocodage.

### Modes d'affichage

L'application comporte 3 modes d'affichage:

**Liste**
* Lister chacune des pièces dans une table
* TBD

TBD

## Évaluation

<table><thead><tr><th align="center">
⚠️ Prévoyez au moins 10 minutes à la fin pour préparer votre soumission ⚠️ 
</th></tr></thead></table>



---

# CS Games 2018 - Mobile Competition

Welcome to the **CS Games 2017 Mobile Competition**!
[(French above ↑)](#cs-games-2018---competition-mobile)

## License

This competition is © 2018 [Mirego](http://www.mirego.com) and may be freely
distributed under the [New BSD license](http://opensource.org/licenses/BSD-3-Clause).
See the [`LICENSE.md`](https://github.com/mirego/csgames18-competition/blob/master/LICENSE.md) file.

## Acknowledgements

Component icons were designed by [Eucalyp](https://creativemarket.com/eucalyp) from [Flaticon.com](https://www.flaticon.com/). Thanks 👌

## About Mirego

[Mirego](http://mirego.com) is a team of passionate people who believe that work is a place where you can innovate and have fun. We're a team of [talented people](http://life.mirego.com) who imagine and build beautiful Web and mobile applications. We come together to share ideas and [change the world](http://mirego.org).

We also [love open-source software](http://open.mirego.com) and we try to give back to the community as much as we can.
