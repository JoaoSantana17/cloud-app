# Role – FastAPI + Docker + Azure VM

> **Deployment em Nuvem utilizando Docker, Docker Compose e Azure VM.**  
> Projeto desenvolvido para a disciplina

---

## Visão Geral

O objetivo deste projeto é **demonstrar o deployment de uma aplicação containerizada** em uma **máquina virtual no Azure**, garantindo:
- Execução em background via Docker Compose;
- Monitoramento pelo Azure Insights;
- Criação e execução por **usuário não-root**;
- Persistência de dados e execução automatizada.

A aplicação é uma **API simples em FastAPI**, simulando parte da arquitetura demo do projeto “Rolê”.

---

## Estrutura de Diretórios

role-docker/
│
├── app/
│ └── main.py # Código principal da aplicação (FastAPI)
│ └── requirements.txt # Dependências da aplicação
│
├── Dockerfile # Instruções de build da imagem Docker
│
├── docker-compose.yml # Orquestração do container
│
└── README.md # Documentação do projeto


---

## Etapas do Deployment

### 1. Criação da VM no Azure

- **Sistema operacional:** Ubuntu 22.04 LTS  
- **Portas liberadas:**  
  - `22` → SSH  
  - `80` → Aplicação  


# Link para o video do YouTube: 

# Créditos

Integrantes do grupo:

Adão Yuri Ferreira da Silva - RM559223
João Vitor Lopes Santana - RM560781

Curso: Análise e Desenvolvimento de Sistemas – FIAP

