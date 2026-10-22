# Mile & Ika in Japan

A 14-night route through Japan on a map: Shinjuku, Hakone, Kyoto, Osaka, Hiroshima, Miyajima, Nagoya and a last night in Ueno, from 23 December 2026 to 6 January 2027, with One Piece and Jujutsu Kaisen spots along the way.

**Open the map:** https://lukinjozg.github.io/Japan-trip/

**All places with Google Maps links:** [PLACES.md](PLACES.md)

## Where we sleep

All booked.

| Nights | Where | Price | Payment |
|---|---|---|---|
| 23–27 Dec (4) | Shinjuku | 244.27 € | Paid |
| 27–28 Dec (1) | Hakone | 183 € | At the property |
| 28–30 Dec (2) | Kyoto | 100 € | 21 Dec |
| 30 Dec – 2 Jan (3) | Osaka | 330 € | At the property |
| 2–3 Jan (1) | Hiroshima | 60 € | 30 Dec |
| 3–5 Jan (2) | Nagoya | 102 € | 31 Dec |
| 5–6 Jan (1) | Ueno | 64 € | 6 Dec |
| **14 nights** | | **1,083.27 €** | 541.64 € each |

## Shinkansen

Four Shinkansen rides, all on the Tokaido and Sanyo line, so one [SmartEX](https://smart-ex.jp/en/) account books every one of them. Fares are per person for a reserved seat in an ordinary car, roughly; the year-end peak adds a few hundred yen.

| Day | Train | Leave | About | Fare | Seats confirmed |
|---|---|---|---|---|---|
| Mon 28 Dec | Odawara → Kyoto, Hikari | 11:00–12:00 | 2 h | ≈ ¥12,500 | 28 Nov |
| Sat 2 Jan | Shin-Osaka → Hiroshima, Nozomi or Sakura | 10:30–11:30 | 1 h 25 min | ≈ ¥10,800 | 2 Dec |
| Sun 3 Jan | Hiroshima → Nagoya, Nozomi | 15:00–16:30 | 2 h 15 min | ≈ ¥15,000 | 3 Dec |
| Tue 5 Jan | Nagoya → Tokyo, Nozomi | 12:00–13:00 | 1 h 40 min | ≈ ¥11,500 | 5 Dec |

About ¥50,000 each, ¥100,000 for two. A 7-day JR Pass (¥50,000) costs the same, only covers 7 of the 9 days between the first and last ride, and needs an extra ticket for Nozomi, so single tickets are better.

Why these times: on 28 Dec you check out of the ryokan around 10:00; on 2 Jan you get the afternoon at the Peace Memorial Park; on 3 Jan Miyajima gets the whole morning (high tide around 7:10, ferry queues grow later); on 5 Jan you have the morning for Atsuta Jingu and the Mugiwara Store.

### Where to book

Book on **[SmartEX](https://smart-ex.jp/en/)**, the official site and app of JR Central, JR West and JR Kyushu, in English. It covers all four rides, sells at the normal JR price, and is the only place that lets you book now for seats a month ahead. Resellers (Klook, Trip.com and the like) add a fee, and buying at the station over New Year risks sold-out trains.

1. Install the SmartEX app (or use the website) and sign up with a credit card. One account books for both of you.
2. Book each ride now. SmartEX takes bookings up to a year ahead and confirms the train and seats from 8:00 Japan time one month before the day (the dates above), which is midnight in Croatia. You get an email.
3. Pick reserved seats in an ordinary car. Booking this early, you can't choose seats or a seat with an oversized baggage area; SmartEX picks them at 8:00 Japan time one month before. Then, straight away and before the general sale at 10:00 Japan time (2:00 in Croatia), change on the seat map:
   - to D and E, the two-seat side, together; E is on the Mt Fuji side in both directions
   - to a seat with an oversized baggage area if a bag is over 160 cm (length + width + height)

   You can't change or refund a booking on that day from 7:30 Japan time until the seats are confirmed.
4. Ride with the QR code ticket SmartEX gives you, or link your IC cards (Suica, PASMO) to the booking and tap through the gates.

### Tricks

- Changes are free, as many times as you like, up to 4 minutes before the train leaves. Book a time now and move it on your phone if Miyajima runs long. Cancelling costs ¥320.
- Over New Year (about 26 Dec to 4 Jan) every Nozomi is reserved seats only, so there is no unreserved car to fall back on. On 2 Jan, Sakura and Mizuho to Hiroshima still have unreserved cars.
- Only Hikari and Kodama stop at Odawara, and only Nozomi run straight from Hiroshima to Nagoya.
- If ordinary seats sell out, the Green Car (first class, about ¥5,000 more) often still has seats.
- Hayatoku early-booking discounts usually don't apply over New Year.
- Local trains (Hiroshima–Miyajimaguchi, Kyoto–Osaka, Tokyo–Ueno) aren't booked: tap in with your IC card. The Romancecar to Hakone and the Skyliner to Narita are booked on their own sites (links on the map).
- Buy an ekiben (station bento) before boarding: anago-meshi in Hiroshima, tenmusu in Nagoya.

## Using the map

- Tap a stop or a line on the map to see the plan. Tap a line to change how you travel between two stops, with notes and links.
- **Sleep** keeps where you sleep apart from the route: add a hotel or ryokan to each overnight stop with a Google Maps or booking link, price and notes, and mark it Option or Booked. Each overnight stop starts with a few hotel suggestions. They show on the map as pink bed pins.
- The layers button switches the map between roads and names, the detailed map and a plain outline. Only Japan is drawn.
- **Add places** takes Google Maps links, place names or coordinates, one per line.
- **Databases** shows the place lists. You can upload your own CSV, a Google Takeout "Saved Places" file or a My Maps KML export.
- Changes are saved in your own browser only. To share your version, use **Download trip file** on the Databases tab and send the file; the other person opens it with **Load trip file**.

## Place lists

The lists are plain CSV files in [databases/](databases/), and the map reads them every time it opens:

- `japan-highlights.csv`: cities, sights, food, nature and onsen across Japan
- `anime-spots.csv`: One Piece stores and statues, Jujutsu Kaisen locations, Jump Shops

To add a list, put a CSV in `databases/` with the columns `name, name_ja, lat, lng, category, region, tag, link, note` and add it to `databases/index.json`.

Map outline: dataofjapan/land. Roads and names: Esri. Detailed map tiles: GSI Japan.
