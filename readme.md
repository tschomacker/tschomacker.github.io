## Update the theme

Go to the themes folder as in the installation and run the following command.

```sh
git pull
```

## Run example site

Go to the `exampleSite` folder from the theme `themes/raditian-free-hugo-theme/exampleSite` and run the following command.

```sh
hugo server --themesDir ../..
```

## Add pictures etc.

Go to the `static` folder

## TODO
edit client-and-work line 38 <br>
ask for change of the icon set to fontawesome icons

## Add HTML in yaml
```html
        <p class="lead">
          {{ .Site.Data.homepage.showcase.description | safeHTML }}
        </p>
```

## Add URL in yaml
relative URLS -> {{ .URL | relURL }} <br>
absolute URLS -> {{ .URL | absURL }} <br>

## Check config.toml
e.g. adding another icon set