# devops-netology
1) Modified
2) В каталоге ./terraform будут проигнорированы:
    - все файлы в подкаталоге .terraform
    - Файлы с расширением .tfstate и содержащие внутри имени tfstate (*.tfstate.*)
    - Файл crash.log
    - Файлы с расширением .tfvars
    - Файлы override.tf override.tf.json и любые файлы содержащиие в конце имени *_override.tf и*_override.tf.json
    - Файлы .terraformrc и terraform.rc
3) Новая строчка к заданию 3 занятия 2.2