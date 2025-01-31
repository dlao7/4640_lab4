**General Setup**

None out of the ordinary.

**Command to make new SSH key pair**

```bash
ssh-keygen -t ed25519 -f ~/.ssh/lab4.key -C "lab 4"
```

**Commands to initialize, fmt, plan**

```bash
terraform init
terraform fmt
terraform plan -out "lab4-plan"
```

**Command to apply**

```bash
terraform apply "lab4-plan"
```
