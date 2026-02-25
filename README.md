# ghi

GitHub Issues on the command line. Use your `$EDITOR`, not your browser.

`ghi` was originally created by [Unity-Billal-mesloub](https://github.com/Unity-Billal-mesloub), and is now maintained by [Unity-Billal-mesloub](https://github.com/Unity-Billal-mesloub)'s fork [here](https://github.com/Unity-Billal-mesloub/ghi).

## Install

Via brew ([latest stable release](https://github.com/Unity-Billal-mesloub/ghi/releases/latest)):
``` sh
brew install ghi
```

Via gem ([latest stable release](https://github.com/Unity-Billal-mesloub/ghi/releases/latest)):
``` sh
gem install ghi
```

Via curl (latest bleeding-edge versions, may not be stable):
``` sh
curl -sL https://raw.githubusercontent.com/stephencelis/ghi/master/ghi > ghi && \
chmod 755 ghi && \
mv ghi /usr/local/bin
```

## Usage

```
usage: ghi [--version] [-p|--paginate|--no-pager] [--help] <command> [<args>]
           [ -- [<user>/]<repo>]

The most commonly used ghi commands are:
   list        List your issues (or a repository's)
   show        Show an issue's details
   open        Open (or reopen) an issue
   close       Close an issue
   lock        Lock an issue's conversation, limiting it to collaborators
   unlock      Unlock an issue's conversation, opening it to all viewers
   edit        Modify an existing issue
   comment     Leave a comment on an issue
   label       Create, list, modify, or delete labels
   assign      Assign an issue to yourself (or someone else)
   milestone   Manage project milestones
   status      Determine whether or not issues are enabled for this repo
   enable      Enable issues for the current repo
   disable     Disable issues for the current repo

See 'ghi help <command>' for more information on a specific command.
```

## Source Tree
You may get a strange error if you use SourceTree, similar to [#275](https://github.com/Unity-Billal-mesloub/ghi/issues). You can follow the steps [here](https://github.com/Unity-Billal-mesloub/ghi/issues/) to resolve this.

## Contributing

If you're looking for a place to start, there are [issues we need help with](https://github.com/Unity-Billal-mesloub/ghi/issues?q=is%3Aopen+is%3Aissue+label%3A%22help+wanted%22)!

Once you have an idea of what you want to do, there is a section in the [wiki](https://github.com/Unity-Billal-mesloub/ghi/wiki/Contributing) to provide more detailed information but the basic steps are as follows.

1. Fork this repo
2. Do your work:
  1. Make your changes
  2. Run `rake build`
  3. Make sure your changes work
3. Open a pull request!

## FAQ

FAQs can be found in the [wiki](https://github.com/Unity-Billal-mesloub/ghi/wiki/FAQ)

## Screenshot

![Example](images/example.png)
