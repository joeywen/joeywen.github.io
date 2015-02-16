# [lovesheryl.com](http://lovesheryl.com)

My personal website , the framework where I forked from [zenorocha.com](http://zenorocha.com/).

## How it works?

I use [Jekyll](http://jekyllrb.com/), a static generator in Ruby, to create this blog.

## First steps

1. Install [Git](http://git-scm.com/downloads) and [Ruby](http://www.ruby-lang.org/pt/downloads/), in case you don't have them yet.

2. Once installed these dependencies, open up the terminal and install [Jekyll](http://jekyllrb.com/) with the following command:

  ```sh
  $ gem install jekyll
  ```

3. Now clone the project:

  ```sh
  $ git clone git@github.com:zenorocha/zenorocha.com.git
  ```

4. Navigate to the project folder:

  ```sh
  $ cd zenorocha.com
  ```

5. And finally run:

  ```sh
  $ jekyll server --watch
  ```

You'll have access to the website at `localhost:4000` :D

## Browser Support

![IE](https://cloud.githubusercontent.com/assets/398893/3528325/20373e76-078e-11e4-8e3a-1cb86cf506f0.png) | ![Chrome](https://cloud.githubusercontent.com/assets/398893/3528328/23bc7bc4-078e-11e4-8752-ba2809bf5cce.png) | ![Firefox](https://cloud.githubusercontent.com/assets/398893/3528329/26283ab0-078e-11e4-84d4-db2cf1009953.png) | ![Opera](https://cloud.githubusercontent.com/assets/398893/3528330/27ec9fa8-078e-11e4-95cb-709fd11dac16.png) | ![Safari](https://cloud.githubusercontent.com/assets/398893/3528331/29df8618-078e-11e4-8e3e-ed8ac738693f.png)
--- | --- | --- | --- | --- |
IE 8+ ✔ | Latest ✔ | Latest ✔ | Latest ✔ | Latest ✔ |

## File structure

The basic file structure for the project is organized in the following way:

```
.
|-- _includes
|-- _layouts
|-- _plugins
|-- _posts
|-- _site
|-- assets
|-- _config.yml
`-- index.html
```

### [_includes](https://github.com/zenorocha/blog/tree/master/_includes)

They're blocks of code used to generate the main page of the site ([index.html](https://github.com/zenorocha/blog/blob/master/index.html)).

### [_plugins](https://github.com/zenorocha/blog/tree/master/_plugins)

Here you'll find all plugins used.

### [_posts](https://github.com/zenorocha/blog/tree/master/_posts)

Here you'll find a list of files for each post.

### [_layouts](https://github.com/zenorocha/blog/tree/master/_layouts)

Here you'll find the default template of the application.

### _site

Here you'll find all the static files generated by Jekyll after it's execution. However, this directory is unnecessary in our model, that's why it's ignored ([.gitignore](https://github.com/zenorocha/blog/blob/master/.gitignore)).

### [assets](https://github.com/zenorocha/blog/tree/master/assets)

Here you'll find all images, CSS and JS files.

### [_config.yml](https://github.com/zenorocha/blog/blob/master/_config.yml)

It stores most of the settings of the application.

### [index.html](https://github.com/zenorocha/blog/blob/master/index.html)

It's the file responsible for all application sections.

*More information about Jekyll's file structure [here](https://github.com/mojombo/jekyll/wiki/Usage).*

## Credits

Inspired by Andy Taylor.

## License

[MIT License](http://zenorocha.mit-license.org/) © Zeno Rocha
