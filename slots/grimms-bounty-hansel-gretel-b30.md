# Grimms' Bounty: Hansel & Gretel

**Provider:** Pocket Games Soft

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/grimms-bounty-hansel-gretel-b30/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/grimms-bounty-hansel-gretel-b30/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/grimms-bounty-hansel-gretel-b30/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/grimms-bounty-hansel-gretel-b30/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/grimms-bounty-hansel-gretel-b30/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "grimms-bounty-hansel-gretel-b30",
  "name": "Grimms' Bounty: Hansel & Gretel",
  "status": "active",
  "provider": {
    "slug": "pocket-games-soft",
    "name": "Pocket Games Soft"
  },
  "game_category": "video_slot",
  "rtp_default": null,
  "rtp_variants": [],
  "volatility": "high",
  "mechanic": "ways",
  "reels": 3,
  "rows": 5,
  "jackpot_type": "none",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": null,
  "themes": [
    {
      "slug": "fairy-tale",
      "name": "Fairy Tale"
    },
    {
      "slug": "witchcraft",
      "name": "Witchcraft"
    }
  ],
  "features": [
    {
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "progressive_multiplier",
      "name": "Progressive Multiplier"
    },
    {
      "slug": "respin",
      "name": "Respin"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/grimms-bounty-hansel-gretel-b30/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/grimms-bounty-hansel-gretel-b30/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/grimms-bounty-hansel-gretel-b30/demand/
```

**12-month volume (illustrative):** 650 · **trend:** flat

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| India | 120 | growing |
| Brazil | 90 | flat |
| Philippines | 90 | flat |
| Indonesia | 60 | flat |
| Pakistan | 60 | flat |
| United States | 40 | flat |
| Algeria | 30 | flat |
| Cyprus | 30 | flat |
| Greece | 20 | flat |
| Kazakhstan | 20 | flat |

> Full per-country breakdown (17 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/grimms-bounty-hansel-gretel-b30/
- **Public page:** https://i-gaming.tools/slot-games/grimms-bounty-hansel-gretel-b30/
- **Full schema:** https://i-gaming.tools/api/docs/
