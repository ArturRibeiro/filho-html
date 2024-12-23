
# Aula: **Introdução ao HTML - Estrutura Básica de um Arquivo HTML**

---

## **Objetivo da Aula**
Apresentar a estrutura básica de um arquivo HTML e explicar a função de cada elemento essencial.

---

## **Conteúdo da Aula**

### 1. **O que é HTML?**
- **Significado:** *HyperText Markup Language*.
- **Função:** Criar a estrutura e o conteúdo de páginas web.
- **Como funciona:** Navegadores interpretam o código HTML para exibir páginas.

---

## **Estrutura Básica de um Arquivo HTML**
Todo arquivo HTML segue uma estrutura básica, composta pelas seguintes partes:

### **1. Declaração do Tipo de Documento**
```html
<!DOCTYPE html>
```
- Indica ao navegador que o arquivo está usando HTML5.

---

### **2. A Tag `<html>`**
```html
<html>
</html>
```
- Contém todo o conteúdo da página.
- É a raiz do documento HTML.

---

### **3. O Cabeçalho (`<head>`)**
```html
<head>
</head>
```
- Fornece informações sobre a página (não visíveis ao usuário).
- Exemplos de uso:
  - Definir o título da página.
  - Vincular arquivos CSS e scripts.

---

### **4. O Corpo (`<body>`)**
```html
<body>
</body>
```
- Contém o conteúdo visível da página, como textos, imagens, links, etc.

---

## **Exemplo Completo de Estrutura**
```html
<!DOCTYPE html>
<html>
<head>
    <title>Minha Primeira Página</title>
</head>
<body>
    <h1>Bem-vindo ao HTML</h1>
    <p>Esta é a estrutura básica de um arquivo HTML.</p>
</body>
</html>
```

---

## **Explicação Detalhada**
1. **`<!DOCTYPE html>`**
   - Garante compatibilidade com navegadores modernos.

2. **`<html>`**
   - Elemento pai de todo o código HTML.

3. **`<head>`**
   - O `<title>` define o texto exibido na aba do navegador.
   - Outras informações, como meta-tags, podem ser adicionadas aqui.

4. **`<body>`**
   - Contém os elementos que aparecerão na página, como:
     - Cabeçalhos (`<h1>`, `<h2>`, etc.).
     - Parágrafos (`<p>`).
     - Imagens (`<img>`).
     - Links (`<a>`).

---

## **Atividade Prática**
1. Crie um arquivo chamado `index.html`.
2. Insira o código básico:
   ```html
   <!DOCTYPE html>
   <html>
   <head>
       <title>Minha Página HTML</title>
   </head>
   <body>
       <h1>Introdução ao HTML</h1>
       <p>Este é o meu primeiro parágrafo em HTML!</p>
   </body>
   </html>
   ```
3. Abra o arquivo em um navegador para visualizar a página.

---

## **Perguntas para os Alunos**
1. Qual é a função do `<head>`?
2. O que acontece se removermos o `<body>`?
3. Qual elemento define o título da aba do navegador?

---

## **Encerramento**
- Resuma a estrutura básica.
- Explique que o próximo passo será aprender mais tags e estilos.
- **Desafio:** Adicione mais um parágrafo e um subtítulo na sua página.
