<p align="center"><a href="https://piedweb.com" rel="dofollow">
<img src="https://raw.githubusercontent.com/PiedWeb/piedweb-devoluix-theme/master/src/img/logo_title.png" width="200" height="200" alt="PiedWeb.com" />
</a></p>

# PiedWeb Bootstrap 5 Theme Component

Made for [PiedWeb CMS](https://github.com/PiedWeb/CMS) and Bootstrap / [Bootstrap 5 extended](https://github.com/PiedWeb/bootstrap5-extended)

## Installation

Get it with composer

```
composer require piedweb/theme-component-bundle
```

Edit your `config/packages/twig.yaml` and add :

```
twig:
    ...
    paths:
        ...
        "%kernel.root_dir%/../vendor/piedweb/theme-component-bundle/src/Resources/views": PiedWebCMS
        "%kernel.projet_dir%/vendor/piedweb/theme-component-bundle/src/Resources/views": PiedWebThemeComponent
```
