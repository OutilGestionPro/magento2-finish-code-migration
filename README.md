Magento 2 Finish Code Migration
===============================
 
This script was made to finish the process of converting your custom Magento 1.x code to Magento 2.
It's especially made to work with the official [Magento Code Migration Toolkit](https://github.com/magento/code-migration)


## Installation

1. Copy `makeCodeReadyToUse.php` to `your-code-migration-develop-path/src/Magento/Migration/Internal/Command`
2. Follow all [Magento Code Migration Toolkit](https://github.com/magento/code-migration) steps
3. After the Migrate PHP code step:
 * Make a backup of your `<dst>` directory
 * run: `php bin/utils.php makeCodeReadyToUse <dst>`

This script remove all php files and rename all files with a *.converted extension into php extension.