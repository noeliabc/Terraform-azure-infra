# ☁️ Terraform - Infraestructura en Azure
![Banner](./D846E0F6-CDDD-4DB5-BECE-05ED0D1A6A9A.png)
Este proyecto crea una infraestructura básica en Microsoft Azure usando Terraform.  
Ideal para practicar despliegues reales en la nube.

---

## 🧱 Recursos que se crean

- Grupo de recursos (`Resource Group`)
- Red virtual y subred
- Interfaz de red (NIC)
- Máquina virtual Linux (Ubuntu)

---

## 🔧 Requisitos

- Tener una cuenta en [Azure](https://portal.azure.com/)
- Tener instalado:
  - [Terraform](https://www.terraform.io/)
  - [Azure CLI](https://learn.microsoft.com/es-es/cli/azure/install-azure-cli)

---

## 🚀 ¿Cómo usarlo?

1. Autenticarse en Azure:

```bash
az login

## 🚀 ¿Cómo usarlo?

```bash
# 1. Autenticarse en Azure
az login

# 2. Inicializar el proyecto
terraform init

# 3. Ver el plan de ejecución
terraform plan

# 4. Aplicar los cambios
terraform apply

# 5. (Opcional) Destruir los recursos cuando ya no los necesites
terraform destroy
