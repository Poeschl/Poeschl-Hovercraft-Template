# Poeschl Hovercraft Template

> This is a template repository. For use copy the whole content and remove this block comment and the screenshots.
  After that it can be adjusted to your hearts content.

This presentation is made with [hovercraft](https://github.com/regebro/hovercraft).

And is meant to be hold on a Full HD aspect ratio (otherwise all slides are looking kind of messed up)

## Screenshots

| ![Title slide](screenshots/title.png) | ![Text slide](screenshots/text.png) | ![Code slide](screenshots/code.png) |
|---------------------------------------|-------------------------------------|-------------------------------------|
## Install

For a easy installation use `pip`: `pip install hovercraft`

## Usage

To host the html-presentation just run

```bash
hovercraft presentation.rst
```

and go to http://localhost:8000

## Create PDF

To create a pdf of the presentation [decktape](https://github.com/astefanutti/decktape) can be used.
Results are mostly flanky -> Needs more love on the css.

```bash
decktape -s 1720x1080 impress http://localhost:8000 presentation.pdf
```

or docker execution

```bash
docker run --rm -t --network host -v $(pwd):/slides astefanutti/decktape -s 1720x1080 impress http://localhost:8000 presentation.pdf
```
