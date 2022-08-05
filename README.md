# DxEMSSQL

This repository contains the Dockerfile and YAML configuration necessary to 
create and deploy a combined DxEnterprise + SQL Server container image. Please see 
[this tie-in Microsoft guide](https://docs.microsoft.com/en-us/sql/linux/tutorial-sql-server-containers-kubernetes-dh2i?view=sql-server-ver16)
for instructions on using the Dockerfile and YAML in this directory.

## Helm Charts

This repository also contains Helm chart source files and tarballs for the combined DxEnterprise + SQL Server container image in Kubernetes. Helpful variables can be found in the `questions.yml` file in the source directory.