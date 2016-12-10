# -={ mediawiki-loader }=- [DEMO](https://chrisbo246.github.io/mediawiki-loader/)


Import a Wikipedia article in your website using the Mediawiki API.

## Features

- Import a full article in a container.
- Fix links.
- Remove unnecessary text (contribution links, messages, etc...)
- Generate an excerpt without additional request.

### Requirements

- jQuery

## Install

Using Bower (or download the zip from Github).

```
bower install --save chrisbo246/mediawiki-loader
```

Load the **mediawiki-loader.js** script.

```
<script src="/bower_components/mediawiki-loader/src/scripts/mediawiki-loader.js"></script>
```

Import the **variables.scss** and **mediawiki-loader.scss** in your SASS file to cleanup the article of every Wikipedia annotations and make small style adjustments.

```
@import "/bower_components/mediawiki-loader/src/styles/variables.scss";
@import "/bower_components/mediawiki-loader/src/styles/mediawiki-loader.scss";
```

## Usage

Add a container with **.mediawiki-container** class and a **data-url**.

```
<div class="mediawiki-container" data-url="https://en.wikipedia.org/wiki/Google"></div>
```

If you need an excerpt on the same page without having to make a second request, simply add a second container with a **.mediawiki-excerpt** class.

```
<div class="mediawiki-excerpt"></div>
```

Don't forget to insert the required mention to the Wikipedia article.

```
<div class="mediawiki-mention">
    <a href="https://en.wikipedia.org/wiki/Google" target="_blank">https://en.wikipedia.org/wiki/Google</a>
</div>
```

<!--

## Contributing
Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

-->

## Bugs

Please use the [GitHub issue tracker](https://github.com/chrisbo246/pickyvagabond/issues) for all bugs and feature requests. Before creating a new issue, do a quick search to see if the problem has been reported already.

<!--

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

-->
