# Análise de Caso de Uso e Objetos em UML

<br>

## 📌 Análise de Caso de Uso

### Objetivo

- Identificar objetos do sistema.
- Análise baseada em descrição textual.
- Compreender o comportamento do sistema.

### Estímulo e Resposta

- Estímulo representa ação do cliente.
- Resposta representa reação do sistema.
- O fluxo alterna entre estímulo e resposta.

### Fluxos de Caso de Uso

- Fluxo principal.
- Fluxos alternativos.
- Fluxos de exceção.

### Fluxo Principal

- Sequência mais direta de execução.
- Caminho principal do sistema.
- Da primeira até a última operação.

### Fluxos Alternativos

- Caminhos secundários de execução.
- Representam variações do comportamento do sistema.
- Exploram outras funcionalidades.

### Fluxos de Exceção

- Tratamento de erros.
- Validações do sistema.
- Restrições de permissão.

<br>

## 📌 Objetos Conceituais

### Definição

- Objetos pertencentes ao modelo de negócios.
- Representam elementos do domínio do problema.
- Identificados durante a análise do sistema.

<br>

## 📌 Classes do Domínio

### Função

- Manipulação de informações do domínio.
- Representação das entidades principais do sistema.
- Tratamento geral de dados.

### Classe Cliente

- CNH.
- CPF.
- Nome.
- Nascimento.
- `getCpf()`
- `getCnh()`
- `getIdade()`

### Classe Carro

- Placa.
- Modelo.
- Cor.
- Disponibilidade.
- `getDisponibilidade()`

### Classe Locação

- Início.
- Fim.
- Valor.
- `agendarReserva()`

<br>

## 📌 Relações entre Classes

### Cliente → Locação

- Solicitar reserva.

### Carro → Locação

- Verificar disponibilidade.

<br>

## 📌 Atributo Derivado

### Definição

- Atributo calculado a partir de outros dados.
- Valor pode ser recalculado quando necessário.
- Não exige armazenamento permanente.

<br>

## ⚙️ Tipos de Objetos em UML

### Objetos de Entidade

- Representam dados do domínio.
- Armazenam informações do sistema.

### Objetos de Controle

- Controlam comportamento da aplicação.
- Coordenam fluxo de operações.
- Surgem quando entidades ficam muito extensas.
- Centralizam lógica de execução.

### Objetos de Fronteira

- Responsáveis pela interface do sistema.
- Comunicação entre usuário e aplicação.
- Geralmente implementados em APIs.
- Geralmente implementados em interfaces de usuário.

<br>

## 💡 Observações Importantes

- Separar entidades, controle e fronteira melhora organização.
- Casos de uso ajudam a descobrir responsabilidades.
- Objetos conceituais surgem antes do código.
- Bons fluxos reduzem ambiguidades.

### Criador dos Conceitos

- **Ivar Jacobson**.

<br>

## ❗ Atenção

- Não confundir caso de uso com tela.
- Nem todo objeto conceitual vira classe final.
- Entidades com regras demais podem precisar de objetos de controle.
- Fluxos de exceção são essenciais.

<br>

## 🔗 Relacionado

- UML
- Caso de Uso
- Diagrama de Classes
- OOAD
- Engenharia de Requisitos

---