# 🚀 Laboratório Prático: Arquitetura de Software & DevOps
## Caso: E-commerce & Varejo ("Compre Rápido") - Grupo 1

Repositório da atividade prática de consultoria técnica e arquitetura de sistemas, focada na resolução do gargalo de infraestrutura (queda por saturação de CPU na Black Friday) e implementação de estratégia em nuvem.

---

## 📋 Sobre o Projeto

A atividade simula um cenário real de crise onde o servidor monolítico de um e-commerce caiu devido ao pico de acessos. O objetivo deste repositório é hospedar a documentação e a interface web explicativa da nova arquitetura proposta, conteinerizada via **Docker** e pronta para deploy contínuo.

### 🛠️ Pontos Chave Apresentados na Aplicação:
* **Diagnóstico do Monolito:** Análise das limitações da escala vertical e do Ponto Único de Falha (SPOF).
* **Escalabilidade Horizontal (Scale-Out):** Distribuição de carga com Load Balancer (Nginx).
* **Sharding de Banco de Dados:** Particionamento horizontal para alívio de I/O.
* **Tolerância a Falhas:** Estratégias de alta disponibilidade e recuperação automática.

---

## 🐳 Tecnologias & Ferramentas Utilizadas

* **HTML5, CSS3 & JavaScript:** Interface web interativa e responsiva para apresentação.
* **Nginx (Alpine):** Servidor web leve e de alta performance servido via container.
* **Docker:** Empacotamento e padronização do ambiente.
* **Render:** Plataforma de nuvem utilizada para hospedagem e entrega do link público.

---
