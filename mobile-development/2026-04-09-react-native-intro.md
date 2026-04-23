# Fundamentos do React Native

<br>

## 📌 Compilação Multiplataforma

- Suporte para Android  
- Suporte para iOS  
- Suporte para Web  
- Necessidade de adaptação para responsividade  
- Empacotamento pode variar por plataforma  

### Responsividade

- Uso de condições por sistema operacional  
- Estilos diferentes por plataforma  
- Não é automaticamente responsivo  

<br>

## 📌 Estrutura de Projeto

### Organização de Pastas

- Criar pasta `src`  
- Criar `components` dentro de `src`  
- `components` armazena elementos reutilizáveis  
- Evitar colocar views dentro de `components`  

### Estrutura de Componente

- Criar pasta específica por componente  
- Exemplo: `button`  
- Criar `index.tsx` dentro da pasta  
- Componente representa estrutura reutilizável  

<br>

## 📌 Criação de Componentes

### Componente Button

- Criado dentro de `components`  
- Exportação default  
- Utilizado após importação  

### Importação de Componentes

- Necessário importar na tela principal  
- Pode usar alias para simplificar caminhos  

### Alias de Caminhos

- Configurado no `tsconfig.json`  
- Exemplo: `"@/*": ["./src/*"]`  
- Substitui caminhos longos  

<br>

## 📌 Props e Reutilização

### Props em Componentes

- Permitem valores dinâmicos  
- Exemplo: `title` em botão  
- Aumentam reutilização  

### Props de Estilo

- Customização visual  
- Podem ser opcionais  
- Uso de valores padrão  

### Parâmetro Rest

- Uso de `...rest`  
- Repassa propriedades automaticamente  
- Evita repetição de código  

<br>

## 📌 Estilização

### TS e TSX

- TS → lógica e estilos  
- TSX → estrutura (UI)  

### StyleSheet

- Utilizado para estilização  
- Semelhante ao CSS  
- Estilos organizados em objetos  

<br>

## 📌 Interação e UI

### TouchableOpacity

- Efeito visual de clique  
- Muito usado em botões  
- Necessário importar  

<br>

## ⚙️ Navegação

### Router

- Controla navegação entre telas  
- Gerencia fluxo da aplicação  
- Base para apps multi-tela  

<br>

## 💡 Ferramentas de Teste

### Genymotion

- Emulador Android  
- Criação de dispositivos virtuais  
- Testes de aplicações mobile  

<br>

## ❗ Atenção

- Componentes devem ser reutilizáveis  
- Evitar acoplamento entre telas e componentes  
- Responsividade precisa ser tratada manualmente  
- Organização de pastas impacta manutenção  

<br>

## 🔗 Relacionado

- React Native  
- TypeScript  
- Componentização  
- Mobile Development  
- UI/UX  

---