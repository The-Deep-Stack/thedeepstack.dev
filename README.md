# thedeepstack.dev

The canonical website and technical publication for The Deep Stack.

## Local development

```sh
hugo mod get
hugo server
```

The site uses Hugo with PaperMod as an upstream module and custom local layouts
for The Deep Stack's Journal + Operations Console visual system.

## Newsletter

Set `params.kitFormAction` in `hugo.yaml` to the form action supplied by Kit.
Until then, subscription calls to action lead to the newsletter information
page without collecting addresses.
