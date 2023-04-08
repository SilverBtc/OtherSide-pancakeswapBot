# OtherSide-pancakeswapBot

Ce bot est un script Python conçu pour acheter une crypto-monnaie spécifique sur PancakeSwap dès que la liquidité minimale requise est disponible. 

## Installation

### Sur Mac
1. Ouvrez le Terminal
2. Installez Homebrew en collant la commande suivante dans le Terminal et en appuyant sur Enter : 
    ```
    /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
    ```
3. Ensuite, installez Python en tapant cette commande : 
    ```
    brew install python
    ```
### Sur Windows
1. Ouvrez le microsoft Store
2. Télécharger Python 3.9

## Téléchargement du bot

1. Rendez-vous sur la page GitHub du projet : https://github.com/SilverBtc/OtherSide-pancakeswapBot.
2. Cliquez sur le bouton "Code" vert en haut à droite de la page (en vert), puis sélectionnez "Download ZIP".
3. Extrayez les fichiers dans le dossier de votre choix.

## Configuration

1. Ouvrez le fichier "config.json" avec un éditeur de texte.
2. Entrez votre clé privée pour le compte que vous souhaitez utiliser pour effectuer les transactions dans le champ "privateKey".
3. Entrez le montant de la crypto-monnaie que vous souhaitez acheter dans le champ "amount to buy".
4. Entrez le montant de gas limit que vous souhaitez utiliser dans le champ "gwei".
5. Entrez le montant minimum de liquidité BNB requise pour l'achat de la crypto-monnaie dans le champ "minBnbLiquidity".

## Lancement du bot

1. Ouvrez le Terminal ou l'invite de commande.
2. Accédez au dossier où vous avez extrait les fichiers du bot à l'aide de la commande `cd`.
3. Installez les dépendances du bot en tapant la commande suivante : 
    ```
    pip install -r requirements.txt
    ```
4. Enfin, lancez le bot en tapant la commande suivante : 
    ```
    python main.py
    ```
ou 
    ```
    python3 main.py
    ```

Le bot commencera à surveiller la liquidité de la crypto-monnaie spécifiée et achètera automatiquement dès que la liquidité minimale requise sera disponible.
Pour couper le bot faite simplement : ctrl + c
