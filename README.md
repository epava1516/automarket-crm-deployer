# automarket-crm-deployer
Punto central que recoge el despliegue de cada componente de este proyecto

# Despliegue de imagenes
Para el despliegue pasaremos por un proceso de construccion en las correspondientes máquinas

## Build
Para la construcción de las imagenes utilizaremos el siguiente comando

```bash
ansible-playbook build.yml --tag ["marketplace", "crm", "api", "front"]
```
Eligiendo entre los correspondientes tags que se deseen `compilar`.