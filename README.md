# Pragmatic Terraform on AWS

のサンプルコードの写経

## 準備

### Terraformのインストール

anyenv => tfenv => terraform を使うと便利 

### AWS設定
```shell script
$ AWS_ACCESS_KEY_ID=${yourid}
$ AWS_SECRET_ACCESS_KEY=${yourkey}
$ AWS_DEFAULT_REGION=${yourregion (ap-northeast-1)}
```

## コマンド
```shell script
$ terraform init
$ terraform plan
$ terraform apply
$ terraform destroy
```
