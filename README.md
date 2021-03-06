# yoshino-cli
help personalize components of Yoshino!

## Getting Started

```
npm install -g yoshino-cli

yoshino init // init local backup

yoshino update // update local backup

yoshino new <component> // create your component
```

## Scripts
### init
Please do this when you firstly install yoshino-cli.

it will init local backup.
```
yoshino init
```

### update
do this when yoshino updates!
```
yoshino update
```

### new
create personalized components of yoshino.The default output directory is `components`.
```
yoshino new <component>
```
you can use `--output` to customize the output directory!
```
yoshino new Alert --output mycomponents
```

### all
output all components
```
yoshino all
```
you can use `--output` to customize the output directory!
```
yoshino all --output mycomponents
```
output theme, eg: `yoshino-theme-template`
```
yoshino all --output mycomponents --theme yoshino-theme-template
```

### -ts
-ts --typescript
output `.tsx`,default output `.js`
```
yoshino new Button -ts
```