<div align="center">
  <img src="https://user-images.githubusercontent.com/11348/52080254-520cb580-2565-11e9-8c21-156cf0b7bcf3.png" width="600" />
  <p><br />This repository is the stable base upon which we build our Elixir projects at Mirego.<br />We want to share it with the world so you can build awesome Elixir applications too.</p>
  <a href="https://travis-ci.com/mirego/elixir-boilerplate"><img src="https://travis-ci.com/mirego/elixir-boilerplate.svg?branch=master" /></a>
</div>

## Content

This boilerplate comes with batteries included, you’ll find:

- [Phoenix](https://phoenixframework.org), the battle-tested production-ready web framework
- Database integration using [Ecto](https://hexdocs.pm/ecto)
- GraphQL API setup with [Absinthe](https://hexdocs.pm/absinthe), [Absinthe.Plug](https://hexdocs.pm/absinthe_plug), [Dataloader](https://hexdocs.pm/dataloader) and [AbsintheErrorPayload](https://hexdocs.pm/absinthe_error_payload)
- Translations with [Gettext](https://hexdocs.pm/gettext)
- [ExUnit](https://hexdocs.pm/ex_unit) tests, factories using [ExMachina](https://hexdocs.pm/ex_machina) and code coverage using [ExCoveralls](https://hexdocs.pm/excoveralls)
- CORS management with [Corsica](https://github.com/whatyouhide/corsica)
- Opinionated linting with [Credo](http://credo-ci.org)
- Security scanning with [Sobelow](https://hexdocs.pm/sobelow)
- OTP release using [Distillery](https://hexdocs.pm/distillery) and [Docker](https://www.docker.com)
- Useful utilities for web features: Basic authentication with [BasicAuth](https://hexdocs.pm/basic_auth), canonical host with [PlugCanonicalHost](https://hexdocs.pm/plug_canonical_host), etc.
- Error reporting with [Sentry](https://hexdocs.pm/sentry)
- A clean and useful `README.md` template (in both [english](./BOILERPLATE_README.md) and [french](./BOILERPLATE_README.fr.md))

## Usage

### With GitHub template

1. Click on the [**Use this template**](https://github.com/mirego/elixir-boilerplate/generate) button to create a new repository
2. Clone your newly created project (`git clone https://github.com/you/repo.git`)
3. Run the boilerplate setup script (`./boilerplate-setup.sh YourProjectName`)
4. Commit the changes (`git commit -a -m "Rename elixir-boilerplate parts"`)

### Without GitHub template

1. Clone this project (`git clone https://github.com/mirego/elixir-boilerplate.git`)
2. Delete the internal Git directory (`rm -rf .git`)
3. Run the boilerplate setup script (`./boilerplate-setup.sh YourProjectName`)
4. Create a new Git repository (`git init`)
5. Create the initial Git commit (`git commit -a -m "Initial commit"`)

## License

Elixir Boilerplate is © 2017-2019 [Mirego](https://www.mirego.com) and may be freely distributed under the [New BSD license](http://opensource.org/licenses/BSD-3-Clause). See the [`LICENSE.md`](https://github.com/mirego/elixir-boilerplate/blob/master/LICENSE.md) file.

The drop logo is based on [this lovely icon by Creative Stall](https://thenounproject.com/term/drop/174999), from The Noun Project. Used under a [Creative Commons BY 3.0](http://creativecommons.org/licenses/by/3.0/) license.

## About Mirego

[Mirego](https://www.mirego.com) is a team of passionate people who believe that work is a place where you can innovate and have fun. We’re a team of [talented people](https://life.mirego.com) who imagine and build beautiful Web and mobile applications. We come together to share ideas and [change the world](http://www.mirego.org).

We also [love open-source software](https://open.mirego.com) and we try to give back to the community as much as we can.
