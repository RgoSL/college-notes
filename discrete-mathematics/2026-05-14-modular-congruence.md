# Congruência Modular

## 📌 Conceitos Principais

### Definição
- Dois números inteiros são **congruentes módulo m** quando deixam o **mesmo resto** na divisão por `m`.

- Representação:

`a ≡ b (mod m)`

- Leitura:
  - **a é congruente a b módulo m**

- Significado:
  - `a ÷ m` e `b ÷ m` possuem o mesmo resto  

<br>

## ⚙️ Funcionamento / Estrutura

### Exemplo 1
Verificar se **27 é congruente a 15 módulo 6**:

- `27 ÷ 6 = 4`, resto **3**
- `15 ÷ 6 = 2`, resto **3**

Como os restos são iguais:

`27 ≡ 15 (mod 6)`

---

### Exemplo 2 — Dia da Semana
Hoje é **quinta-feira**. Daqui a **250 dias**, qual será o dia?

- Uma semana possui `7` dias

`250 ÷ 7 = 35`, resto **5**

Logo:

`250 ≡ 5 (mod 7)`

Somamos **5 dias** a partir de quinta:

- sexta (+1)  
- sábado (+2)  
- domingo (+3)  
- segunda (+4)  
- terça (+5)  

**Resultado → terça-feira**

---

### Exemplo 3 — Potência Modular
Calcular o resto de:

`2^50 ÷ 6`

Queremos:

`2^50 (mod 6)`

#### Passo 1
Sabemos que:

`2³ = 8`

Como:

`8 ≡ 2 (mod 6)`

Então podemos substituir:

`(2³)^16 ≡ 2^16 (mod 6)`

---

#### Passo 2
Reescrevendo:

`2^50 = 2^48 * 2²`

Logo:

`2^50 ≡ (2³)^16 * 4 (mod 6)`

Substituindo:

`≡ 8^16 * 4 (mod 6)`

Como:

`8 ≡ 2 (mod 6)`

Então:

`≡ 2^16 * 4 (mod 6)`

---

#### Passo 3
Reduzindo sucessivamente:

`2^16 ≡ 2 (mod 6)`

Logo:

`2^50 ≡ 2 * 4 (mod 6)`

`2^50 ≡ 8 (mod 6)`

Como:

`8 ≡ 2 (mod 6)`

Refazendo corretamente pela sequência:

`2^50 ≡ 4 (mod 6)`

**Resto = 4**

<br>

## 💡 Observações Importantes
- Em congruência modular, **somente o resto importa**.
- Podemos substituir números por equivalentes menores usando `≡`.
- Muito usado em criptografia, calendários e algoritmos.

<br>

## ❗ Atenção
- Não confundir **igualdade (`=`)** com **congruência (`≡`)**.
- `a ≡ b (mod m)` não significa que `a = b`.
- Significa apenas que possuem o mesmo resto módulo `m`.

<br>

## 🔗 Relacionado
- Matemática Discreta  
- Divisão Euclidiana  
- Aritmética Modular  
- Teoria dos Números  

---