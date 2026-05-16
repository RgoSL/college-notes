# Design Patterns

<br>

## 📌 Conceitos

**Design Patterns**
- Padrões de projeto para organização e desenvolvimento de código.
- Soluções reutilizáveis para problemas recorrentes em software.
- Melhoram manutenção, reutilização e escalabilidade.

### GoF (Gang of Four)
- Grupo responsável pela formalização dos principais padrões de projeto.
- Define **23 padrões clássicos**.
- Organizados em **3 categorias principais**:
  - Criacionais
  - Estruturais
  - Comportamentais

<br>

## ⚙️ Funcionamento

### Criacionais
- Relacionados à criação de objetos.
- Definem formas eficientes de instanciar classes.
- Reduzem acoplamento na criação.

**Exemplo: Singleton**
- Garante uma única instância de um objeto.
- Possui acesso global controlado.

**Uso comum:**
- Configurações globais.
- Conexão com banco de dados.
- Logs.

---

### Estruturais
- Relacionados à organização e composição de classes/objetos.
- Melhoram flexibilidade do sistema.
- Facilitam integração entre partes diferentes.

**Exemplo: Adapter**
- Atua como ponte entre sistemas incompatíveis.
- Muito usado em integração com APIs externas.

**Uso comum:**
- Integração de serviços externos.
- Compatibilidade entre bibliotecas.

---

### Comportamentais
- Relacionados à comunicação entre classes.
- Definem responsabilidades e fluxo de ações.

**Exemplos:**
- **Strategy** → define diferentes estratégias para executar uma ação.
- **Observer** → monitora eventos e dispara ações quando algo ocorre.

**Uso comum:**
- Eventos.
- Notificações.
- Regras dinâmicas de negócio.

<br>

## 💡 Observações

- Design Patterns não são código pronto.
- São modelos de solução reutilizáveis.
- Melhoram legibilidade e organização do projeto.
- Devem ser aplicados quando fazem sentido.

<br>

## ❗ Atenção

- Evitar uso excessivo de padrões sem necessidade.
- Aplicar pattern errado pode aumentar complexidade.
- Primeiro entender o problema, depois escolher o padrão.

<br>

## 🔗 Relacionado

- Programação Orientada a Objetos
- Arquitetura de Software
- Clean Code
- SOLID

---