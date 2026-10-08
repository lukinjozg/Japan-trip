# Mile & Ika in Japan

A two-week route through Japan on a map: Tokyo, Hakone, Kyoto, Nara, Osaka, Hiroshima, Miyajima and Kumamoto, from 23 December 2026 to 6 January 2027, with One Piece and Jujutsu Kaisen spots along the way.

**Open the map:** https://lukinjozg.github.io/japan-trip/

**All places with Google Maps links:** [PLACES.md](PLACES.md)

## Using the map

- Tap a stop or a line on the map to see the plan. Tap a line to change how you travel between two stops, with notes and links.
- **Add places** takes Google Maps links, place names or coordinates, one per line.
- **Databases** shows the place lists. You can upload your own CSV, a Google Takeout "Saved Places" file or a My Maps KML export.
- Changes are saved in your own browser only. To share your version, use **Download trip file** on the Databases tab and send the file; the other person opens it with **Load trip file**.

## Place lists

The lists are plain CSV files in [databases/](databases/), and the map reads them every time it opens:

- `japan-highlights.csv`: cities, sights, food, nature and onsen across Japan
- `anime-spots.csv`: One Piece stores and statues, Jujutsu Kaisen locations, Jump Shops

To add a list, put a CSV in `databases/` with the columns `name, name_ja, lat, lng, category, region, tag, link, note` and add it to `databases/index.json`.

Map outline: Natural Earth and dataofjapan/land. Detailed map tiles: GSI Japan.
