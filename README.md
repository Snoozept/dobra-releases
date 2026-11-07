# Dobra — APKs de teste

Distribuição pública de APKs de teste do Dobra. Este repositório contém apenas documentação, `latest.json` e APKs nas Releases: **não contém código-fonte do jogo nem chaves de assinatura**.

## Android

[Descarregar Dobra 0.2.0-test](https://github.com/Snoozept/dobra-releases/releases/download/v0.2.0-test/dobra-amostra.apk) · [Notas da versão](https://github.com/Snoozept/dobra-releases/releases/tag/v0.2.0-test)

Amostra em retrato, Android 6+ com WebView atualizado e WebGL2. APK universal, assinada com a mesma chave de debug da 0.1: instalar por cima, sem desinstalar. Só permitir instalações desta origem se confiar nesta distribuição de teste. O Android pede confirmação; não existe instalação silenciosa.

200 níveis em 10 capítulos, menu/mapa/progresso local, pausa, definições, controlos de toque revistos. Inglês em cada abertura; escolha de idioma apenas para a sessão: English, 中文(简体), Español, हिन्दी, العربية, Português, বাংলা, Русский, 日本語, Français. Jogo e fontes incluídos, sem rede; só o verificador de atualização usa internet. Sem conta, anúncios ou compras.

Ao abrir, a app consulta [latest.json](https://raw.githubusercontent.com/Snoozept/dobra-releases/main/latest.json). Se existir versão superior, oferece atualizar; o download verifica SHA-256, aplicação, versão e certificado antes de abrir o instalador Android.

**Versão de teste:** níveis gerados e verificados por solver, ainda sem afinação humana completa; traduções não revistas por nativos. Testes Chromium com toque real CDP, sem validação em aparelho físico. O emulador não concluiu a instalação por timeout da verificação de integridade. Não é garantia de desempenho num Android médio. As regras de design aguardam validação da Solene.
