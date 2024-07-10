# packer-commands

- packer init .
- packer fmt .
- packer validate .
- packer build file-name.pkr.hcl
- packer build --var-file=variables.pkrvars.hcl file-name.pkr.hcl
Packer will automatically load any variable file that matches the name *.auto.pkrvars.hcl