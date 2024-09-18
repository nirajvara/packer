# packer for AWS AMI creation and installed the packages

packer init packer.pkr.hcl
packer validate packer.pkr.hcl
packer build packer.pkr.hcl

