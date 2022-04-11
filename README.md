# Screenshots for atlas.smartforests.net

This repository keeps a history of how different pages on [atlas.smartforests.net](atlas.smartforests.net) look, updated every 14 days.

### Configuration

- How often the screenshots are re-generated is specified in [.github/workflows/generate_screenshots.yml](https://github.com/planetarypraxis/smartforests-screenshots/blob/32a55910fc2cc8f9d9067336aa76a76b02a26cf4/.github/workflows/generate_screenshots.yml#L8)

- What URLs it screenshots (and technical details of the images like filename, width and height) is defined in [settings/shot-scraper.yml](https://github.com/planetarypraxis/smartforests-screenshots/blob/32a55910fc2cc8f9d9067336aa76a76b02a26cf4/settings/shot-scraper.yml#L1-L44).

### Technical docs

This repo uses [shot-scraper](https://github.com/simonw/shot-scraper) to generate screenshots using procedures defined in [a YAML file](settings/shot-scraper.yml).

Shot-scraper is triggered by [this GitHub Actions workflow](.github/workflows/shots.yml) on a recurring schedule.

The screenshot images are then written back to this repository.
