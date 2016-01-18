# airplay
Ruby CLI to play videos on Apple TV through AirPlay

## Usage

```
Usage: airplay [options] URL
    -f, --format=FORMAT              Set explicit format [for youtube-dl](https://github.com/rg3/youtube-dl/blob/master/README.md#format-selection)
    -h, --host=HOST                  Set Apple TV host
```

## Example

```shell
airplay --host=my-apple-tv.local --formatf "[height <=? 720]" https://www.youtube.com/watch?v=QH2-TGUlwu4
```
