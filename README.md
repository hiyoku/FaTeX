# FaTeX
Fatec-SJC Professor Jessen Vidal LaTex Template

### Example of TG using this template:
- Segurança em Redes de IoT - [(DOWNLOAD ZIP)](https://www.dropbox.com/s/2zxeslq247yqsbi/FATEC%20-%20Seguran%C3%A7a%20IOT.zip?dl=0)

### How to edit?
Just use any LaTeX editor like:
- TexMaker
- Texstudio
- Atom (With plugins)
- Visual Studio Code (With plugins)

Or online editor:
- ShareLaTeX

### Commands

#### `\tabela`

To render a table, it's required a title, caption, label and the contents, like so:

```latex
\tabela{<TABULAR>}{<TITLE>}{<CAPTION>}{tab:<LABEL>}
```

> Use `tabularx` for better rendering

##### Example

```latex
\tabela{
  \begin{tabularx}{\textwidth}{|c|X|}
  \hline
  Exemplo de tabela com \texttt{tabularx} & O parâmetro X torna o texto justificado. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Etiam faucibus a massa a iaculis. Praesent vel tempor metus, quis faucibus augue. Suspendisse eget tellus non metus volutpat ultrices. Vestibulum finibus laoreet maximus. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec est purus, volutpat id sapien in, blandit mattis mi. Maecenas accumsan lobortis felis non pharetra. \\ \hline
  \end{tabularx}
}{Título da tabela}{Legenda da tabela}{tab:exemplo}
```

#### `\figura`

To render a figure, it's required a image path, caption and label, like so:

```latex
\figura{<IMAGE_PATH>}{<CAPTION>}{<FONTE>}{tab:<LABEL>}
```

##### Example

```latex
\figura{img/logo-fatec-sjc.jpg}{Exemplo de uso de figura}{Elaborada pelo autor}{fig:logo_fatec_sjc}
```

### Thanks to:
- Diogo Branquinho
- Eduardo Sakaue
- Giuliano Bertoti
- Emanuel Mineda
