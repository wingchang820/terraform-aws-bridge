# Terraform ↔ Docker Local Bridge (Nginx + Redis)
- Init: `terraform init -upgrade`
- Plan: `terraform plan`
- Apply: `terraform apply` (Nginx 8080, Redis 6379)
- Verify: `curl -I http://localhost:8080`, `docker exec -it demo_redis redis-cli ping`
- Destroy: `terraform destroy`
