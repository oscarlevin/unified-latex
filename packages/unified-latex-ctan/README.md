<!-- DO NOT MODIFY -->
<!-- This file was autogenerated by build-docs.ts -->
<!-- Edit the docstring in index.ts and regenerate -->
<!-- rather than editing this file directly. -->
# unified-latex-ctan

## What is this?

Macro/environment definitions and utilities for specific LaTeX packages from CTAN.

Note: basic LaTeX macro/environment definitions come from the `latex2e` package, even though
this is technically not a CTAN "package".

## When should I use this?

If you want information about special functions/macros from particular CTAN packages, or
you need to parse special environments.

## Install

```bash
npm install @unified-latex/unified-latex-ctan
```

This package contains both esm and commonjs exports. To explicitly access the esm export,
import the `.js` file. To explicitly access the commonjs export, import the `.cjs` file.

# Constants

| Name              | Type                                                                                                                                                                             | Description                                                                                                          |
| :---------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------- |
| `environmentInfo` | `{ cleveref: EnvInfoRecord; exam: EnvInfoRecord; geometry: EnvInfoRecord; hyperref: EnvInfoRecord; latex2e: EnvInfoRecord; ... 6 more ...; xparse: EnvInfoRecord; }`             | Info about the environments for available ctan packages. `latex2e` contains&#xA;the standard environments for LaTeX. |
| `macroInfo`       | `{ cleveref: MacroInfoRecord; exam: MacroInfoRecord; geometry: MacroInfoRecord; hyperref: MacroInfoRecord; latex2e: MacroInfoRecord; ... 6 more ...; xparse: MacroInfoRecord; }` | Info about the macros for available ctan packages. `latex2e` contains&#xA;the standard macros for LaTeX.             |