# Oh My ZSH plugin for Elixir, IEX, Mix and Phoenix

Terminal shortcuts for Elixir developers.

## Install and run
```
cd ~/.oh-my-zsh/custom/plugins
git clone https://github.com/gusaiani/elixir-oh-my-zsh.git elixir
```

Enable it by adding _elixir_ to the [_plugins array_](https://github.com/robbyrussell/oh-my-zsh/blob/master/templates/zshrc.zsh-template#L48).

## Aliases

| Alias                    | Command                          |
| :------------------------| :--------------------------------|
| i                        | iex                              |
| ism                      | iex -S mix                       |
| ips                      | iex -S mix phoenix.server        |
| m                        | mix                              |
| mc                       | mix compile                      |
| mho                      | mix hex.outdated                 |
| mn                       | mix new                          |
| mns                      | mix new --sup                    |
| mr                       | mix run                          |
| mrnh                     | mix run --no-halt                |
| mt                       | mix test                         |
| mdc                      | mix deps.compile                 |
| mdg                      | mix deps.get                     |
| mdgc                     | mix do deps.get, deps.compile    |
| mdun                     | mix deps.unlock                  |
| mduu                     | mix deps.unlock --unused         |
| mdu                      | mix deps.update                  |
| mdua                     | mix deps.update --all            |
| meb                      | mix escript.build                |
| mec                      | mix ecto.create                  |
| mem                      | mix ecto.migrate                 |
| mecm                     | mix do ecto.create, ecto.migrate |
| mpn                      | mix phoenix.new                  |
| mps                      | mix phoenix.server               |
| mpr                      | mix phoenix.routes               |
| mpgm                     | mix phoenix.gen.model            |
| mpgh                     | mix phoenix.gen.html             |
| mpgj                     | mix phoenix.gen.json             |
| mpgc                     | mix phoenix.gen.channel          |
| hrmec                    | heroku run mix ecto.create       |
| hrmem                    | heroku run mix ecto.migrate      |
