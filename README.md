# Atividade CI – Aula Remota 1 (DevOps / Terraform / Ansible)
##  Evidências:

1. **Terraform**
   ```bash
   terraform -chdir=terraform init
   terraform -chdir=terraform validate
   ```
terraform validate antes e depois de resolver o erro na versão do python
<img width="528" height="347" alt="terraform_1" src="https://github.com/user-attachments/assets/187c6e1a-396c-4567-ae03-16ab4b660742" />

   ```bash
   terraform -chdir=terraform plan
   ```
   <img width="351" height="390" alt="terraform_2" src="https://github.com/user-attachments/assets/447b360d-d82c-4af8-a8a5-8bba20165d2a" />


2. **Ansible**
   ```bash
   ansible-playbook --syntax-check ansible/playbook.yml
   ```
<img width="523" height="96" alt="ansible_1" src="https://github.com/user-attachments/assets/e793141b-9ec2-40a2-83a6-9d47bca37a33" />

## ⚙️ CI (GitHub Actions)
<img width="943" height="413" alt="actions_1" src="https://github.com/user-attachments/assets/2141d8f7-25f1-4784-9b44-c506fe129df1" />
