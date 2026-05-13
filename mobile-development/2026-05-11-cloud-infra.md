# Cloud e Docker

<br>

## 📌 Docker

- Ferramenta para hospedagem e execução de containers  
- Baseado em sistemas Unix/Linux  
- Dependente do sistema operacional hospedeiro  
- Facilita isolamento de aplicações  

### Containers

- Simulam ambientes isolados  
- Executam aplicações de forma independente  
- Compartilham o kernel do sistema hospedeiro  
- Mais leves que máquinas virtuais  

### Virtual Machine (VM)

- Emulação completa de máquina física  
- Possui sistema operacional próprio  
- Consome mais recursos que containers  

<br>

## 📌 Servidores

- Responsáveis pela hospedagem da aplicação  
- Geralmente utilizam Linux  
- Executam aplicações como sites e APIs  

### Requisições

- Comunicação por portas  
- Uso comum de HTTP/HTTPS  
- Cliente envia requisição ao servidor  

### Balanceador de Carga

- Distribui requisições entre servidores  
- Evita sobrecarga  
- Melhora disponibilidade e desempenho  

<br>

## ⚙️ Escalabilidade com Docker

- Containers podem ser replicados automaticamente  
- Escalonamento baseado em demanda  
- Exemplo: uso acima de 80% pode gerar novo container  

<br>

## 📌 Provedores de Nuvem

- AWS :contentReference[oaicite:0]{index=0}  
- Azure :contentReference[oaicite:1]{index=1}  
- Google Cloud :contentReference[oaicite:2]{index=2}  
- Alibaba Cloud :contentReference[oaicite:3]{index=3}  

<br>

## 📌 Serverless (Lambda)

- Execução sem gerenciamento direto de servidor  
- Infraestrutura gerenciada pelo provedor cloud  
- Necessário definir:
  - Memória
  - Ambiente/SO
  - Tempo de execução  

### Funcionamento

- Servidor inicia sob demanda  
- Não precisa ficar ativo 24/7  
- Ideal para eventos e APIs  

<br>

## 📌 GraalVM

- Executa aplicações Java de forma nativa  
- Compila código para binário específico do SO  
- Reduz tempo de inicialização  
- Muito útil em ambientes serverless  

<br>

## 💡 Observações

- Docker melhora portabilidade  
- Containers são mais leves que VMs  
- Serverless reduz custo operacional  

<br>

## ❗ Atenção

- Container não é máquina virtual  
- Docker depende do SO hospedeiro  
- Serverless pode sofrer com *cold start*  

<br>

## 🔗 Relacionado

- Docker  
- Cloud Computing  
- Linux  
- Serverless  
- DevOps  

---