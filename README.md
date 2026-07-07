# Sennett. — Releases

> 🇧🇷 [Versão em português logo abaixo.](#sennett--releases-pt-br)

**Sennett** is a meeting-reminder app that makes sure you never miss a meeting — with timely, escalating alerts on your devices. This repository hosts the **official release assets for the Sennett macOS app** distributed outside the Mac App Store (DMG + auto-update packages).

- Website: [sennett.app](https://sennett.app) (English) · [sennett.com.br](https://sennett.com.br) (português)

## Download the latest stable version

Grab the newest stable build from the latest release page:

**→ [Latest release](https://github.com/lumebuild/sennett_releases/releases/latest)**

Download the `.dmg` asset, open it, and drag **Sennett** into your Applications folder. Direct links follow the pattern `https://github.com/lumebuild/sennett_releases/releases/latest/download/<asset-name>` — the DMG asset name is stable per channel, so that link always points at the newest stable DMG.

> **No releases yet?** The app is on its way — releases will appear here soon. Check [sennett.app](https://sennett.app) for launch news.

The app updates itself automatically once installed (powered by [Velopack](https://velopack.io)); you normally only need the DMG for the first install.

## Beta / pre-releases

Release candidates are published here as **GitHub pre-releases** on the `beta` channel, ahead of each stable version. They are intended for testers:

- Marked **Pre-release** on the [releases page](https://github.com/lumebuild/sennett_releases/releases).
- May contain bugs — install them only if you want to try what's next and don't mind the rough edges.
- Beta installs update along the beta channel; to return to stable, install the latest stable DMG.

## What's in this repository

Only release **assets and docs** — no source code:

- `.dmg` installers and portable packages per release
- Velopack full/delta update packages and per-channel feed indexes (`releases.<channel>.json`)
- The [release-notes template](.github/release-notes-template.md) our publish workflow stamps onto each release

Sennett's **source code lives in a private repository**. Issues and pull requests here are not monitored for app development.

---

<a id="sennett--releases-pt-br"></a>

# Sennett. — Releases (pt-BR)

O **Sennett** é um aplicativo de lembretes de reunião que garante que você nunca perca uma reunião — com alertas pontuais e escalonados nos seus dispositivos. Este repositório hospeda os **ativos oficiais de lançamento do aplicativo Sennett para macOS** distribuído fora da Mac App Store (DMG + pacotes de atualização automática).

- Site: [sennett.com.br](https://sennett.com.br) (português) · [sennett.app](https://sennett.app) (inglês)

## Baixe a versão estável mais recente

Baixe a versão estável mais nova na página do último lançamento:

**→ [Último lançamento](https://github.com/lumebuild/sennett_releases/releases/latest)**

Baixe o arquivo `.dmg`, abra-o e arraste o **Sennett** para a pasta Aplicativos. Links diretos seguem o padrão `https://github.com/lumebuild/sennett_releases/releases/latest/download/<nome-do-arquivo>` — o nome do DMG é estável por canal, então esse link sempre aponta para o DMG estável mais recente.

> **Ainda não há lançamentos?** O aplicativo está a caminho — os lançamentos aparecerão aqui em breve. Acompanhe as novidades em [sennett.com.br](https://sennett.com.br).

Depois de instalado, o aplicativo se atualiza automaticamente (via [Velopack](https://velopack.io)); normalmente você só precisa do DMG na primeira instalação.

## Beta / pré-lançamentos

Versões candidatas (RCs) são publicadas aqui como **pré-lançamentos do GitHub** no canal `beta`, antes de cada versão estável. Elas são destinadas a testadores:

- Marcadas como **Pre-release** na [página de lançamentos](https://github.com/lumebuild/sennett_releases/releases).
- Podem conter bugs — instale apenas se quiser experimentar as novidades e não se importar com imperfeições.
- Instalações beta se atualizam pelo canal beta; para voltar ao estável, instale o DMG estável mais recente.

## O que há neste repositório

Apenas **ativos e documentação** de lançamento — nenhum código-fonte:

- Instaladores `.dmg` e pacotes portáteis por lançamento
- Pacotes de atualização full/delta do Velopack e índices de feed por canal (`releases.<canal>.json`)
- O [modelo de notas de lançamento](.github/release-notes-template.md) que nosso fluxo de publicação aplica a cada lançamento

O **código-fonte do Sennett fica em um repositório privado**. Issues e pull requests aqui não são monitorados para o desenvolvimento do aplicativo.
