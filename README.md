# soester-duinen.nl demo site
Repository for the website https://soester-duinen.nl including some of my best pictures

You can use this  template for your own and change it and make it yours.

Use it in Kubernetes with nginx

helm repo add bitnami https://charts.bitnami.com/bitnami

helm install  yourapp-nginx --set cloneStaticSiteFromGit.enabled=true --set cloneStaticSiteFromGit.repository=https://github.com/nondualit/soester-duinen.nl.git --set cloneStaticSiteFromGit.branch=main bitnami/nginx

More info

https://github.com/bitnami/charts/tree/master/bitnami/nginx/#installing-the-chart

All pictures made by Anibal Ojeda can be used under the CC0-1.0 license
