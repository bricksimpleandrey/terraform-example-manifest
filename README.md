# terraform-example-manifest

You need to fork this repo and change the `terraform.json` to contain the `s3prefix` you choose in the very start of this tutorial. This is for terraform to centralize the state files of your provisioned infrastructure within your root s3 bucket. This ensures that if terraform commands are run on multiple machines, they all use the same state file.

Change `optimus-prime-008` in that file to the s3 prefix you choose at the start.

Once you change the `s3prefix` in the `terraform.json` file, you should signup for a dockerhub account. Optionally you may use the built in demo account already in `docker.json`.