# birdcrab

The crab goes birdwatching. A new bird lands every 12 hours, at 12am and 12pm local time, with a hand-drawn sketch, a field note and a real recording of its call. A countdown shows when the next bird arrives, and the bird log keeps the last 7 days.

It's a single static page with no build step and no server code.

## Files

```
index.html     the whole app: markup, styles, drawings, bird data and script
sounds/        69 short bird recordings (AAC audio in .mp4 files)
README.md      this file, including credits for every recording
```

## Run it locally

Open `index.html` through a local web server so the sounds load:

```
python3 -m http.server 8000
```

Then visit http://localhost:8000.

## Publish with GitHub Pages

1. Push these files to the root of a repository.
2. In the repository, go to **Settings → Pages**.
3. Under **Build and deployment**, pick **Deploy from a branch**, choose your main branch and the `/ (root)` folder, and save.
4. The site appears at `https://<your-username>.github.io/<repository-name>/` after a minute or two.

## Sound credits and licenses

Every sound is a real field recording. Each clip was trimmed to about 10 seconds, faded in and out, level-matched and re-encoded to AAC. Those changes are the only edits. Each clip keeps the license of its original recording, listed below.

**Commercial use:** 11 clips are licensed CC BY-NC-SA (non-commercial): snowy owl, emperor penguin, secretary bird, common ostrich, brown pelican, scarlet ibis, sulphur-crested cockatoo, burrowing owl, mandarin duck, bee hummingbird, wandering albatross. Don't sell or monetize this app with those clips included. Replace them first, or remove them. All other clips are public domain, CC0, CC BY or CC BY-SA, which allow commercial use with credit (and, for BY-SA, sharing the clip under the same license).

| Bird | Recorded by | License | Source |
| --- | --- | --- | --- |
| american robin | radrat | [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0) | [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Turdus_migratorius_-_American_Robin_XC566186.mp3) |
| great blue heron | G. McGrane | [Public domain](https://commons.wikimedia.org/wiki/File:Great_Blue_Heron1.ogg) | [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Great_Blue_Heron1.ogg) |
| ruby-throated hummingbird | Jonathon Jongsma | [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0) | [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Archilochus_colubris_-_Ruby-throated_Hummingbird_XC109597.mp3) |
| snowy owl | Tero Linjama | [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) | [xeno-canto](https://xeno-canto.org/343144) |
| mallard | Jonathon Jongsma | [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0) | [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Anas_platyrhynchos_-_Mallard_XC112828.mp3) |
| scarlet macaw | Ganesh Mohan T | [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0) | [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Scarlet_macaw_01.wav) |
| peregrine falcon | Sharadapte | [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0) | [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Peregrine_falcon_call_recorded_in_February_2010_at_Yana,_Karnataka.wav) |
| atlantic puffin | unknown recordist | [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0) | [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Atlantic_Puffin_(Fratercula_arctica)_(W1CDR0001416_BD3).ogg) |
| northern cardinal | Jonathon Jongsma | [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0) | [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Cardinalis_cardinalis_-_Northern_Cardinal_XC112830.mp3) |
| american flamingo | Justin Watts | [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) | [xeno-canto](https://xeno-canto.org/737280) |
| greater roadrunner | Bob DuHamel | [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0) | [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Roadrunner_Clatter.ogg) |
| emperor penguin | Santiago Imberti | [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) | [xeno-canto](https://xeno-canto.org/689246) |
| blue jay | Jonathon Jongsma | [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0) | [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Cyanocitta_cristata_-_Blue_Jay_XC108404.mp3) |
| common kingfisher | Marie-Lan Taÿ Pamart | [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0) | [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Alcedo_atthis_-_Common_Kingfisher_XC476785.mp3) |
| barn owl | Joost van Bruggen | [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0) | [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Tyto_alba_-_Western_Barn_Owl_XC432000.mp3) |
| wood duck | Jonathon Jongsma | [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0) | [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Aix_sponsa_-_Wood_Duck_XC63109.mp3) |
| toco toucan | Fabrício Grigolin | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0) | [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Toco_Toucan_call_(Ramphastos_toco).ogg) |
| bald eagle | NPS & MSU Acoustic Atlas/Jennifer Jerrett | [Public domain](https://commons.wikimedia.org/wiki/File:Yellowstone_sound_library_-_Bald_Eagle_-_003.mp3) | [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Yellowstone_sound_library_-_Bald_Eagle_-_003.mp3) |
| north island brown kiwi | Department of Conservation | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0) | [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Kiwi_Male_North_Island_brown_kiwi_song.ogg) |
| black-capped chickadee | Jonathon Jongsma | [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0) | [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Poecile_atricapillus_-_Black-capped_Chickadee_XC70185.mp3) |
| secretary bird | Niall Perrins | [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) | [xeno-canto](https://xeno-canto.org/391856) |
| european starling | Marie-Lan Taÿ Pamart | [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0) | [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Sturnus_vulgaris_-_Common_Starling_XC516954.mp3) |
| mute swan | Alexander Kürthy | [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0) | [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Cygnus_olor_-_Mute_Swan_XC307509.mp3) |
| pileated woodpecker | G. McGrane | [Public domain](https://commons.wikimedia.org/wiki/File:Pileated_Woodpecker.ogg) | [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Pileated_Woodpecker.ogg) |
| common ostrich | Michael Chiappone | [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) | [xeno-canto](https://xeno-canto.org/845942) |
| painted bunting | AMANTEDESAURIOS | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0) | [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Passerina_ciris_1435567.ogg) |
| brown pelican | Judith PRIAM | [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) | [xeno-canto](https://xeno-canto.org/357928) |
| great horned owl | Michael & Katie LaTour | [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0) | [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Bubo_virginianus_-_Great_Horned_Owl_XC450919.mp3) |
| budgerigar | mary905 | [Public domain](https://commons.wikimedia.org/wiki/File:Budgerigar_chirping.ogg) | [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Budgerigar_chirping.ogg) |
| arctic tern | Doug Hynes | [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0) | [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Sterna_paradisaea_-_Arctic_Tern_XC564600.mp3) |
| american goldfinch | Kevin Hood | [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0) | [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Spinus_tristis_-_American_Goldfinch_XC483030.mp3) |
| wild turkey | Jonathon Jongsma | [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0) | [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Meleagris_gallopavo_-_Wild_Turkey_XC134744.ogg) |
| osprey | unknown recordist | [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0) | [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Osprey_(Pandion_haliaetus)_(W1CDR0001434_BD8).ogg) |
| common loon | Jonathon Jongsma | [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0) | [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Gavia_immer_-_Common_Loon_XC139388.mp3) |
| laughing kookaburra | Powys, V. | [CC BY 3.0](https://creativecommons.org/licenses/by/3.0) | [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Dacelo_novaeguineae_ANWC_X00520.opus) |
| scarlet ibis | Dante Buzzetti | [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) | [xeno-canto](https://xeno-canto.org/1016019) |
| cedar waxwing | Jonathon Jongsma | [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0) | [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Bombycilla_cedrorum_-_Cedar_Waxwing_XC107623.mp3) |
| sulphur-crested cockatoo | Mengshuai Ge | [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) | [xeno-canto](https://xeno-canto.org/1071627) |
| burrowing owl | Thomas Beverly | [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) | [xeno-canto](https://xeno-canto.org/382734) |
| mandarin duck | Alan Dalton | [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) | [xeno-canto](https://xeno-canto.org/953769) |
| red-tailed hawk | Jonathon Jongsma | [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0) | [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Buteo_jamaicensis_-_Red-tailed_Hawk_XC71575.mp3) |
| eastern bluebird | Jonathon Jongsma | [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0) | [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Sialia_sialis_-_Eastern_Bluebird_XC179669.mp3) |
| shoebill | — | no recording (shoebills are nearly silent) | — |
| indian peafowl | Ke4roh | [Public domain](https://commons.wikimedia.org/wiki/File:Pavo_cristatus_(call).ogg) | [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Pavo_cristatus_(call).ogg) |
| common raven | Jonathon Jongsma | [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0) | [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Corvus_corax_-_Northern_Raven_XC101590.mp3) |
| bee hummingbird | Catriona Leven | [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) | [xeno-canto](https://xeno-canto.org/318392) |
| herring gull | Sonothèque ADVL | [CC0](http://creativecommons.org/publicdomain/zero/1.0/deed.en) | [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:XC707075_-_European_Herring_Gull_-_Larus_argentatus.mp3) |
| baltimore oriole | Jonathon Jongsma | [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0) | [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Icterus_galbula_-_Baltimore_Oriole_XC101614.mp3) |
| emu | Lütgens, Hans | [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0) | [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Dromaius_novaehollandiae_Lue0043_03.wav) |
| kea | unknown recordist | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0) | [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Kea-song.wav) |
| sandhill crane | Jonathon Jongsma | [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0) | [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Grus_canadensis_-_Sandhill_Crane_XC111489.mp3) |
| northern mockingbird | David Illig | [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0) | [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Mimus_polyglottos_Northern_Mockingbird.ogg) |
| american kestrel | Niels Krabbe | [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0) | [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Falco_sparverius_-_American_Kestrel_XC250844.mp3) |
| resplendent quetzal | Leander Khil | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0) | [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Resplendent_Quetzal_song_(Pharomachrus_mocinno).ogg) |
| wandering albatross | Greg McLachlan | [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) | [xeno-canto](https://xeno-canto.org/883164) |
| red-headed woodpecker | Jonathon Jongsma | [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0) | [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Melanerpes_erythrocephalus_-_Red-headed_Woodpecker_XC254603.mp3) |
| barn swallow | Jonathon Jongsma | [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0) | [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Hirundo_rustica_-_Barn_Swallow_XC83449.mp3) |
| canada goose | Antonio Xeira | [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0) | [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Branta_canadensis_-_Canada_Goose_XC388771.mp3) |
| hoopoe | Alexander Kurthy | [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0) | [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Upupa_epops_-_Eurasian_Hoopoe_XC108366.mp3) |
| great egret | Jonathon Jongsma | [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0) | [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Ardea_alba_-_Great_Egret_XC131650.ogg) |
| eurasian magpie | Benoît Van Hecke | [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0) | [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Pica_pica_-_Eurasian_Magpie_XC537413.mp3) |
| willow ptarmigan | unknown recordist | [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0) | [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Red_Grouse_(Lagopus_lagopus)_(W1CDR0001407_BD28).ogg) |
| belted kingfisher | Jonathon Jongsma | [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0) | [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Megaceryle_alcyon_-_Belted_Kingfisher_XC132872.ogg) |
| red-winged blackbird | radrat | [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0) | [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Agelaius_phoeniceus_-_Red-winged_Blackbird_XC551977.mp3) |
| andean condor | Fernando Castro | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0) | [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Andean_Condor_call_(Vultur_gryphus).ogg) |
| house wren | radrat | [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0) | [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Troglodytes_aedon_-_House_Wren_XC558995.mp3) |
| bar-tailed godwit | Lauri Hallikainen | [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0) | [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:XC234849-Default_Project.ogg) |
| tufted titmouse | U. S. Fish and Wildlife Service | [Public domain](https://commons.wikimedia.org/wiki/File:Tufted_Titmouse_call.ogg) | [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Tufted_Titmouse_call.ogg) |
| killdeer | Jonathon Jongsma | [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0) | [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Charadrius_vociferus_-_Killdeer_XC62728.mp3) |
| mourning dove | Jonathon Jongsma | [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0) | [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Zenaida_macroura_-_Mourning_Dove_XC128006.ogg) |

Bird drawings, field notes and code: the crab's own sketches. Colors and shapes are close, not field-guide exact.
