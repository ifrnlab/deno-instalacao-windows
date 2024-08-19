# Como testar no VS Code?

1. Abra o VS Code[^1]
2. Instale a extensão `Deno` de DenoLand. Em um terminal[^2], execute:

    - `code --install-extension denoland.vscode-deno`

3. Abra uma pasta[^3] e crie um arquivo do TypeScript (Extensão `.ts`).
4. Abra a paleta de comandos[^4] e execute: `Deno: enable`
5. Digite o código que você deseja testar no arquivo.
6. Retorne para o terminal e execute os seguintes comandos:

    1. Descubra seu diretório de trabalho. Execute:

        - `pwd`

    2. Liste os arquivos `.js` ou `.ts` do diretório de trabalho:

        - `ls *.ts`

    3. Escolha o ARQUIVO a ser lido pelo `deno` e execute:

        - `deno run ARQUIVO.ts`

[^1]: Caso ele ainda não esteja instalado, abra o PowerShell e execute: `winget install --id Microsoft.VisualStudioCode`
[^2]: Menu: Ver -> Terminal (Teclas `Ctrl`+`'`)
[^3]: Menu: Arquivo -> Abrir Pasta (Teclas `Ctrl+K`, `Ctrl+O`)
[^4]: Menu: Ver -> Paleta de comandos (Teclas `Ctrl+Shift+P`)
