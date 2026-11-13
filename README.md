# Homebrew tap — wired-magic

Binários macOS (Apple Silicon e Intel, macOS 14+) do
[wired-magic](https://github.com/CaioFaSoares/wired-magic-tools).

## Instalar

```sh
brew tap CaioFaSoares/tap
brew install CaioFaSoares/tap/wired-magic
wm --version
```

A formula `Formula/wired-magic.rb` é gerada e enviada por
`scripts/publish_macos.sh` no repositório de origem; não edite os checksums à mão.

## Atualizar

A TUI instalada pelo tap verifica o Homebrew ao abrir e instala versões novas em
segundo plano. A versão nova passa a valer na próxima abertura, sem derrubar a
sessão ou o agente atual. Para atualizar manualmente:

```sh
brew update
brew upgrade CaioFaSoares/tap/wired-magic
```

Não execute Homebrew como root. Consulte
[docs/homebrew.md](https://github.com/CaioFaSoares/wired-magic-tools/blob/main/docs/homebrew.md)
para publicação, arquiteturas e solução de problemas.
