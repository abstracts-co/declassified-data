# declassified-data

The large files behind [a/declassified](https://abstracts.co/a/declassified): page images, photos, films, tapes, the catalog and a PageIndex store, served by GitHub Pages at https://abstracts-co.github.io/declassified-data/ with `Access-Control-Allow-Origin: *`.

- `catalog.json`: what the explorer loads.
- `index.json`: every country, topic and file for agents, with summaries, official sources and links.
- `search.json`: the index nodes the explorer searches.
- `<country>/<topic>/<id>/`: one file's thumbnail, page images, photo, film or tape.
- `pageindex/`: a PageIndex local store. Clone this repository and open it with `PageIndexClient(index={"storage_path": "pageindex"})`.

Everything here was declassified or released by a government; each file's official source and license are in `index.json`. The layout and how to add a file are in the community repository: [docs/data.md](https://github.com/abstracts-co/declassified/blob/main/docs/data.md) and [skills/add-a-file](https://github.com/abstracts-co/declassified/blob/main/skills/add-a-file/SKILL.md).
