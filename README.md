## install_repos
Install repositories for your RedHat based OS.

### Why?
I got tired of having to track down, download and then install keys and rpms
or download files. This automates much of that.

### ...
This was developed using CentOS over the course of the last few years and is
tailored to my specific needs.

I'm quite willing to accept pull requests--that's why I made this public.

I hope you get as much use out of it as I do.

### Usage
  Usage:
    install_repos -l|--list
      List known repository names.
  
    install_repos -n repo1 repo2
      Install specified repositories.
      If -n is included then don't really install, just show what would have been done.
  
    install_repos -n -a|--all [repo1 repo2]
      Install all known repositories. Any repositories listed will not be installed.
      If -n is included then don't really install, just show what would have been done.
  
    install_repos -h|--help
      This help text.
