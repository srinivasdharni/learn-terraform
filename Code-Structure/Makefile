	dev:
		rm -f .terraform
		terraform init -backend-config=dev-env/state.tfvars
		terraform apply -auto-approve -var-file=dev-env/inputs.tfvars
	
	prod:
		rm -f .terraform
		terraform init -backend-config=prod-env/state.tfvars
		terraform apply -auto-approve -var-file=prod-env/inputs.tfvars