# Multiplataforma no React Native

<br>

## 📌 Multiplataforma

### Arquivos por Plataforma

- Uso de `index.android.tsx`  
- Uso de `index.ios.tsx`  
- Uso de `index.web.tsx`  
- Separação de implementação por sistema  

### Identificação de Plataforma

- Uso do `Platform`  
- Identifica o sistema operacional  
- Permite lógica condicional  

### Padronização de Componentes

- Uso de `interface`  
- Garante consistência entre plataformas  
- Define estrutura comum  

<br>

## 📌 Tipagem e Componentes

### React.FC

- Tipagem de componentes  
- Permite definição de props  
- Melhora organização  

### Props Opcionais

- Uso de `?:`  
- Define propriedades opcionais  
- Permite `undefined` ou ausência  

<br>

## 📌 Gerenciamento de Estado e Ações

### onClose()

- Função para fechamento de elementos  
- Usada em componentes interativos  
- Aplicada em modais e alerts  

### Elemento Alert

- Possui mensagem  
- Possui título  
- Define tipo/comportamento  
- Controle de visibilidade  

<br>

## 📌 Organização de Constantes

### Pasta constants

- Armazena valores fixos  
- Centraliza configurações  
- Facilita manutenção  

### Configuração de Cores

- Definidas em constantes  
- Organizadas em objetos  
- Permitem padronização  

### Padrão de Cores

- Exemplo: `blue`  
- `100` → tom mais claro  
- `200` → tom mais escuro  
- Facilita reutilização  

<br>

## 💡 Observações

- Separação por plataforma melhora escalabilidade  
- Tipagem fortalece segurança do código  
- Constants evitam repetição  

<br>

## ❗ Atenção

- Evitar duplicação excessiva entre plataformas  
- Garantir consistência entre versões  
- Uso incorreto de tipos pode gerar erros difíceis  

<br>

## 🔗 Relacionado

- React Native  
- TypeScript  
- Componentização  
- Mobile Development  
- Boas práticas de código  

---