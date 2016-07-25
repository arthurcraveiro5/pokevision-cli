# (Unofficial) PokéVision CLI

This tool allows you to talk directly to the PokeVision.com API servers. Right now there is only one command - `pokevision watch`, which monitors the coordinates provided for new Pokémon, and logs their location & expiration time.

## Install

```sh
$ curl -LO https://github.com/jacobmarshall/pokevision-cli/releases/download/1.0.4/darwin-amd64.tar.gz
$ tar -xvzf darwin-amd64.tar.gz
$ sudo mv ./pokevision /usr/local/bin
```

## Usage

```sh
$ pokevision watch --lat=34.00846023931052 --lon=-118.49802017211914
2016/07/22 23:43:14 Found new Pokémon...
2016/07/22 23:43:14 Electabuzz (2 minutes) at 34.009281622135/-118.49784634188
2016/07/22 23:43:14 Shellder (1 minute) at 34.00974867823/-118.49884989372
2016/07/22 23:43:14 Psyduck (5 minutes) at 34.008127253796/-118.49830250257
2016/07/22 23:43:14 Kabuto (3 minutes) at 34.007904895169/-118.4934671352
2016/07/22 23:43:14 Electabuzz (1 minute) at 34.008372025295/-118.49447071366
2016/07/22 23:43:14 Staryu (6 minutes) at 34.006079044182/-118.49182490277
2016/07/22 23:43:14 Ekans (6 seconds) at 34.006867650323/-118.49155119578
2016/07/22 23:43:14 Geodude (2 minutes) at 34.006741762417/-118.49173366716
2016/07/22 23:43:14 Weedle (7 minutes) at 34.008332287824/-118.49875866199
2016/07/22 23:43:14 Nidorina (1 minute) at 34.009707683102/-118.49520058507
2016/07/22 23:43:14 Staryu (6 minutes) at 34.005749600448/-118.49027389049
2016/07/22 23:43:14 Shellder (3 minutes) at 34.004652196031/-118.49082130825
2016/07/22 23:43:14 Drowzee (7 minutes) at 34.007428877695/-118.49948851445
2016/07/22 23:43:14 Zubat (7 minutes) at 34.00795459958/-118.49930605164
2016/07/22 23:43:14 Doduo (4 minutes) at 34.007828703036/-118.49948851445
2016/07/22 23:43:14 Growlithe (5 minutes) at 34.012492884561/-118.49684278394
2016/07/22 23:43:14 Nidoran♂ (7 minutes) at 34.012184931996/-118.49647785227
...
```

## Upcoming features

- Desktop notifications
- Push to Slack
- Pokémon rarity filter
