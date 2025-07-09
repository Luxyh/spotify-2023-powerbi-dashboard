# 📊 Informações sobre o Dataset – Top Spotify Songs 2023

## 🔗 Fonte dos Dados
O dataset foi retirado do Kaggle, disponível publicamente neste link:  
[Top Spotify Songs 2023 – Kaggle](https://www.kaggle.com/datasets/nelgiriyewithana/top-spotify-songs-2023)

---

## 🎧 Descrição
Este conjunto de dados contém uma lista abrangente das músicas mais famosas de 2023, conforme listadas no Spotify.  
Além dos dados tradicionais de streaming, ele inclui insights sobre popularidade em diversas plataformas (Spotify, Apple Music, Deezer, Shazam) e características musicais.

---

## 🧾 Principais Colunas:

| Coluna                | Descrição |
|-----------------------|-----------|
| `track_name`          | Nome da música |
| `artist(s)_name`      | Nome do(s) artista(s) |
| `artist_count`        | Número de artistas por música |
| `released_year`       | Ano de lançamento |
| `released_month`      | Mês de lançamento |
| `released_day`        | Dia de lançamento |
| `in_spotify_playlists`| Nº de playlists no Spotify |
| `in_spotify_charts`   | Presença nos charts do Spotify |
| `streams`             | Total de streams |
| `in_apple_playlists`  | Nº de playlists no Apple Music |
| `in_apple_charts`     | Presença nos charts do Apple Music |
| `in_deezer_playlists` | Nº de playlists no Deezer |
| `in_deezer_charts`    | Presença nos charts do Deezer |
| `in_shazam_charts`    | Presença nos charts do Shazam |
| `bpm`                 | Batidas por minuto (tempo da música) |
| `key`                 | Tom musical |
| `mode`                | Modo (maior ou menor) |
| `danceability_%`      | Dançabilidade (%) |
| `valence_%`           | Positividade (%) |
| `energy_%`            | Energia (%) |
| `acousticness_%`      | Nível de elementos acústicos (%) |
| `instrumentalness_%`  | Nível de instrumentalidade (%) |
| `liveness_%`          | Presença de elementos ao vivo (%) |
| `speechiness_%`       | Presença de fala (%) |

---

## 🛠️ Pré-processamento e Limpeza
- A coluna de data foi reestruturada para formar um campo de data completo (dia/mês/ano)
- Foram criadas medidas DAX para somatórios, rankings e percentuais
- Algumas músicas duplicadas ou inconsistentes foram filtradas no Power Query
- Novas tabelas foram criadas para gráficos específicos


---

> Dados coletados de forma pública para fins de estudo em Análise de Dados com Power BI.
