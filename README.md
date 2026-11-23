<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="icon-dark.png">
    <img src="icon.png" alt="Babble" width="112">
  </picture>
</p>

<h1 align="center">Babble voices</h1>

<p align="center">Voice packs for Babble. Free to use.</p>

Babble reads `catalog.json` from here and lists each pack in Library → Available. You can hear every voice
before you download anything. The previews are in `previews/`, and the pack files are on Hugging Face.

Every voice comes from a recording that can be shared, and its source and license are listed in the catalog.

## Adding a pack

1. Export it in Babble (Train a voice → Export pack), with previews.
2. `python scripts/publish_pack.py <pack> <this folder> --hf <user>/babble-voices` in the Babble repo.
3. Upload the pack to Hugging Face and push this repo (the script prints both commands).
