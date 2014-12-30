# Chomado

Chomado command

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'chomado', :git => "git://github.com/tbpgr/chomado.git"
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install specific_install
    $ gem specific_install -l "git://github.com/tbpgr/chomado.git"

## Usage

### commands

~~~bash
$ chomad commands
commands
homo
lolita
~~~

### homo

~~~bash
$ chomad homo
(^o^)ホモォ...
~~~

### lolita

~~~bash
$ chomad lolita
はるかぜﾀｿ ﾊｧﾊｧ
~~~

### help

~~~bash
$chomado help
Commands:
  chomado commands        # show subcommands
  chomado excel           # chomado hate excel
  chomado help [COMMAND]  # Describe available commands or one specific command
  chomado homo            # chomado love homo
  chomado lolita          # chomado love lolita
  chomado version         # version

Options:
  -h, [--help], [--no-help]        # help message.
      [--version], [--no-version]  # version
~~~

## Contributing

1. Fork it ( https://github.com/tbpgr/chomado/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request
