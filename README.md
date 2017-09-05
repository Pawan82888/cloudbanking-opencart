# cloudbanking-opencart
## OpenCart Cloudbanking payment module

Versions

* To install Cloudbanking payment module you need  OpenCart 3.x versions

### Installation

* Backup your webstore and database
* Upload the module file [cloudbanking.ocmod.zip] via _Extensions_ -> _Extension Installer_
* Activate the module in payment extensions (_Extensions_ -> _Payments_)
* Configure the module settings:
  * Auth key
  * Api Version
  * Customer Id
  * Enabled the module

* After saving configuratin the most important step you need to install package  cloudbanking/omnipay-cloudbanking   using composer.

* in terminal open the root directory of opencart and write a command composer require "cloudbanking/omnipay-cloudbanking" .

* To ensure that your package is install go into system->storage->vendor and look for package name "cloudbanking".

### Notes

Tested and developed with OpenCart v.3.0.2.0

### Troubleshooting

If you hosting service doesn't provide a FTP access

Alternatively you can just upload the _upload_ directory content to your opencart
installation directory.


