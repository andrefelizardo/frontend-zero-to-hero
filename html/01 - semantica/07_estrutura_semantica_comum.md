---
marp: true
---

## Quais são as estruturas semânticas mais comuns?

```html
<body>
  <header>
    <!-- Cabeçalho da página -->
  </header>
  <nav>
    <!-- Menu de navegação -->
  </nav>
  <main>
    <section>
      <!-- Seção de conteúdo -->
    </section>
    <article>
      <!-- Artigo ou post -->
    </article>
    <aside>
      <!-- Conteúdo complementar -->
    </aside>
  </main>
  <footer>
    <!-- Rodapé da página -->
  </footer>
</body>
```

---

# Erros comuns em estruturas (não) semânticas

- **Uso excessivo de `<div>`e `<span>`**: Utilizar essas tags genéricas para tudo, sem considerar o significado do conteúdo.
- **Ignorar a hierarquia de títulos**: Pular níveis de `<h1>`para `<h3>`, por exemplo, sem uma ordem lógica.
- **Não utilizar tags apropriadas**: Deixar de usar `<nav>`para menus ou `<footer>` para rodapés, opotando por `<div>` genéricos.
- **Misturar conteúdo semântico com apresentação**: Utilizar tags para estilização ao invés de significado, como usar `<b>` para negrito sem considerar o contexto.
