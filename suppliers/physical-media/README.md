# Physical Media Suppliers

> For CDs, DVDs, Blu-rays, vinyl. OddHobb Records and similar.

---

## Kunaki — PRIMARY (cheapest)

| Field | Value |
|-------|-------|
| **URL** | https://www.kunaki.com |
| **Location** | Sparks, Nevada, USA |
| **Products** | CD, DVD, Blu-ray, vinyl |
| **MOQ** | 1 |
| **Ship time** | 24 hours production + 14 days international |

### Pricing
| Product | Cost | Notes |
|---------|------|-------|
| CD (printed jacket) | $1.50 | Full color, cellophane |
| CD (jewel case) | $2.00 | 2-panel insert, tray card |
| CD (disc only) | $0.75 | No packaging |
| DVD (jacket) | $1.50 | |
| DVD (case) | $2.00 | |
| Blu-ray | $2.45 | Case + artwork + cellophane |
| Vinyl (12" black) | $36 | Playable |
| Vinyl (12" color) | $50 | Playable |
| Vinyl (12" display) | $11 | Non-playable |

### Features
- Free UPC barcode for jewel-case CDs
- Dropship via XML/HTTP API
- CSV multi-recipient fulfillment
- Prefund account for automated orders
- Audio CD, MP3 CD, Data CD

### Caveats
- Own return address (not white-label)
- No custom thank-you cards inside
- No cassette manufacturing

---

## DiskCrafters — UK Premium

| Field | Value |
|-------|-------|
| **URL** | https://www.diskcreators.co.uk |
| **Location** | Greater Manchester, UK |
| **Products** | CD, digipak, digisleeve, digifile |
| **MOQ** | 1 |
| **Ship time** | UK-based, worldwide |

### Pricing
| Product | Cost |
|---------|------|
| Plastic sleeve | £6.50 |
| Slim jewel case | £7.50 |
| Standard jewel case | £7.99 |
| Clear jewel case | £8.99 |

### Services
- Direct-to-disc printing (not stickers)
- Mastering from £3/track
- Artwork design service
- Vinyl-to-digital conversion
- Free samples of existing work

### Fulfillment Model
- You give them audio/art
- They create order page
- Customer buys
- They manufacture, ship, handle support/refunds/tax
- You get profit split

---

## WALRUS — Micro-Label Feel

| Field | Value |
|-------|-------|
| **URL** | https://walrus.audio |
| **Products** | CD, cassette, vinyl |
| **MOQ** | 1 |
| **Ship time** | 2-4 business days |
| **Model** | Zero upfront, revenue split |

### Products
| Product | Format |
|---------|--------|
| CD | Jewel case or printed jacket |
| Cassette | J-card + printed labels |
| Vinyl | 7" or 12" lathe cuts |

### Best For
- Feeling like a real micro-label
- Cassette manufacturing (Kunaki doesn't do cassettes)
- Zero upfront cost

---

## elasticStage — Premium

| Field | Value |
|-------|-------|
| **URL** | https://elasticstage.com |
| **Location** | UK, ships to 92 countries |
| **Products** | Vinyl + booklet, CDs |
| **Best for** | Collectible releases once demand exists |

---

## Comparison Matrix

| Feature | Kunaki | DiskCrafters | WALRUS | elasticStage |
|---------|--------|-------------|--------|-------------|
| **CD cost** | $2.00 | £7.99 | Revenue split | Varies |
| **MOQ** | 1 | 1 | 1 | 1 |
| **Cassettes** | No | No | Yes | No |
| **Vinyl** | Yes ($36+) | No | Yes | Yes |
| **Dropship** | Yes (API) | Yes (fulfillment) | Yes | Yes |
| **UK shipping** | Slow (14 days) | Fast | Fast | Fast |
| **White-label** | No (own address) | Yes | Yes | Yes |
| **Custom inserts** | No | Yes | Yes | Yes |

## Recommendation

| Use Case | Supplier |
|----------|----------|
| **Cheap prototype** | Kunaki ($2 CD) |
| **UK commercial launch** | DiskCrafters (£7.99) |
| **Cassette releases** | WALRUS |
| **Premium collectible** | elasticStage |
| **Micro-label feel** | WALRUS |

## Integration Flow

```
OddHobb Records → Kunaki API → CD manufactured → Shipped to customer
                         ↓
              Etsy order → automation → fulfillment
                         ↓
              Spotify/Amazon → digital distribution
```
