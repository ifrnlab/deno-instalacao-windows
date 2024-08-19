# Como testar no VS Code?

1. Instale a extensão `Deno` de DenoLand. Em um terminal[^1], execute:

    - `code --install-extension denoland.vscode-deno`

2. Abra uma pasta[^2] e crie um arquivo do TypeScript (Extensão `.ts`).
3. Abra a paleta de comandos[^3] e execute: `Deno: enable`
4. Digite o código que você deseja testar no arquivo.
5. Retorne para o terminal e execute os seguintes comandos:

    1. Descubra seu diretório de trabalho. Execute:

        - `pwd`

    2. Liste os arquivos `.js` ou `.ts` do diretório de trabalho:

        - `ls *.ts`

    3. Escolha o ARQUIVO a ser lido pelo `deno` e execute:

        - `deno run ARQUIVO.ts`


[^1]: Menu: Ver -> Terminal (Teclas `Ctrl`+`'`)
[^2]: Menu: Arquivo -> Abrir Pasta (Teclas `Ctrl+K`, `Ctrl+O`)
[^3]: Menu: Ver -> Paleta de comandos (Teclas `Ctrl+Shift+P`)
