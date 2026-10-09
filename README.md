# Mile & Ika in Japan

An 11-night route through Japan on a map: Tokyo, Hakone, Kyoto, Nara, Osaka and Nagoya, from 23 December 2026 to 3 January 2027, back to Tokyo by Shinkansen, with One Piece and Jujutsu Kaisen spots along the way.

**Open the map:** https://lukinjozg.github.io/Japan-trip/

**All places with Google Maps links:** [PLACES.md](PLACES.md)

## Using the map

- Tap a stop or a line on the map to see the plan. Tap a line to change how you travel between two stops, with notes and links.
- **Sleep** keeps where you sleep apart from the route: add a hotel or ryokan to each overnight stop with a Google Maps or booking link, price and notes, and mark it Option or Booked. They show on the map as pink bed pins.
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
