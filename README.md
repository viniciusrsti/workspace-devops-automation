# workspace-devops-automation
Estrutura de pastas 

├── .github/
│   └── workflows/
│       └── pipeline.yml       # pipeline CI/CD (GitHub Actions)
├── terraform/
│   ├── main.tf                # Código principal da infra (VPC, EC2, SG)
│   ├── outputs.tf             # Saída do IP público da EC2
│   └── provider.tf            # Configuração do provedor AWS
├── ansible/
│   ├── playbook.yml           # Instalação do Docker e Deploy da App Java
│   └── templates/
│       └── docker-compose.yml # Se optar por rodar via compose na EC2
└── README.md                  # Documentação do laboratório