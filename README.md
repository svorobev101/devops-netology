# devops-netology
## Sergei Vorobev


## gitignore
- все вложенные директории .terraform 
```**/.terraform/*```
- все файлы, с расширением ```.tfstate```, либо содержащие маску ```.tfstate.``` в названии
```
*.tfstate
*.tfstate.*
```
- файл ```crash.log```
- все файлы с расширением .tfvars ```*.tfvars```

- файл ```override.tf```, все файлы с расширением ```.tf``` и именем, заканчивающимся на ```override```, либо ```.json``` 
и именем, заканчивающимся на ```override.tf```

```override.tf
override.tf.json
*_override.tf
*_override.tf.json
```
- файл ```terraform.rc``` и все файлы с расширением ```.terraform```
```
.terraformrc
terraform.rc
```