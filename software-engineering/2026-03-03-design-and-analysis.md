# Análise, Design e Modelagem de Software

<br>

## 📌 Análise x Design

### Análise

- Foco em compreender o problema.
- Próxima do mundo real.
- Menor preocupação técnica.
- Classes mais simples e conceituais.
- Representa objetos do domínio.

### Design

- Foco em compreender a solução.
- Aproxima o modelo do ambiente virtual.
- Maior preocupação técnica.
- Classes mais técnicas.
- Refinamentos sucessivos.

### Relação entre Análise e Design

- A análise tende a ser mais ampla.
- O design é mais direcionado.
- O design transforma conceitos da análise em soluções técnicas.
- Objetivo de aproximar o mundo real do mundo artificial.

<br>

## 📌 Modelagem de Software

### Modelagem Estrutural

- Representa estrutura estática.
- Baseada em diagrama de classes.
- Apresenta entidades.
- Apresenta atributos.
- Apresenta métodos.

### Modelagem Comportamental

- Representa comportamento dinâmico.
- Baseada em diagramas de sequência.
- Baseada em diagramas de atividade.
- Mostra interação entre objetos.
- Mostra fluxo de execução.

<br>

## 📌 Ordem de Elaboração dos Diagramas

### Visão de Requisitos

- Diagrama de caso de uso.
- Definição do escopo do sistema.
- Identificação de atores.
- Identificação de funcionalidades.

### Visão de Comportamento

- Diagrama de atividade.
- Modelagem do fluxo de cada caso de uso.
- Representação de etapas.
- Representação de decisões.

### Visão Estrutural

- Diagrama de classes.
- Definição da estrutura estática.
- Definição de entidades.
- Definição de atributos.
- Definição de métodos.

### Ciclo de Vida

- Diagrama de máquina de estados.
- Representação de estados de objetos.
- Definição de transições.
- Definição de eventos.

<br>

## 📌 Diagrama de Sequência

### Função

- Representa interações entre objetos.
- Representa lógica do domínio de negócio.
- Valida métodos dos objetos.
- Aproxima análise e design.

### Papel no Processo

- Etapa intermediária entre análise e design.
- Contribui para validação da lógica do sistema.
- Aproxima o diagrama da implementação.

<br>

## 📌 Programação Síncrona e Assíncrona

### Programação Síncrona

- Execução sequencial de tarefas.
- Chamada de método.
- Espera pelo resultado.
- Execução do próximo método.

### Programação Assíncrona

- Execução paralela de tarefas.
- Tarefas podem ocorrer simultaneamente.
- Múltiplas operações iniciadas ao mesmo tempo.

<br>

## 📌 Perspectivas de Modelagem

### Perspectiva Conceitual

- Representação do domínio do problema.
- Interpretação de situações do mundo real.
- Identificação de objetos do domínio.

### Perspectiva de Especificação

- Descrição de abstrações de software.
- Definição de interfaces.
- Ausência de tecnologia específica.

### Perspectiva de Implementação

- Descrição da implementação do software.
- Uso de tecnologia específica.
- Detalhamento técnico do sistema.

<br>

## 📌 Engenharia Progressiva e Reversa

### Engenharia Progressiva

- Conceitual.
- Especificação.
- Implementação.

### Engenharia Reversa

- Implementação existente.
- Extração da especificação.
- Extração da visão conceitual.

<br>

## ⚙️ Interação entre Objetos

### Colaboração entre Classes

- Classes podem solicitar auxílio de outras classes.
- Objetos colaboram entre si.
- Cada classe executa sua responsabilidade.

### Exemplo Conceitual

- Classe `Jogo` depende da classe `Dado`.
- `Jogo` define a lógica.
- `Dado` fornece valores aleatórios.

### Objeto Protagonista

- Objeto principal de uma operação.
- Solicita operações de outros objetos.

<br>

## ⚙️ Exemplo — Domínio Jogo de Dados

### Objeto Dados

- Lados.

### Objeto Jogo

- Resultados.

### Objeto Jogador

- Nome.
- Pontos.

### Regra de Negócio

- Vitória ao atingir 7 pontos.
- Cada jogador lança o dado 3 vezes.

### Observação de Modelagem

- Jogador pode ser objeto na análise.
- Jogador pode ser ator no design.
- A função define se será ator ou objeto.

<br>

## 💡 Princípio de Design

> “Coisas simples devem ser simples.  
> Coisas complexas devem ser possíveis.”  
> **Alan Kay**

<br>

## ❗ Atenção

- Análise não é implementação.
- Diagramas não substituem código.
- Excesso de modelagem pode atrasar entregas.
- Falta de modelagem gera retrabalho.

<br>

## 🔗 Relacionado

- OOAD
- UML
- Diagrama de Classes
- Caso de Uso
- Engenharia de Software

---