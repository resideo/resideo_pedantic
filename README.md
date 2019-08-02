# Resideo's common pedantic options

A common pedantic configuration for all of Resideo's Dart/Flutter packages.

## Installation

Include this package under your dev dependencies in `pubspec.yaml`:

```yaml
dev_dependencies:
  resideo_pedantic:
    git:
      url: git@github.com:resideo/resideo_pedantic.git
```

> This can replace `pedantic` if it is listed in your pubspec already.

Then include the options in your `analysis_options.yaml`:

```yaml
include: package:resideo_pedantic/analysis_options.yaml
```

> This can replace `pedantic` if it is listed in your options already.
