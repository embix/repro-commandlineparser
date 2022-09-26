# repro-commandlineparser

Reproduce bug in CommandLine mentioned in [issue 851](https://github.com/commandlineparser/commandline/issues/851).

Calling the program with `-p` should work on any platform, yet with git-bash (msys/windows) we get an IOException.
