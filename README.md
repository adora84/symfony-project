Symfony project
===============

Cool list of public APIs: https://github.com/toddmotto/public-apis

This is just a quick example, I use the [Giphy API](https://github.com/Giphy/GiphyAPI#search-endpoint)!

## Launch the app

```shell
cd symfony-project
php bin/console server:run
firefox "localhost:8000?q=kitten"
```

Try to change the value of the `q` GET parameter :wink:.

## Understand the app

Check files `app/Resources/view/default/index.html.twig` and `src/AppBundle/Controller/DefaultController.php`
