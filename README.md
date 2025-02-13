# soester-duinen.nl demo site
Repository for the website https://soester-duinen.nl including some of my best pictures

You can use this  template for your own and change it and make it yours.

Use it in Kubernetes with nginx

helm repo add bitnami https://charts.bitnami.com/bitnami

helm install  yourapp-nginx --set cloneStaticSiteFromGit.enabled=true --set cloneStaticSiteFromGit.repository=https://github.com/nondualit/soester-duinen.nl.git --set cloneStaticSiteFromGit.branch=main bitnami/nginx

More info

https://github.com/bitnami/charts/tree/master/bitnami/nginx/#installing-the-chart

All pictures made by Anibal Ojeda can be used under the GNU General Public License (GPL) 3.0

Please contact me if you want to have the picture without mark.

## Copyright

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.
