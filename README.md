# terraform-docker-nginx

Quick tutorial for a simple setup which follows the official guide [here](https://developer.hashicorp.com/terraform/tutorials/aws-get-started/install-cli).

Provisions an NGINX server on port 8080.

## Steps

After starting Docker service:

```
terraform init

(optional) terrafom plan

terraform apply
```

Verify the existence of the NGINX container by visiting `localhost:8000` or running `docker ps` to see the container.

To stop the container: `terraform destroy`.
