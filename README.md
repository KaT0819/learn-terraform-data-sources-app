# Learn Terraform data sources

Learn how Terraform data sources help you import data into your Terraform configuration.

Follow along [with this
tutorial](https://learn.hashicorp.com/tutorials/terraform/data-sources?in=terraform/configuration-language)
on HashiCorp Learn.


## 手順
本ソースではlearn-terraform-data-sources-vpcにて定義したVPCを用いているため、
先にlearn-terraform-data-sources-vpcをappliyしてからこちらの手順を進める。

``` shell
terraform init

terraform apply

curl $(terraform output -raw lb_url)

```
