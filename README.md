# Repo Frontend Angular Demo

Repositorio de demostración que consume el pack **Frontend / Angular** desde el repositorio central `copilot-enterprise-prompt-packs`.

## Uso rápido

1. Crea el secret `GH_TOKEN_READ_PACKS` en este repo con un PAT que tenga permiso de lectura sobre el repo central.
2. Edita el workflow `.github/workflows/sync-copilot-angular-pack.yml` y reemplaza:
   `tu-org/copilot-enterprise-prompt-packs` por el nombre real de tu organización.
3. Ve a **Actions** y ejecuta el workflow **Sync Copilot Angular Pack**.
4. Revisa el Pull Request generado y haz merge si todo está correcto.
