# Plug n' Brain — downloads

Um segundo cérebro no seu computador: você joga arquivos, prints e notas numa caixa de texto,
acha o trecho certo com a fonte e pluga o mesmo cérebro no Claude, no ChatGPT/Codex e no Cursor
do seu computador. Tudo fica com você.

Este repositório guarda só as versões prontas para baixar. Um produto Gravidade Zero.

## Baixar

[**Baixar para Windows (versão mais nova)**](https://github.com/Artur-Antunes-1/plugnbrain-downloads/releases/latest/download/PlugNBrain-Windows-x64.zip) · [todas as versões](https://github.com/Artur-Antunes-1/plugnbrain-downloads/releases)

Windows 10 ou 11, 64 bits. O Mac vem numa próxima versão.

## Instalar

1. Baixe o zip e extraia onde quiser (por exemplo, em Documentos).
2. Abra a pasta `Plug n' Brain` e dê dois cliques em `Plug n' Brain.exe`.
3. Jogue o primeiro arquivo na caixa.

**O Windows vai avisar na primeira vez.** O app ainda não tem assinatura digital (ela vem numa
próxima versão). Na tela azul, clique em **Mais informações** e depois em **Executar assim mesmo**.

Se o seu Windows 11 tem o **Controle Inteligente de Aplicativos** ligado, ele bloqueia apps sem
assinatura e não oferece essa opção: nesse caso, o Plug n' Brain ainda não roda nesse computador.

## Conferir o arquivo

Cada versão traz um `SHA256SUMS.txt`. No PowerShell:

```powershell
Get-FileHash .\PlugNBrain-Windows-x64.zip -Algorithm SHA256
```

O resultado tem que ser igual ao do `SHA256SUMS.txt` da versão.

## Onde ficam seus dados

Em `C:\Users\<você>\.plugnbrain`. Para desinstalar, feche o app e apague a pasta do app; para
apagar também o cérebro, apague a pasta `.plugnbrain`. Antes, se quiser, use "Exportar tudo" no app.
