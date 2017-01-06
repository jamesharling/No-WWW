# No-WWW
Azure App Service extension to remove the www prefix on requests.

# Installation
Install using your App Service's SCM site or through the Azure Portal.

# Usage
Once installed, you will need to restart your App Service to pick up the changes. Once done, the site will remove any `www.` prefix from the requested domain, e.g. `www.google.co.uk => google.co.uk`
