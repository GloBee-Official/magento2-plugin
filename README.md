# NOTICE
This is a Community-supported project.

If you are interested in becoming a maintainer of this project, please contact us at integrations@globee.com. Developers at GloBee will attempt to work along the new maintainers to ensure the project remains viable for the foreseeable future.

# GloBee plugin for Magento 2

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square)](https://raw.githubusercontent.com/GloBee-Official/magento2-plugin/master/LICENSE.txt)

# Description

Bitcoin payment plugin for Magento using the globee.com service.

## Quick Start Guide

To get up and running with our plugin quickly, see the GUIDE here: https://github.com/GloBee-Official/magento2-plugin/blob/master/GUIDE.md

## Support

**GloBee Support:**

* Last Cart Version Tested: 2.1.2
* [GitHub Issues](https://github.com/GloBee-Official/magento2-plugin/issues)
  * Open an issue if you are having issues with this plugin.
* [Support](https://help.globee.com)
  * GloBee merchant support documentation

**Magento Support:**

* [Homepage](http://magento.com)
* [Documentation](http://docs.magentocommerce.com)
* [Community Edition Support Forums](https://www.magentocommerce.com/support/ce/)

## Troubleshooting

1. Ensure a valid SSL certificate is installed on your server. Also ensure your root CA cert is updated. If your CA cert is not current, you will see curl SSL verification errors.
2. Verify that your web server is not blocking POSTs from servers it may not recognize. Double check this on your firewall as well, if one is being used.
3. Check the `payment_bitpay.log` file for any errors during GloBee payment attempts. If you contact GloBee support, they will ask to see the log file to help diagnose the problem.  The log file will be found inside your Magento's `var/log/` directory. **NOTE:** You will need to enable the debugging setting for the extension to output information into the log file.
4. Check the version of this plugin against the official plugin repository to ensure you are using the latest version. Your issue might have been addressed in a newer version! See the [Releases](https://github.com/GloBee-Official/magento2-plugin/releases) page or the Magento Marketplace for the latest version.
5. If all else fails, send an email describing your issue **in detail** to support@globee.com

**TIP:** When contacting support it will help us is you provide:

* Magento CE Version (Found at the bottom page in the Administration section)
* Other extensions you have installed
  * Some extensions do not play nice
* Configuration settings for the extension (Most merchants take screen grabs)
* Any log files that will help
  * web server error logs
  * enabled debugging for this extension and send us `var/log/payment_bitpay.log`
* Screen grabs of error message if applicable.


## Contribute

To contribute to this project, please fork and submit a pull request.