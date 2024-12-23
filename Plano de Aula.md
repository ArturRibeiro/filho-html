
# Plano de Aula Completo: HTML - Do Simples ao Avançado

---

## **Objetivo Geral**
Fornecer aos alunos uma compreensão completa de HTML, desde os fundamentos até conceitos avançados, permitindo a criação de páginas web responsivas e estruturadas.

---

## **Estrutura do Plano de Aula**
### Duração Total
- **8 horas** divididas em 4 módulos.
- Cada módulo pode ser adaptado conforme a necessidade dos alunos.

### Módulos:
1. Introdução ao HTML e Estrutura Básica.
2. Formatação e Elementos Multimídia.
3. Formulários e Tabelas.
4. Conceitos Avançados e Acessibilidade.

---

## **Conteúdo Detalhado**

### **Módulo 1: Introdução ao HTML e Estrutura Básica**
#### **Objetivo**
Ensinar a estrutura básica de um arquivo HTML e conceitos fundamentais.

#### **Tópicos**
1. O que é HTML e sua importância.
2. Estrutura básica:
   - `<!DOCTYPE>`
   - `<html>`
   - `<head>` e `<body>`
3. Títulos e parágrafos: `<h1>` a `<h6>`, `<p>`.
4. Comentários: `<!-- -->`

#### **Exemplo**
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

#### **Atividade**
- Criar uma página com título, subtítulos e parágrafos descritivos.

---

### **Módulo 2: Formatação e Elementos Multimídia**
#### **Objetivo**
Ensinar como adicionar estilos básicos, links, imagens e listas.

#### **Tópicos**
1. Tags de formatação: `<strong>`, `<em>`, `<u>`.
2. Links: `<a href="url">Texto</a>`.
3. Imagens: `<img src="url" alt="descrição">`.
4. Listas ordenadas e não ordenadas: `<ol>`, `<ul>`, `<li>`.

#### **Exemplo**
```html
<body>
    <h2>Minha Lista de Links</h2>
    <ul>
        <li><a href="https://example.com">Exemplo</a></li>
        <li><a href="https://outrasite.com">Outro Site</a></li>
    </ul>
    <img src="imagem.jpg" alt="Uma imagem de exemplo">
</body>
```

#### **Atividade**
- Criar uma página com links, uma lista e uma imagem.

---

### **Módulo 3: Formulários e Tabelas**
#### **Objetivo**
Ensinar a criação de formulários interativos e tabelas estruturadas.

#### **Tópicos**
1. Elementos de formulário: `<form>`, `<input>`, `<textarea>`, `<button>`, `<select>`.
2. Tabelas: `<table>`, `<tr>`, `<td>`, `<th>`, `<caption>`.
3. Atributos importantes: `action`, `method`, `placeholder`.

#### **Exemplo**
```html
<form action="/enviar" method="post">
    <label for="nome">Nome:</label>
    <input type="text" id="nome" name="nome" placeholder="Digite seu nome">
    <button type="submit">Enviar</button>
</form>
```

#### **Atividade**
- Criar um formulário de contato com campos de nome, e-mail e mensagem.
- Criar uma tabela com dados fictícios organizados em linhas e colunas.

---

### **Módulo 4: Conceitos Avançados e Acessibilidade**
#### **Objetivo**
Explorar técnicas avançadas e boas práticas de acessibilidade.

#### **Tópicos**
1. Estrutura semântica: `<header>`, `<footer>`, `<section>`, `<article>`, `<aside>`.
2. Atributos globais: `id`, `class`, `data-*`.
3. Introdução ao CSS inline: `style=""`.
4. Boas práticas de acessibilidade:
   - Uso de atributos `alt` em imagens.
   - Títulos descritivos.
   - Elementos focáveis e navegáveis por teclado.

#### **Exemplo**
```html
<header>
    <h1>Blog de Tecnologia</h1>
</header>
<section>
    <article>
        <h2>Postagem Recente</h2>
        <p>Este é um artigo sobre HTML semântico.</p>
    </article>
</section>
<footer>
    <p>&copy; 2024 Blog de Tecnologia</p>
</footer>
```

#### **Atividade**
- Criar uma página com estrutura semântica.
- Adicionar estilos básicos utilizando atributos inline.

---

## **Conclusão do Plano**
- Revisar os conceitos apresentados.
- Propor um projeto final: criar uma página completa com todos os elementos abordados.
- Fornecer recursos para estudos adicionais (MDN Web Docs, W3Schools).

---

## **Materiais Necessários**
- Computadores com editores de código (VS Code ou similar).
- Navegadores atualizados.
- Recursos online para consulta (MDN, W3Schools).

---

## **Recursos Adicionais**
- [MDN Web Docs - HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [W3Schools - HTML](https://www.w3schools.com/html/)
