<div align="center">
    <h1>Repattern</h1>
    <b>Unique deterministic procedural image and identicon generator, with all sorts of modifiers</b>
</div>

## Quick preview:

- [**Quick start**](#quick-start)
- [**Usage**](#usage)
  - [**Importing**](#importing)
  - [**Generate**](#generate)
  - [**Saving**](#saving)
  - [**Getting a buffer**](#getting-a-buffer-for-web-use-apis-etc)
  - [**Identicon**](#identicon)
  - [**Delusional Background**](#delusional-background-1)
  - [**Psychedelic Background**](#psychedelic-background-1)
  - [**Combined**](#combined)
  - [**Effects**](#effects)
    - [**Early Internet**](#early-internet)
    - [**Cybercore**](#cybercore)
    - [**Pixelated**](#pixelated)
- [**More examples**](#more-examples)

### Identicons:

<div align="center">
<table>
<tr>
<th><div align="center">Normal</div></th>
<th><div align="center">Gradient</div></th>
<th><div align="center">Gradient + Base color</div></th>
<th><div align="center">Rounded blocks</div></th>
<th><div align="center">Padding</div></th>
</tr>
<tr>
<td><a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/specific/Identicon/Repattern-1.0.png"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/specific/Identicon/Repattern-1.0.png"></a></td>
<td><a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/specific/Identicon/Repattern-1.0-gradient.png"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/specific/Identicon/Repattern-1.0-gradient.png"></a></td>
<td><a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/specific/Identicon/Repattern-1.0-gradient-red.png"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/specific/Identicon/Repattern-1.0-gradient-red.png"></a></td>
<td><a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/specific/Identicon/Repattern-1.0-gradient-red-round.png"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/specific/Identicon/Repattern-1.0-gradient-red-round.png"></a></td>
<td><a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/specific/Identicon/Repattern-1.0-gradient-red-padding100.png"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/specific/Identicon/Repattern-1.0-gradient-red-padding100.png"></a></td>
</tr>

</table>
 
</div>

<details>
    <summary>Options</summary>

> Seed: `Repattern-1.0`
>
> Options: (For the normal picture, just add the seed with no other modifiers)
>
> Gradient: `Identicon_Options(gradient=True)`
>
> Gradient + Base color: `Identicon_Options(gradient=True, basecolor=(255,0,0))`
>
> Rounded blocks: `Identicon_Options(gradient=True, basecolor=(255,0,0), round_blocks=True, block_radius=1000)`
>
> Padding: `Identicon_Options(gradient=True, basecolor=(255,0,0), round_blocks=True, block_radius=1000, padding=100)`

</details>

### Backgrounds:

#### Delusional background:

<div align="center">
<table>
<tr>
<th><div align="center">Normal</div></th>
<th><div align="center">Increased depth</div></th>
<th><div align="center">Early internet effect</div></th>
<th><div align="center">Cyber effect</div></th>
<th><div align="center">Pixelated effect</div></th>
</tr>
<tr>
<td><a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/specific/delusional_background/Repattern-1.0-delulu.png"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/specific/delusional_background/Repattern-1.0-delulu.png"></a></td>
<td><a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/specific/delusional_background/Repattern-1.0-delulu-depth20.png"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/specific/delusional_background/Repattern-1.0-delulu-depth20.png"></a></td>
<td><a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/specific/delusional_background/Repattern-1.0-delulu-early.png"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/specific/delusional_background/Repattern-1.0-delulu-early.png"></a></td>
<td><a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/specific/delusional_background/Repattern-1.0-delulu-cyber.png"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/specific/delusional_background/Repattern-1.0-delulu-cyber.png"></a></td>
<td><a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/specific/delusional_background/Repattern-1.0-delulu-pix0.2.png"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/specific/delusional_background/Repattern-1.0-delulu-pix0.2.png"></a></td>
</tr>

</table>

</div>

<details>
    <summary>Options</summary>

> Seed: `Repattern-1.0-delulu`
>
> Options: (For the normal picture, just add the seed with no other modifiers)
>
> Increased depth: `Delusional_Background_Options(depth=20)`
>
> Early internet effect: `Delusional_Background_Options(early_internet_effect=True)`
>
> Cyber effect: `Delusional_Background_Options(cybercore_effect=True)`
>
> Pixelated effect: `Delusional_Background_Options(pixelated_effect=True, pixelated_strength=0.2)`

</details>

#### Psychedelic background:

<div align="center">
<table>
<tr>
<th><div align="center">Normal</div></th>
<th><div align="center">Force complex</div></th>
<th><div align="center">Early internet effect</div></th>
<th><div align="center">Cyber effect</div></th>
<th><div align="center">Pixelated effect</div></th>
</tr>
<tr>
<td><a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/specific/psychedelic_background/Repattern-1.0-psych.png"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/specific/psychedelic_background/Repattern-1.0-psych.png"></a></td>
<td><a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/specific/psychedelic_background/Repattern-1.0-psych-force_complex.png"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/specific/psychedelic_background/Repattern-1.0-psych-force_complex.png"></a></td>
<td><a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/specific/psychedelic_background/Repattern-1.0-psych-early.png"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/specific/psychedelic_background/Repattern-1.0-psych-early.png"></a></td>
<td><a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/specific/psychedelic_background/Repattern-1.0-psych-cyber.png"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/specific/psychedelic_background/Repattern-1.0-psych-cyber.png"></a></td>
<td><a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/specific/psychedelic_background/Repattern-1.0-psych-pix0.2.png"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/specific/psychedelic_background/Repattern-1.0-psych-pix0.2.png"></a></td>
</tr>

</table>

</div>

<details>
    <summary>Options</summary>

> Seed: `Repattern-1.0-psych`
>
> Options: (For the normal picture, just add the seed with no other modifiers)
>
> Force complex: `psychedelic_background_options(force_complex=True)`
>
> Early internet effect: `psychedelic_background_options(early_internet_effect=True)`
>
> Cyber effect: `psychedelic_background_options(cybercore_effect=True)`
>
> Pixelated effect: `psychedelic_background_options(pixelated_effect=True, pixelated_strength=0.2)`

</details>

### Combined (Generated identicon on top of generated background):

<div align="center">
<table>
<tr>
<th><div align="center">Delusional background</div></th>
<th><div align="center">Psychedelic background</div></th>
<th><div align="center">Delusional Gradient</div></th>
<th><div align="center">Psychedelic Gradient</div></th>
<th><div align="center">Rounded</div></th>
</tr>
<tr>
<td><a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/specific/combined/delulu/Repattern-1.0-combined-delulu.png"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/specific/combined/delulu/Repattern-1.0-combined-delulu.png"></a></td>
<td><a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/specific/combined/psychedelic/Repattern-1.0-combined-psych.png"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/specific/combined/psychedelic/Repattern-1.0-combined-psych.png"></a></td>
<td><a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/specific/combined/delulu/Repattern-1.0-combined-delulu-gradient.png"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/specific/combined/delulu/Repattern-1.0-combined-delulu-gradient.png"></a></td>
<td><a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/specific/combined/psychedelic/Repattern-1.0-combined-psych-gradient.png"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/specific/combined/psychedelic/Repattern-1.0-combined-psych-gradient.png"></a></td>
<td><a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/specific/combined/delulu/Repattern-1.0-combined-delulu-round.png"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/specific/combined/delulu/Repattern-1.0-combined-delulu-round.png"></a></td>
</tr>

<tr>
<th><div align="center">Blend alpha</div></th>
<th><div align="center">Early internet effect</div></th>
<th><div align="center">Cyber effect</div></th>
<th><div align="center">Psychedelic Gradient</div></th>
<th><div align="center">Pixelated effect</div></th>
</tr>
<tr>
<td><a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/specific/combined/delulu/Repattern-1.0-combined-delulu-blend_alpha.png"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/specific/combined/delulu/Repattern-1.0-combined-delulu-blend_alpha.png"></a></td>
<td><a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/specific/combined/psychedelic/Repattern-1.0-combined-psych-early.png"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/specific/combined/psychedelic/Repattern-1.0-combined-psych-early.png"></a></td>
<td><a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/specific/combined/delulu/Repattern-1.0-combined-delulu-cyber.png"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/specific/combined/delulu/Repattern-1.0-combined-delulu-cyber.png"></a></td>
<td><a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/specific/combined/psychedelic/Repattern-1.0-combined-psych-gradient.png"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/specific/combined/psychedelic/Repattern-1.0-combined-psych-gradient.png"></a></td>
<td><a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/specific/combined/delulu/Repattern-1.0-combined-delulu-pix.png"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/specific/combined/delulu/Repattern-1.0-combined-delulu-pix.png"></a></td>
</tr>

</table>

</div>

## Quick start

```bash
pip install repattern
```

```python
from repattern import Generate, Combined_Options

Gen = Generate(
    seed="Hi! I'm a unique seed, set me to None so I can randomize myself!",
    height=512,
    width=512,
    type="combined",
    combined_options=Combined_Options(
        # use_psychedelic_background=True,
        upscale_height=1024,
        upscale_width=1024,
        combined_cybercore_effect=True,
        combined_early_internet_effect=True,
    ),
)
Gen.save("repattern","PNG")


"""
Gen.returnBuffer("WEBP",thumb=True):
    {
        "buffer": io.BytesIO(),
        "type": "image/webp",
        "exif": {
            'seed': "Hi! I'm a unique seed, set me to None so I can randomize myself!",
            'type': 'combined',
            'combined_options': {
                'identicon_width': 512,
                'identicon_height': 512,
                'identicon_padding': 51,
                'upscale_width': 1024,
                'upscale_height': 1024,
                'combined_early_internet_effect': True,
                'combined_cybercore_effect': True
            }
        },
    }
"""

```

## Usage

### Importing

```python
from repattern import (
    Generate,
    Identicon_Options,
    Delusional_Background_Options,
    Psychedelic_Background_Options,
    Combined_Options,
)
```

### Generate

The generating class, pass a seed, width, height and a type. After passing a type you can use the corresponding class to change the generating options. E.g. `combined_options=Combined_Options(upscale_height=1024,upscale_width=1024)`

```python
Gen = Generate(
    seed="your-seed", # Leave it as None to generate a randomized seed.
    width=512,
    height=512,
    type="combined",    # "identicon" | "delusional_background" | "psychedelic_background" | "combined"
    combined_options=Combined_Options()
)
```

### Saving:

```python
Gen.save("output.png")      # PNG
Gen.save("output.jpg")      # format inferred from extension
Gen.save("output", "WEBP")  # explicit format
Gen.save()                  # saves as {seed}_{type}.png
```

### Getting a buffer (for web use, APIs, etc.):

```python
result = Gen.returnBuffer(
    typee="WEBP",   # "WEBP" | "PNG" | "JPEG"
    thumb=True      # True = quality 50 | False = quality 100
)

# returns:
# {
#     "buffer": io.BytesIO(),
#     "type": "image/webp",
#     "exif": {
#         "seed": "your-seed", # Leave it as None to generate a randomized seed
#         "type": "combined",
#         "combined_options": { ... }  # only non-default options
#     }
# }
```

> Saved images always embeds its seed and options as EXIF metadata, so any image can always be reproduced exactly.

---

> If your IDE support suggestions then you can always hover on any typed class such as [`Combined_Options()`, `Identicon_Options()`, `Psychedelic_Background_Options()`, `Delusional_Background_Options()`]
>
> to see all of the available options.

### Identicon

```python
Gen = Generate(
    seed="your-seed", # Leave it as None to generate a randomized seed
    width=512,
    height=512,
    type="identicon",
    identicon_options=Identicon_Options(

        blocks_amount=7,            # default: 7
        padding=50,                 # padding around the icon in pixels, default: 50

        mode="colored",             # "colored" | "monochrome" | "grayscale" | "pastel"
        basecolor=(255, 0, 0),      # force RGB foreground color, default: None (derived from seed)
        backgroundcolor=(0, 0, 0),  # default: black
        transparent=False,          # overrides backgroundcolor, default: False
        color_theme="warm",         # "warm" | "cool" | "forest" | "ocean" | "sunset" | None
        saturation_boost=2.0,       # only in "colored" mode, default: 2.0
        brightness_boost=1.0,       # only in "colored" mode, default: 1.0

        gradient=False,
        gradient_strength=1.0,      # default: 1.0

        round_blocks=False,
        block_radius=0.25,          # fraction of cell size, default: 0.25
        cell_variation=0,           # random size variation per block, 0.0–1.0

        pattern_mask="matrix",      # bit mask string controlling which cells can be filled
        use_alpha=True,
        seed=None,                  # override seed just for the identicon

        width=512,
        height=512,
        background_width=512,       # total output size including background
        background_height=512,
        upscale_width=1024,         # upscale after generation, default: None
        upscale_height=1024,
    )
)
```

---

### Delusional Background

```python
Gen = Generate(
    seed="your-seed", # Leave it as None to generate a randomized seed
    width=512,
    height=512,
    type="delusional_background",
    delusional_background_options=Delusional_Background_Options(
        depth=8,                    # complexity of the function tree, higher = more complex
        max_attempts=20,            # attempts to find a high-quality pattern, default: 20
        base_color=(100, 0, 200),   # tint the palette, default: None (random from seed)
        seed=None,
        width=512,
        height=512,
        upscale_width=1024,
        upscale_height=1024,
    )
)
```

---

### Psychedelic Background

```python
Gen = Generate(
    seed="your-seed", # Leave it as None to generate a randomized seed
    width=512,
    height=512,
    type="psychedelic_background",
    psychedelic_background_options=Psychedelic_Background_Options(
        depth=-4,           # negative = shallower start, default: -4
        force_complex=True, # avoids flat/simple outputs, default: False
        seed=None,
        width=512,
        height=512,
        upscale_width=1024,
        upscale_height=1024,
    )
)
```

---

### Combined

```python
Gen = Generate(
    seed="your-seed", # Leave it as None to generate a randomized seed
    width=512,
    height=512,
    type="combined",
    combined_options=Combined_Options(
        icon_seed=None,     # defaults to Generate seed
        back_seed=None,     # defaults to Generate seed

        use_psychedelic_background=False,   # use psychedelic instead of delusional

        blend_alpha=1.0,        # identicon opacity, 0.0–1.0
        blend_mode="normal",    # "normal" | "overlay" | "multiply" | "screen" | "soft_light"
        background_first=True,
        identicon_on_top=True,

        background_width=512,
        background_height=512,
        upscale_width=1024,
        upscale_height=1024,

        identicon_width=512,
        identicon_height=512,
        identicon_padding=51,
        identicon_blocks_amount=7,
        identicon_mode="colored",   # "colored" | "monochrome" | "grayscale" | "pastel"
        identicon_basecolor=None,
        identicon_backgroundcolor=(0, 0, 0),
        identicon_transparent=True, # default True in combined mode
        identicon_gradient=False,
        identicon_gradient_strength=1.0,
        identicon_color_theme=None,
        identicon_saturation_boost=2.0,
        identicon_brightness_boost=1.0,
        identicon_round_blocks=False,
        identicon_block_radius=0.25,
        identicon_cell_variation=0,
        identicon_pattern_mask="matrix",

        background_depth=8,
        background_base_color=None,
        background_max_attempts=20,

        psychedelic_background_depth=-4,
        psychedelic_background_force_complex=False,
    )
)
```

---

### Effects

Three effects are available: **Early Internet**, **Cybercore**, and **Pixelated**.

Every type supports all three effects. In `combined` mode, you can apply them per layer or on the final composited output. Each effect has a `_strength` float (0.0–1.0) to control intensity.

#### Early Internet

```python
# identicon
Identicon_Options(early_internet_effect=True, early_internet_strength=0.7)

# delusional background
Delusional_Background_Options(early_internet_effect=True, early_internet_strength=0.7)

# psychedelic background
Psychedelic_Background_Options(early_internet_effect=True, early_internet_strength=0.7)

# combined per layer
Combined_Options(
    identicon_early_internet_effect=True, identicon_early_internet_strength=0.7,
    background_early_internet_effect=True, background_early_internet_strength=0.7,
)

# combined on final output
Combined_Options(combined_early_internet_effect=True, combined_early_internet_strength=0.7)
```

#### Cybercore

```python
# identicon
Identicon_Options(cybercore_effect=True, cybercore_strength=0.7)

# delusional background
Delusional_Background_Options(cybercore_effect=True, cybercore_strength=0.7)

# psychedelic background
Psychedelic_Background_Options(cybercore_effect=True, cybercore_strength=0.7)

# combined per layer
Combined_Options(
    identicon_cybercore_effect=True, identicon_cybercore_strength=0.7,
    background_cybercore_effect=True, background_cybercore_strength=0.7,
)

# combined on final output
Combined_Options(combined_cybercore_effect=True, combined_cybercore_strength=0.7)
```

#### Pixelated

```python
# identicon
Identicon_Options(pixelated_effect=True, pixelated_strength=0.7)

# delusional background
Delusional_Background_Options(pixelated_effect=True, pixelated_strength=0.2)  # 0.2 = subtle

# psychedelic background
Psychedelic_Background_Options(pixelated_effect=True, pixelated_strength=0.7)

# combined per layer
Combined_Options(
    identicon_pixelated_effect=True, identicon_pixelated_strength=0.7,
    background_pixelated_effect=True, background_pixelated_strength=0.2,
)

# combined on final output
Combined_Options(combined_pixelated_effect=True, combined_pixelated_strength=0.7)
```

All three effects can be stacked on any layer in any combination.

```python
Gen = Generate(
    seed="your-seed", # Leave it as None to generate a randomized seed
    type="combined",
    combined_options=Combined_Options(
        use_psychedelic_background=True,
        background_early_internet_effect=True,
        background_cybercore_effect=True,
        background_pixelated_effect=True,
        background_pixelated_strength=0.2,
        combined_early_internet_effect=True,
        combined_cybercore_effect=True,
    )
)
```

## More examples

<div align="center">

#### Full seed: c69e7a2d8099d4877cdf640a8042aca348f05205a9c97a9e01

| Combined (delusional)                                                                                                                                                                                                                                             | Combined (No effects)                                                                                                                                                                                                                                                                             | Background                                                                                                                                                                                                                                                                                |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/delulu/c69e7.png" target="_blank"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/delulu/c69e7.png" width="256"></a> | <a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/delulu_without_effects/c69e7.png" target="_blank"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/delulu_without_effects/c69e7.png" width="256"></a> | <a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/backgrounds/delulu/c69e7.png" target="_blank"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/backgrounds/delulu/c69e7.png" width="256"></a> |

| Combined (distorted)                                                                                                                                                                                                                                                    | Combined (No effects)                                                                                                                                                                                                                                                                                   | Background                                                                                                                                                                                                                                                                                      |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/distorted/c69e7.png" target="_blank"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/distorted/c69e7.png" width="256"></a> | <a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/distorted_without_effects/c69e7.png" target="_blank"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/distorted_without_effects/c69e7.png" width="256"></a> | <a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/backgrounds/distorted/c69e7.png" target="_blank"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/backgrounds/distorted/c69e7.png" width="256"></a> |

#### Full seed: 2dc42bc3ede4265f41d863dece5118e1a82e5c8c69dedf9630

| Combined (delusional)                                                                                                                                                                                                                                             | Combined (No effects)                                                                                                                                                                                                                                                                             | Background                                                                                                                                                                                                                                                                                |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/delulu/2dc42.png" target="_blank"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/delulu/2dc42.png" width="256"></a> | <a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/delulu_without_effects/2dc42.png" target="_blank"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/delulu_without_effects/2dc42.png" width="256"></a> | <a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/backgrounds/delulu/2dc42.png" target="_blank"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/backgrounds/delulu/2dc42.png" width="256"></a> |

| Combined (distorted)                                                                                                                                                                                                                                                    | Combined (No effects)                                                                                                                                                                                                                                                                                   | Background                                                                                                                                                                                                                                                                                      |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/distorted/2dc42.png" target="_blank"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/distorted/2dc42.png" width="256"></a> | <a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/distorted_without_effects/2dc42.png" target="_blank"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/distorted_without_effects/2dc42.png" width="256"></a> | <a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/backgrounds/distorted/2dc42.png" target="_blank"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/backgrounds/distorted/2dc42.png" width="256"></a> |

#### Full seed: 0b37b430e0b00142cbfdd818d0e9562d9d347544079040b804

| Combined (delusional)                                                                                                                                                                                                                                             | Combined (No effects)                                                                                                                                                                                                                                                                             | Background                                                                                                                                                                                                                                                                                |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/delulu/0b37b.png" target="_blank"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/delulu/0b37b.png" width="256"></a> | <a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/delulu_without_effects/0b37b.png" target="_blank"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/delulu_without_effects/0b37b.png" width="256"></a> | <a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/backgrounds/delulu/0b37b.png" target="_blank"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/backgrounds/delulu/0b37b.png" width="256"></a> |

| Combined (distorted)                                                                                                                                                                                                                                                    | Combined (No effects)                                                                                                                                                                                                                                                                                   | Background                                                                                                                                                                                                                                                                                      |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/distorted/0b37b.png" target="_blank"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/distorted/0b37b.png" width="256"></a> | <a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/distorted_without_effects/0b37b.png" target="_blank"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/distorted_without_effects/0b37b.png" width="256"></a> | <a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/backgrounds/distorted/0b37b.png" target="_blank"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/backgrounds/distorted/0b37b.png" width="256"></a> |

#### Full seed: 600bd30349a981b924a07568e3bcd8e36a141dd048062f36e9

| Combined (delusional)                                                                                                                                                                                                                                             | Combined (No effects)                                                                                                                                                                                                                                                                             | Background                                                                                                                                                                                                                                                                                |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/delulu/600bd.png" target="_blank"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/delulu/600bd.png" width="256"></a> | <a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/delulu_without_effects/600bd.png" target="_blank"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/delulu_without_effects/600bd.png" width="256"></a> | <a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/backgrounds/delulu/600bd.png" target="_blank"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/backgrounds/delulu/600bd.png" width="256"></a> |

| Combined (distorted)                                                                                                                                                                                                                                                    | Combined (No effects)                                                                                                                                                                                                                                                                                   | Background                                                                                                                                                                                                                                                                                      |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/distorted/600bd.png" target="_blank"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/distorted/600bd.png" width="256"></a> | <a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/distorted_without_effects/600bd.png" target="_blank"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/distorted_without_effects/600bd.png" width="256"></a> | <a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/backgrounds/distorted/600bd.png" target="_blank"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/backgrounds/distorted/600bd.png" width="256"></a> |

#### Full seed: 9811657cd6ebbfdf1f862df437538a5c2c873b23badfe9a177

| Combined (delusional)                                                                                                                                                                                                                                             | Combined (No effects)                                                                                                                                                                                                                                                                             | Background                                                                                                                                                                                                                                                                                |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/delulu/98116.png" target="_blank"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/delulu/98116.png" width="256"></a> | <a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/delulu_without_effects/98116.png" target="_blank"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/delulu_without_effects/98116.png" width="256"></a> | <a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/backgrounds/delulu/98116.png" target="_blank"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/backgrounds/delulu/98116.png" width="256"></a> |

| Combined (distorted)                                                                                                                                                                                                                                                    | Combined (No effects)                                                                                                                                                                                                                                                                                   | Background                                                                                                                                                                                                                                                                                      |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/distorted/98116.png" target="_blank"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/distorted/98116.png" width="256"></a> | <a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/distorted_without_effects/98116.png" target="_blank"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/distorted_without_effects/98116.png" width="256"></a> | <a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/backgrounds/distorted/98116.png" target="_blank"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/backgrounds/distorted/98116.png" width="256"></a> |

#### Full seed: d8a4eff74fa978a5eb0aa44ecc66f4533950dc35178ad9e0de

| Combined (delusional)                                                                                                                                                                                                                                             | Combined (No effects)                                                                                                                                                                                                                                                                             | Background                                                                                                                                                                                                                                                                                |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/delulu/d8a4e.png" target="_blank"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/delulu/d8a4e.png" width="256"></a> | <a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/delulu_without_effects/d8a4e.png" target="_blank"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/delulu_without_effects/d8a4e.png" width="256"></a> | <a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/backgrounds/delulu/d8a4e.png" target="_blank"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/backgrounds/delulu/d8a4e.png" width="256"></a> |

| Combined (distorted)                                                                                                                                                                                                                                                    | Combined (No effects)                                                                                                                                                                                                                                                                                   | Background                                                                                                                                                                                                                                                                                      |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/distorted/d8a4e.png" target="_blank"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/distorted/d8a4e.png" width="256"></a> | <a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/distorted_without_effects/d8a4e.png" target="_blank"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/distorted_without_effects/d8a4e.png" width="256"></a> | <a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/backgrounds/distorted/d8a4e.png" target="_blank"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/backgrounds/distorted/d8a4e.png" width="256"></a> |

#### Full seed: 6df6e8ea26e1f7396160d9fa01a63ddb64c96b18f71efce3b8

| Combined (delusional)                                                                                                                                                                                                                                             | Combined (No effects)                                                                                                                                                                                                                                                                             | Background                                                                                                                                                                                                                                                                                |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/delulu/6df6e.png" target="_blank"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/delulu/6df6e.png" width="256"></a> | <a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/delulu_without_effects/6df6e.png" target="_blank"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/delulu_without_effects/6df6e.png" width="256"></a> | <a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/backgrounds/delulu/6df6e.png" target="_blank"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/backgrounds/delulu/6df6e.png" width="256"></a> |

| Combined (distorted)                                                                                                                                                                                                                                                    | Combined (No effects)                                                                                                                                                                                                                                                                                   | Background                                                                                                                                                                                                                                                                                      |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/distorted/6df6e.png" target="_blank"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/distorted/6df6e.png" width="256"></a> | <a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/distorted_without_effects/6df6e.png" target="_blank"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/distorted_without_effects/6df6e.png" width="256"></a> | <a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/backgrounds/distorted/6df6e.png" target="_blank"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/backgrounds/distorted/6df6e.png" width="256"></a> |

#### Full seed: 9cb376dace89ba8e4e23cd34b769e93abc18ef2a82822e8ddc

| Combined (delusional)                                                                                                                                                                                                                                             | Combined (No effects)                                                                                                                                                                                                                                                                             | Background                                                                                                                                                                                                                                                                                |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/delulu/9cb37.png" target="_blank"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/delulu/9cb37.png" width="256"></a> | <a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/delulu_without_effects/9cb37.png" target="_blank"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/delulu_without_effects/9cb37.png" width="256"></a> | <a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/backgrounds/delulu/9cb37.png" target="_blank"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/backgrounds/delulu/9cb37.png" width="256"></a> |

| Combined (distorted)                                                                                                                                                                                                                                                    | Combined (No effects)                                                                                                                                                                                                                                                                                   | Background                                                                                                                                                                                                                                                                                      |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/distorted/9cb37.png" target="_blank"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/distorted/9cb37.png" width="256"></a> | <a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/distorted_without_effects/9cb37.png" target="_blank"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/distorted_without_effects/9cb37.png" width="256"></a> | <a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/backgrounds/distorted/9cb37.png" target="_blank"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/backgrounds/distorted/9cb37.png" width="256"></a> |

#### Full seed: d4bbe906621b3c41be15988878270c10d78a4d3167bee36a9c

| Combined (delusional)                                                                                                                                                                                                                                             | Combined (No effects)                                                                                                                                                                                                                                                                             | Background                                                                                                                                                                                                                                                                                |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/delulu/d4bbe.png" target="_blank"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/delulu/d4bbe.png" width="256"></a> | <a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/delulu_without_effects/d4bbe.png" target="_blank"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/delulu_without_effects/d4bbe.png" width="256"></a> | <a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/backgrounds/delulu/d4bbe.png" target="_blank"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/backgrounds/delulu/d4bbe.png" width="256"></a> |

| Combined (distorted)                                                                                                                                                                                                                                                    | Combined (No effects)                                                                                                                                                                                                                                                                                   | Background                                                                                                                                                                                                                                                                                      |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/distorted/d4bbe.png" target="_blank"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/distorted/d4bbe.png" width="256"></a> | <a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/distorted_without_effects/d4bbe.png" target="_blank"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/distorted_without_effects/d4bbe.png" width="256"></a> | <a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/backgrounds/distorted/d4bbe.png" target="_blank"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/backgrounds/distorted/d4bbe.png" width="256"></a> |

#### Full seed: e22b2f16daa35354b47b72b3460b918f91ded5dd7ee2430ffd

| Combined (delusional)                                                                                                                                                                                                                                             | Combined (No effects)                                                                                                                                                                                                                                                                             | Background                                                                                                                                                                                                                                                                                |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/delulu/e22b2.png" target="_blank"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/delulu/e22b2.png" width="256"></a> | <a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/delulu_without_effects/e22b2.png" target="_blank"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/delulu_without_effects/e22b2.png" width="256"></a> | <a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/backgrounds/delulu/e22b2.png" target="_blank"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/backgrounds/delulu/e22b2.png" width="256"></a> |

| Combined (distorted)                                                                                                                                                                                                                                                    | Combined (No effects)                                                                                                                                                                                                                                                                                   | Background                                                                                                                                                                                                                                                                                      |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/distorted/e22b2.png" target="_blank"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/distorted/e22b2.png" width="256"></a> | <a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/distorted_without_effects/e22b2.png" target="_blank"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/distorted_without_effects/e22b2.png" width="256"></a> | <a href="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/backgrounds/distorted/e22b2.png" target="_blank"><img width="200" src="https://raw.githubusercontent.com/remohexa/repattern/main/repostuff/images/repattern/backgrounds/distorted/e22b2.png" width="256"></a> |

</div>

### Credits

`repattern` is made by [@remohexa](https://remohexa.com). and is released under [GPLv3](LICENCE) license.

### Notes

This's the first version of this project readme, expect some improvements later.
