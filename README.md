Magento 2 Finish Code Migration
===============================

## English Section

This script was made to finish the process of converting your custom Magento 1.x code to Magento 2.
It only works with the official [Magento Code Migration Toolkit](https://github.com/magento/code-migration)


### Installation

1. Copy `makeCodeReadyToUse.php` to `your-code-migration-develop-path/src/Magento/Migration/Internal/Command`
2. Follow all [Magento Code Migration Toolkit](https://github.com/magento/code-migration) steps
3. After the `Migrate PHP code` step:
 * Make a backup of your `<dst>` directory
 * run: `php bin/utils.php makeCodeReadyToUse <dst>`

This script remove all php files and rename all files with a `*.converted` extension into `php` extension.

## French Section

Ce script a été conçu pour terminer le processus de conversion de votre code personnalisé de Magento 1.x vers Magento 2.x
Il fonctionne uniquement avec la version officielle de [Magento Code Migration Toolkit](https://github.com/magento/code-migration)


### Installation

1. Copiez le fichier `makeCodeReadyToUse.php` dans le dossier `your-code-migration-develop-path/src/Magento/Migration/Internal/Command`
2. Suivez toutes les étapes de migration de [Magento Code Migration Toolkit](https://github.com/magento/code-migration) steps
3. Après l'étape `Migrate PHP code` :
 * Créez une sauvegarde de votre dossier `<dst>`
 * exécutez la commande: `php bin/utils.php makeCodeReadyToUse <dst>`

Ce script supprime tous les fichiers php et renomme les fichiers avec l'extension `*.converted` en `*.php`