<h1><img width="200px" alt="Sass" src="https://rawgit.com/sass/sass-site/master/source/assets/img/logos/logo.svg" /></h1>

**Sass makes CSS fun again**. Sass is an extension of CSS, adding nested rules,
variables, mixins, selector inheritance, and more. It's translated to
well-formatted, standard CSS using the command line tool or a plugin for your
build system.

## Install Sass

You can install Sass on Windows, Mac, or Linux by downloading the package for
your operating system [from GitHub][] and [adding it to your `PATH`][path].
That's all—there are no external dependencies and nothing else you need to
install.

[from github]: https://github.com/sass/dart-sass/releases/tag/1.1.1
[path]: https://katiek2.github.io/path-doc/

If you use Node.js, you can also install Sass using [npm][] by running

[npm]: https://www.npmjs.com/

```
npm install -g sass
```

**However, please note** that this will install the pure JavaScript
implementation of Sass, which runs somewhat slower than the other options listed
here. But it has the same interface, so it'll be easy to swap in another
implementation later if you need a bit more speed!

See [the Sass website](https://sass-lang.com/install) for more ways to install
Sass.

Once you have Sass installed, you can run the `sass` executable to compile
`.sass` and `.scss` files to `.css` files. For example:

```
sass source/stylesheets/index.scss build/stylesheets/index.css
```

## Learn Sass

Check out [the Sass website](https://sass-lang.com/guide) for a guide on how to
learn Sass!

## This Repository

This repository is a simple boilerplate template to get you started with sass.

## Development setup

Before cloning this repo:

1.  Have Git installed.

Run Git bash or your terminal.
Goto the directory that you want to store the files

```sh
git clone https://github.com/Warui-K/sass-css.git
```

2. Compile the sass

 On your terminal run

 ```sh
 sass --watch scss/style.scss css/style.css

 ```
 You can add your scss code in the style.scss file
## View the frontpage

Open your browser and go to your_directory/index.html

## Release History

- 1.0.0
  - Work in progress

## Contributing

1. Fork it (<https://github.com/Warui-K/sass-css.git>)
2. Create your feature branch (`git checkout -b feature/fooBar`)
3. Commit your changes (`git commit -am 'Add some fooBar'`)
4. Push to the branch (`git push origin feature/fooBar`)
5. Create a new Pull Request

## Branch Naming conventions

Branches created are named using the following format:

```
{story type}-{descriptive-branch-name}
```

`story-type` - Indicates the context of the branch and are one of:

- ft == Feature
- bg == Bug
- ch == Chore
- rf == Refactor

`descriptive-branch-name` - Short 2-3 words summary about what the branch contains

### PR Naming

The PR title should be named using the following format:

```
#[ID] Story description
```

**Example**

```
#57 Add functionas & hooks feature
```

### PR Description Template (Markdown)

The description of the PR should contain the following headings and corresponding content in Markdown format.

```md
#### What does this PR do?

#### Description of Task to be completed?

#### How should this be manually tested?

#### Any background context you want to provide?

#### What are the relevant trello cards?

#### Screenshots (if appropriate)

#### Questions:
```

### Commits

Atomic commits should be made with the format:

```
<type>(<scope>): <subject>``<BLANK LINE> <body> <BLANK LINE> <footer>

```

Any line cannot be longer than 100 characters, meaning be concise.

`<type>` should be:

- feature - ft
- bug - bg
- chore - ch
- release -rlse
- refactor - rf
- documentation -doc
- style -sty
- test -tst

`<scope>` should be something specific to the commit change. For example:

costume

- flight
- fighting-style
- fan-base
- logo and so on.

`<subject>` text should:

- use present tense: "save" not "saved" or "saving"
- not capitalize first letter i.e no "Carry to safety"
- not end with a dot (.)

**Message body (optional)** If a body is to be written, it should:

- written in present tense.
- include the reason for change and difference in the previous behaviour

**Message Footer** This should be used for referencing the issues using the following keywords: Start, Delivers, Fixes and Finishes. it should be inside a square bracket. Example:

```
[Start #34]
```

or in a case of multiple issues:

```
[Finishes #65, #56, #46]
```

## Example

chore(coveralls):add coveralls yml  
[Finishes #4]

## Acknowlegnements

"Sass Crash course tutorial - Brad Traversy of Traversy Media
Course link : https://www.youtube.com/watch?v=nu5mdN2JIwM

## License

MIT License

Copyright (c) 2020 Warui Kamiri
