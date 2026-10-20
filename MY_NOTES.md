# Notes made during project implementation
**During every tutorial project, I make notes on what I had to do to achieve the goal. These notes are stored here.**

1) This tutorial is rather miniscule. Steps 3 and 4 actually repeat Step 2, but on Terraform servers instead of EKS. I did not complete them, since my goal is mainly to learn AWS (EKS in this case).
2) AWS console login should, of course, be set up before being able to run terraform apply.
3) The .tf files had to be adjusted before running terraform apply, setting the desired sizes, key pair, region and the CIDR block. These changes, being private, are not included into this repository.
4) The settings endpoint_public_access and endpoint_private_access must both be true to allow the creation of this cluster. To improve security, it could also be possible to edit endpoint access cidrs in variables.tf.