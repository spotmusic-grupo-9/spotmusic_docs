# Overview

* [**Overview**](README.md)
  * [1 SpotMusic](1%20SpotMusic/README.md)
  * [2 Deployment](2%20Deployment/README.md)

---

![diagram](https://www.plantuml.com/plantuml/svg/0/LP1DQy9048RlWVo7RKuMrBruwacnjWhQX2GYFOLnC-Z2VeITsRR-dFwM_h6I1Ffn6zvvdsTWbiGGE5gJ9dVQAHDR55VcZXwa3F0-lsY-ndCa3CexHiTpvQti3BWUcX6tHf_bUZ4h-kXus4iBn1ZaUj6iU-A3vzsWJvDgcv-QObDM-KjJv6LThdRrv3vDzglN_5Wt-yrJtPIxv-qGfWbhDYWUDLm2M10j2ZKAlMYzg3hFXqXQzTK20tatYHGXQ3yLsP7YrsVG_vlPtuNoTl210DPla0qdgninsedrPsrmAh9nwBdEmCreOX8eR2y36f4IpU_T7t2ba0YayewynR6vHDSEd_W6)

# SpotMusic & Grupo 9

Soluções em nuvem para compartilhamento de musicas e playlist 🎶

## Projetos e pastas

### Spotmusic docs

- **Descrição:** O [spotmusic_docs](https://github.com/spotmusic-grupo-9/spotmusic_docs) contém a documentação no formato C4 do projeto.
- **Tecnologias:** C4. _Utilize a extensão [PlantUML](https://marketplace.visualstudio.com/items?itemName=jebbs.plantuml) para visualizar os dados gerados pelas extensões `.puml` no projeto._

### Spotmusic API

- **Descrição:** O [spotmusic_api](https://github.com/spotmusic-grupo-9/spotmusic_api) é a API principal deste projeto.
- **Tecnologias:** [Python 3.11](https://www.python.org/downloads/release/python-3110/), [FastAPI](https://fastapi.tiangolo.com/)

### Spotmusic Account API

- **Descrição:** O [spotmusic_account_api](https://github.com/spotmusic-grupo-9/spotmusic_account_api) é responsável pelo controle de autorização/autenticação do projeto.
- **Tecnologias:** [Python 3.11](https://www.python.org/downloads/release/python-3110/), [FastAPI](https://fastapi.tiangolo.com/)

### Spotmusic Insights

- **Descrição:** O [spotmusic_insights](https://github.com/spotmusic-grupo-9/spotmusic_insights) é responsável por gerar playlists como recomendações baseado no historico dos usuários.
  - api `retorno de recomendações com base no historico`
  - worker `cria recomendações com base no historico`
- **Tecnologias:**  [Python 3.11](https://www.python.org/downloads/release/python-3110/), [FastAPI](https://fastapi.tiangolo.com/), [Gunicorn](https://fastapi.tiangolo.com/de/deployment/server-workers/?h=gunicorn)

### Spotmusic Operations Worker

- **Descrição:** O [spotmusic_operations_woker](https://github.com/spotmusic-grupo-9/spotmusic_operations_woker) é responsável pela conversão de texto em fala para enriquecimento de busca.
- **Tecnologias:** [Python 3.11](https://www.python.org/downloads/release/python-3110/), [FastAPI](https://fastapi.tiangolo.com/), [Gunicorn](https://fastapi.tiangolo.com/de/deployment/server-workers/?h=gunicorn), [Azure Speech To Text](https://azure.microsoft.com/en-us/products/ai-services/speech-to-text)

### Spotmusic Mobile Android

- **Descrição:** O [spotmusic_mobile_android](https://github.com/spotmusic-grupo-9/spotmusic_mobile_android) é nosso aplicativo mobile android.
- **Tecnologias:** [Kotlin](https://developer.android.com/kotlin), [SQLite](https://developer.android.com/training/data-storage/sqlite?hl=pt-br)

### Spotmusic Mobile iOS

- **Descrição**: O [spotmusic_mobile_ios](https://github.com/spotmusic-grupo-9/spotmusic_mobile_ios) é nosso aplicativo mobile ios.
- **Tecnologias:** [Swift](https://www.apple.com/br/swift/), [SQLite](https://github.com/stephencelis/SQLite.swift)

## Commitlint
Padrão de commits [link](https://github.com/conventional-changelog/commitlint/?tab=readme-ov-file#what-is-commitlint)
