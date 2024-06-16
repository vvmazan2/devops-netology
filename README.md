# devops-netology
В глобальном gitignore в данный момент никакие файлы не игнорируются.
В gitignore созданном в директории terraform игнорируются след файлы и директории:
**/.terraform/*
*.tfstate
*.tfstate.*
crash.log
crash.*.log
*.tfvars
*.tfvars.json
override.tf
override.tf.json
*_override.tf
*_override.tf.json
.terraform.tfstate.lock.info
.terraformrc
terraform.rc