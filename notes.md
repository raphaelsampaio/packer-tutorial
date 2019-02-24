Packer runs based on templetes, describing instances via the `builders` node.

A **builder** is responsible for creating an instance (AWS EC2, for example) and extracting an image (AWS AMI) out of it.

To validate a template, run `packer validate template.json`.