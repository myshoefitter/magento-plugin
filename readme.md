# mySHOEFITTER Plugin for Magento 2

<a href="https://en.myshoefitter.com" target="_blank" className="banner-image">
  <img src="https://raw.githubusercontent.com/myshoefitter/js-sdk/main/.github/readme/promotion.jpg" alt="mySHOEFITTER Promotion Banner" />
</a>

### Method 1: Installation via Composer
1. Add Repository: Add the Github repository to your Magento project:
```bash
composer config repositories.vendor_myshoefitter vcs https://github.com/myshoefitter/magento-plugin.git
```
2. Require the Module: Run the following command to require the module into your project:
```bash
composer require vendor/myshoefitter
```
3. Enable the Module: After installation, run the following commands:
```bash
php bin/magento setup:upgrade
php bin/magento setup:di:compile
php bin/magento cache:clean
```
4. Verify Installation: Ensure that the module is enabled:
```bash
php bin/magento module:status Vendor_mySHOEFITTER
```
You should see Vendor_mySHOEFITTER in the list of enabled modules.

### Method 2: Manual Installation
1. **Download the Module:** Download and unzip the MyShoeFitter module.
2. **Upload Files:** Upload the extracted folder to your Magento installation under app/code/Vendor/MyShoeFitter. If the code directory does not exist, create it within the app directory.
3. **Enable the Module:** Run the following commands from the root of your Magento 2 installation:
```bash
php bin/magento setup:upgrade
php bin/magento setup:di:compile
php bin/magento cache:clean
```
4. **Verify Installation:** Ensure that the module is enabled by running:
```bash
php bin/magento module:status Vendor_mySHOEFITTER
```
You should see Vendor_mySHOEFITTER in the list of enabled modules.

---

**🚀 Get your Shop ID at [https://en.myshoefitter.com/kontakt](https://en.myshoefitter.com/kontakt)**  
**📖 Read the Documentation at [https://docs.myshoefitter.com](https://docs.myshoefitter.com)**