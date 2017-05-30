# Git en Français

## Introduction

Det dagliga språket för de olika kommandona i `git` (eller `jävel`) är
på svenska ett enda stort svengelskakalas. Jag finner mig själv ofta
sägandes _"Kan du pusha branchen?"_ eller _"Jag pullar!"_, vilket
känns pinsamt.

Detta dokument ämnar etablera en ren svensk jargong som kan användas
på arbetsplatsen för att med fördel undvika pressade situationer med
kollegor samt boskap.

## Proposition

Nedan följer tabeller över verb och substantiv relaterade till git,
deras nuvarande bruk samt förslag på hur vi tillsammans kan bättra
oss.

| Verb        | Usage courrant | Proposition   |
|-------------|----------------|---------------|
| pull        | poule          | tirer         |
| push        | pouche         | pousser       |
| fetch       | fetcher        | rapporter     |
| branch      | brancher       | fourcher      |
| commit      | commiter       | sousmettre    |
| rebase      | rebaser        | amputer       |
| merge       | merger         | combinaison   |
| squash      | squasher       | ecraser       |
| stash       | stasher        | cacher        |
| tag         | taguer         | étiquetter    |
| cherry-pick | cherry-picker  | trier         |
| amend       | amender        | corriger      |
| blame       | blâmer         | blâmer        |

| Substantiv   | Usage courrant | Proposition       |
|--------------|----------------|-------------------|
| git          | git            | salaud            |
| repository   | repo           | dépôt             |
| branch       | branch         | branche           |
| commit       | commit         | sousmission       |
| pull request | pull request   | requête de tirage |
| stash        | stache         | cachette          |
| tag          | tagg           | étiquette         |

## Exemples
    - Pourrais tu tirer la branche que je vien d'amputer puis la pousser à github?
    
    - J'ai fourcher recement et sousmis les changement de ma cachette.
    
    - Envois une requete de tirage quand tu as fini avec la combinaison! 

    - Trions donc la branche-maître.

    - Mince, j'ai malencontreusement forcer le poussage sur la branche maître. D:

    - Ecrase mes sousmission avant de combiner.

## Dagligt bruk

Nedan följer en rad kommandoradskommandon för att sätta upp en svensk
gitmiljö. Avsaknaden av svenska tecken i täcknamnen beror på en brist i git
(överväg att förbättra mjukvaran och skicka en ryckbegäran!). Följande
kommandon ändrar din `~/.gitconfig` och kommer att verka globalt.

    git config --global alias.ryck pull
    git config --global alias.knuffa push
    git config --global alias.gren branch
    git config --global alias.forgrena branch
    git config --global alias.forbinda commit
    git config --global alias.ympa rebase
    git config --global alias.sammanfoga merge
    git config --global alias.gom stash
    git config --global alias.klandra blame
    git config --global alias.marke tag
    git config --global alias.mark tag

    alias jävel=git
