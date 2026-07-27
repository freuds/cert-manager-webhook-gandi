# CHANGELOG
| Date | Version | Description |
| ------ | ------ | ------ |
| 2026-07-12 | v0.6.1 | fix concurrent DNS-01 challenges on the same FQDN (apex + wildcard):<br>Present now appends the TXT value to the existing rrset instead of replacing it<br>CleanUp now removes only the challenge's own value and deletes the record only when empty |
| 2021-10-11 | v0.3.0 | SINTEF fork version |
| 2021-10-11 | v0.2.0 | add chart-releaser GitHub action |
| 2021-10-06 | v0.2.0 | update cert-manager to 1.5.4<br>update k8s API version to 0.22.2<br>migrate to new LiveDNS API (https://api.gandi.net)<br>add Helm repo with GitHub pages<br>simplify Dockerfile & switch to Buildx<br>update make test target (remove shell script)<br>update README.md with changes made<br>update GitHub workflow with Buildx<br>add k8s APF support (k8s >= 1.20) |
| 2020-02-26 | v0.1.1 | switch to Docker Hub |
| 2020-02-26 | v0.1.0 | initial release |