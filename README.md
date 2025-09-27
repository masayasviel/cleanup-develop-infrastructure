# cleanup develop infrastructure

## CFn

```sh
chmod 777 create.sh update.sh
editor ./params/{file name}
# 拡張子は含めない
./create.sh {yml file name}
./update.sh {yml file name}
# IAMロール作成系は下記オプションをつける
--capabilities CAPABILITY_NAMED_IAM
```
