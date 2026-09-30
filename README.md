# Página de redes sociais

Projeto de estudo do Curso em Vídeo para apresentar páginas de redes sociais em uma composição visual com iframe.

## Tecnologias e funcionalidades

**HTML5 e CSS3**

- Navegação entre páginas locais de demonstração.
- Composição com imagens e iframe.

## Como executar

Requisitos: navegador moderno. Para o servidor local abaixo, Python 3.

```sh
git clone https://github.com/FilipeBandeira/projeto-social.git
cd projeto-social
python3 -m http.server 8000
```

Abra `http://localhost:8000`. O servidor local apenas entrega os arquivos estáticos.

## Organização

- `index.html`: navegação principal.
- `home.html`, `github.html` e outras páginas: conteúdo do iframe.
- `estilos/` e `imagens/`: recursos.

## Escopo

Projeto educacional que registra a prática de desenvolvimento web. Recursos de terceiros, como fontes e conteúdo incorporado, podem exigir internet.
## Autor e licença

[Filipe Bandeira](https://github.com/FilipeBandeira). Consulte o arquivo [LICENSE](LICENSE) para os termos do repositório. Materiais e marcas de terceiros mantêm seus respectivos direitos.
