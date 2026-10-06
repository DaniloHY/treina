# Instruções

- Clone o repositório
- Obtenha minha chave pública via WKD (contato@ehcode42.net.br)
- Crie um projeto em Zig
  - Deve haver um arquivo mise.toml com entrada para versão 0.16.0 do Zig
  - Crie apenas o arquivo main.zig
  - Imprima seu nome completo na tela, sem usar a função de debug (std.debug.print)
- Assine seu .zig
- Crie um pacote seu-nome-completo.tar.gz (zipado) contendo:
  - main.zig
  - mise.toml
  - assinatura digital do main.zig
  - sua chave pública em formato binário
  - **ATENÇÃO:** os arquivos devem ser estar em um pasta nomeada **src**
- Criptografe seu tarball (arquivo tar.gz) com minha chave pública
- Submeta seu código via Pull Request assinado
