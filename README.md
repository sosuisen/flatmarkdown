# flatmarkdown

Markdown parser library for PetaJournal. Wraps [comrak](https://github.com/kivikakk/comrak) with PetaJournal-specific options pre-configured.

## API

- `markdown_to_html(input: &str) -> String` — Convert Markdown to HTML
- `markdown_to_ast(input: &str) -> String` — Convert Markdown to JSON AST ([spec](SPEC.md))

## Testing

```sh
cargo test
```
