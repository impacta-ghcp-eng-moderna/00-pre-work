## 🚀 Como iniciar seu Codespace

[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/{{ repository }}?quickstart=1)

1. Clique no badge acima (ou vá em **Code → Codespaces → Create codespace on main**).
2. Aguarde o Codespace terminar de construir o ambiente (o `devcontainer` instala o .NET 10 automaticamente).
3. Inicie a aplicação de uma das formas abaixo:

   - **Opção A -- pressione `F5`** (recomendado). O projeto já vem com uma configuração de
     debug pronta (`.vscode/launch.json`), então o VS Code compila e inicia a aplicação com
     o debugger conectado automaticamente.
   - **Opção B -- pelo terminal**, rode:
     ```bash
     dotnet run --project src/PreWork
     ```
     > [!WARNING]
     > Se você iniciar pelo terminal, o **debugger do VS Code não vai se conectar** --
     > você não conseguirá usar breakpoints. Além disso, enquanto a aplicação estiver
     > rodando no terminal, ele fica ocupado; para rodar qualquer outro comando nele
     > (ou tentar iniciar a aplicação de novo), primeiro pare o processo com `Ctrl+C`.
4. Quando o VS Code perguntar, clique em **Abrir no navegador** (ou abra a porta encaminhada `5075` na aba **Ports**).
5. Você deve ver uma página comemorando o sucesso do seu ambiente. 🎉

### ✅ Terminou?

Quando ver a página de sucesso, **comente nesta issue com a palavra `concluído`**.
Você vai receber as instruções de como limpar o ambiente (remover o Codespace e o repositório)
para evitar uso desnecessário de recursos.
