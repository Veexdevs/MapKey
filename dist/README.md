# APKs compilados pelo GitHub Actions

Arquivos gerados automaticamente pelo workflow **Build APK**
(`.github/workflows/build-apk.yml`) a partir do `MapKey-Android-Project.zip`
da raiz do repositório. Nenhum arquivo do projeto é modificado na compilação.

| Arquivo | O que é |
|---|---|
| `MapKey-debug.apk` | **APK instalável.** Build de debug, já assinada com a chave de depuração da CI. Copie para o celular, abra e autorize "fontes desconhecidas". Requer Android 8.0+ (API 26). |
| `checksums.sha256` | SHA-256 dos APKs da build que gerou este arquivo. |

Este arquivo é atualizado a cada build na branch `main`. Para versões
anteriores, veja os [Releases](../releases) ou os artefatos em
[Actions](../actions).
