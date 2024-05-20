# VHP4Safety webapge

Repository to redirect from vhp4safety.nl to ScienCrew

The setup is as follows:

1. the DNS records for vhp4safety.nl point to one of the GitHub DNS servers
2. GitHub Pages uses the `CNAME` file in this repository to link to (www.)vhp4safety.nl website to the GitHub pages in this repository
3. this landing page repository does a HTTP redirect (302) to the ScienCrew webpage
