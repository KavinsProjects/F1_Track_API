# F1 Track Images API

An open, free-to-use API for Formula 1 2026 season track/circuit images. No auth, no rate limits, just static image files served over HTTPS via GitHub Pages.

## Base URL

```
https://kavinsprojects.github.io/F1_Track_API
```

## Endpoints

### Get all tracks (metadata)

```
GET https://kavinsprojects.github.io/F1_Track_API/data.json
```

Returns a JSON array of every 2026 F1 circuit with its `id`, `name`, and `img_url`.

**Example response:**
```json
[
  {
    "id": 1,
    "name": "Albert Park Circuit (Melbourne, Australia)",
    "img_url": "https://kavinsprojects.github.io/F1_Track_API/track-img/Albert_Park_Circuit.png"
  },
 
]
```

### Get a specific track image

```
GET https://kavinsprojects.github.io/F1_Track_API/track-img/<Track-img>
```

Replace `<Track-img>` with any filename from the table below.

**Example:**
```
https://kavinsprojects.github.io/F1_Track_API/track-img/Albert_Park_Circuit.png
```

## Available Tracks

| ID | Circuit | Filename |
|----|---------|----------|
| 1 | Albert Park Circuit (Melbourne, Australia) | `Albert_Park_Circuit.png` |
| 2 | Shanghai International Circuit (China) | `chinese_Circuit.png` |
| 3 | Suzuka International Racing Course (Japan) | `Suzuka_Circuit.png` |
| 4 | Bahrain International Circuit (Sakhir, Bahrain) | `Bahrain_Circuit.png` |
| 5 | Jeddah Corniche Circuit (Saudi Arabia) | `Jeddah_Circuit.png` |
| 6 | Miami International Autodrome (USA) | `Miami_Circuit.png` |
| 7 | Circuit Gilles Villeneuve (Montreal, Canada) | `Gilles_Villeneuve_Circuit.png` |
| 8 | Circuit de Monaco (Monte Carlo, Monaco) | `Monaco_Circuit.png` |
| 9 | Circuit de Barcelona-Catalunya (Spain) | `Barcelona_Circuit.png` |
| 10 | Red Bull Ring (Spielberg, Austria) | `Red_Bull_Ring.png` |
| 11 | Silverstone Circuit (Great Britain) | `Silverstone_Circuit.png` |
| 12 | Circuit de Spa-Francorchamps (Belgium) | `Spa_Francorchamps_Circuit.png` |
| 13 | Hungaroring (Budapest, Hungary) | `Hungaroring_Circuit.png` |
| 14 | Circuit Zandvoort (Netherlands) | `Zandvoort_Circuit.png` |
| 15 | Madring - IFEMA Circuit (Madrid, Spain) | `Madring_Circuit.png` |
| 16 | Baku City Circuit (Azerbaijan) | `Baku_City_Circuit.png` |
| 17 | Marina Bay Street Circuit (Singapore) | `Marina_Bay_Circuit.png` |
| 18 | Circuit of the Americas (Austin, USA) | `COTA_Circuit.png` |
| 19 | Autodromo Hermanos Rodriguez (Mexico City, Mexico) | `Mexico_Circuit.png` |
| 20 | Autodromo Jose Carlos Pace - Interlagos (Sao Paulo, Brazil) | `Interlagos_Circuit.png` |
| 21 | Las Vegas Strip Circuit (USA) | `Las_Vegas_Circuit.png` |
| 22 | Losail International Circuit (Qatar) | `Losail_Circuit.png` |
| 23 | Yas Marina Circuit (Abu Dhabi, UAE) | `Yas_Marina_Circuit.png` |
| 24 | Autodromo Nazionale Monza (Italy) | `Monza_Circuit.png` |


## Notes

- This is a static, read-only API — image URLs never expire as long as the repo stays public.
- Filenames are case-sensitive.
- Images are illustrative placeholders/track references for the 2026 F1 season and are not official Formula 1 assets.
- Feel free to fork this repo and add your own track images.

## License

This project is for educational and personal use. Formula 1, F1, and associated team/circuit names are trademarks of Formula One Licensing B.V. and are not affiliated with this project.