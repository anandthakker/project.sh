
<h1 align="center">project.sh</h1>

<div align="center">
  <strong><pre>$ROOT/$ORG/REPO</pre></strong>
</div>

Tools to navigate and manage source code repositories living on GitHub.

To clone this repository for example, run:

```bash
$ clone juliangruber project.sh
```

The directory structure created is:

```
$ROOT/$ORG/$REPO
```

With $ROOT set to `~/dev/` for example, this repository will have been cloned
to `~/dev/juliangruber/project.sh`.


## Installation

```bash
source project.sh
export PROJ_ROOT=~/dev/
```

## Functions

### goto $ORG $REPO

Go to `$ROOT/$ORG/REPO`. If this directory does _not_ exist, the project will be cloned for you. This makes it the main function to use.

### clone $ORG $REPO

Clone the project from `https://github.com/$ORG/$REPO` into `$ROOT/$ORG/$REPO` and cd into the directory.

## Configuration

You only need to set `PROJ_ROOT` to your project root.

## Kudos

I picked this idea up when I was working at segment, but we never got around to publishing it.

## License

MIT
