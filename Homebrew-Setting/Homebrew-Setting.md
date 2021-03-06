# Homebrew Setting

## __1. Homebrew Site__
> https://brew.sh/index_ko

<br>

## __2. Homebrew Install Command__
```bash
$ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
==> Checking for `sudo` access (which may request your password)...
$ Password: [계정의 Password]
```

<br>

## __3. Homebrew Install Console__

<details markdown="1">
<summary><span style="color:green">Success</span></summary>

```bash
==> This script will install:
/usr/local/bin/brew
/usr/local/share/doc/homebrew
/usr/local/share/man/man1/brew.1
/usr/local/share/zsh/site-functions/_brew
/usr/local/etc/bash_completion.d/brew
/usr/local/Homebrew
==> The following new directories will be created:
/usr/local/bin
/usr/local/etc
/usr/local/include
/usr/local/lib
/usr/local/sbin
/usr/local/share
/usr/local/var
/usr/local/opt
/usr/local/share/zsh
/usr/local/share/zsh/site-functions
/usr/local/var/homebrew
/usr/local/var/homebrew/linked
/usr/local/Cellar
/usr/local/Caskroom
/usr/local/Frameworks
==> The Xcode Command Line Tools will be installed.

Press RETURN/ENTER to continue or any other key to abort:
==> /usr/bin/sudo /bin/mkdir -p /usr/local/bin /usr/local/etc /usr/local/include /usr/local/lib /usr/local/sbin /usr/local/share /usr/local/var /usr/local/opt /usr/local/share/zsh /usr/local/share/zsh/site-functions /usr/local/var/homebrew /usr/local/var/homebrew/linked /usr/local/Cellar /usr/local/Caskroom /usr/local/Frameworks
==> /usr/bin/sudo /bin/chmod ug=rwx /usr/local/bin /usr/local/etc /usr/local/include /usr/local/lib /usr/local/sbin /usr/local/share /usr/local/var /usr/local/opt /usr/local/share/zsh /usr/local/share/zsh/site-functions /usr/local/var/homebrew /usr/local/var/homebrew/linked /usr/local/Cellar /usr/local/Caskroom /usr/local/Frameworks
==> /usr/bin/sudo /bin/chmod go-w /usr/local/share/zsh /usr/local/share/zsh/site-functions
==> /usr/bin/sudo /usr/sbin/chown "계정이름" /usr/local/bin /usr/local/etc /usr/local/include /usr/local/lib /usr/local/sbin /usr/local/share /usr/local/var /usr/local/opt /usr/local/share/zsh /usr/local/share/zsh/site-functions /usr/local/var/homebrew /usr/local/var/homebrew/linked /usr/local/Cellar /usr/local/Caskroom /usr/local/Frameworks
==> /usr/bin/sudo /usr/bin/chgrp admin /usr/local/bin /usr/local/etc /usr/local/include /usr/local/lib /usr/local/sbin /usr/local/share /usr/local/var /usr/local/opt /usr/local/share/zsh /usr/local/share/zsh/site-functions /usr/local/var/homebrew /usr/local/var/homebrew/linked /usr/local/Cellar /usr/local/Caskroom /usr/local/Frameworks
==> /usr/bin/sudo /bin/mkdir -p /usr/local/Homebrew
==> /usr/bin/sudo /usr/sbin/chown -R "계정이름":admin /usr/local/Homebrew
==> /usr/bin/sudo /bin/mkdir -p /Users/"계정이름"/Library/Caches/Homebrew
==> /usr/bin/sudo /bin/chmod g+rwx /Users/"계정이름"/Library/Caches/Homebrew
==> /usr/bin/sudo /usr/sbin/chown -R "계정이름" /Users/"계정이름"/Library/Caches/Homebrew
==> Searching online for the Command Line Tools
==> /usr/bin/sudo /usr/bin/touch /tmp/.com.apple.dt.CommandLineTools.installondemand.in-progress


==> Installing Command Line Tools for Xcode-13.3
==> /usr/bin/sudo /usr/sbin/softwareupdate -i Command\ Line\ Tools\ for\ Xcode-13.3
Software Update Tool

Finding available software


Downloading Command Line Tools for Xcode
Downloaded Command Line Tools for Xcode
Installing Command Line Tools for Xcode
Done with Command Line Tools for Xcode
Done.
==> /usr/bin/sudo /usr/bin/xcode-select --switch /Library/Developer/CommandLineTools
==> /usr/bin/sudo /bin/rm -f /tmp/.com.apple.dt.CommandLineTools.installondemand.in-progress
==> Downloading and installing Homebrew...
remote: Enumerating objects: 207371, done.
remote: Counting objects: 100% (65/65), done.
remote: Compressing objects: 100% (57/57), done.
remote: Total 207371 (delta 6), reused 60 (delta 6), pack-reused 207306
Receiving objects: 100% (207371/207371), 57.37 MiB | 10.07 MiB/s, done.
Resolving deltas: 100% (152565/152565), done.
From https://github.com/Homebrew/brew
 * [new branch]          dependabot/bundler/Library/Homebrew/rubocop-1.28.2  -> origin/dependabot/bundler/Library/Homebrew/rubocop-1.28.2
 * [new branch]          dependabot/bundler/Library/Homebrew/sorbet-0.5.9976 -> origin/dependabot/bundler/Library/Homebrew/sorbet-0.5.9976
 * [new branch]          master                                              -> origin/master
 * [new tag]             0.1                                                 -> 0.1
 * [new tag]             0.2                                                 -> 0.2
 * [new tag]             0.3                                                 -> 0.3
 * [new tag]             0.4                                                 -> 0.4
 * [new tag]             0.5                                                 -> 0.5
 * [new tag]             0.6                                                 -> 0.6
 * [new tag]             0.7                                                 -> 0.7
 * [new tag]             0.7.1                                               -> 0.7.1
 * [new tag]             0.8                                                 -> 0.8
 * [new tag]             0.8.1                                               -> 0.8.1
 * [new tag]             0.9                                                 -> 0.9
 * [new tag]             0.9.1                                               -> 0.9.1
 * [new tag]             0.9.2                                               -> 0.9.2
 * [new tag]             0.9.3                                               -> 0.9.3
 * [new tag]             0.9.4                                               -> 0.9.4
 * [new tag]             0.9.5                                               -> 0.9.5
 * [new tag]             0.9.8                                               -> 0.9.8
 * [new tag]             0.9.9                                               -> 0.9.9
 * [new tag]             1.0.0                                               -> 1.0.0
 * [new tag]             1.0.1                                               -> 1.0.1
 * [new tag]             1.0.2                                               -> 1.0.2
 * [new tag]             1.0.3                                               -> 1.0.3
 * [new tag]             1.0.4                                               -> 1.0.4
 * [new tag]             1.0.5                                               -> 1.0.5
 * [new tag]             1.0.6                                               -> 1.0.6
 * [new tag]             1.0.7                                               -> 1.0.7
 * [new tag]             1.0.8                                               -> 1.0.8
 * [new tag]             1.0.9                                               -> 1.0.9
 * [new tag]             1.1.0                                               -> 1.1.0
 * [new tag]             1.1.1                                               -> 1.1.1
 * [new tag]             1.1.10                                              -> 1.1.10
 * [new tag]             1.1.11                                              -> 1.1.11
 * [new tag]             1.1.12                                              -> 1.1.12
 * [new tag]             1.1.13                                              -> 1.1.13
 * [new tag]             1.1.2                                               -> 1.1.2
 * [new tag]             1.1.3                                               -> 1.1.3
 * [new tag]             1.1.4                                               -> 1.1.4
 * [new tag]             1.1.5                                               -> 1.1.5
 * [new tag]             1.1.6                                               -> 1.1.6
 * [new tag]             1.1.7                                               -> 1.1.7
 * [new tag]             1.1.8                                               -> 1.1.8
 * [new tag]             1.1.9                                               -> 1.1.9
 * [new tag]             1.2.0                                               -> 1.2.0
 * [new tag]             1.2.1                                               -> 1.2.1
 * [new tag]             1.2.2                                               -> 1.2.2
 * [new tag]             1.2.3                                               -> 1.2.3
 * [new tag]             1.2.4                                               -> 1.2.4
 * [new tag]             1.2.5                                               -> 1.2.5
 * [new tag]             1.2.6                                               -> 1.2.6
 * [new tag]             1.3.0                                               -> 1.3.0
 * [new tag]             1.3.1                                               -> 1.3.1
 * [new tag]             1.3.2                                               -> 1.3.2
 * [new tag]             1.3.3                                               -> 1.3.3
 * [new tag]             1.3.4                                               -> 1.3.4
 * [new tag]             1.3.5                                               -> 1.3.5
 * [new tag]             1.3.6                                               -> 1.3.6
 * [new tag]             1.3.7                                               -> 1.3.7
 * [new tag]             1.3.8                                               -> 1.3.8
 * [new tag]             1.3.9                                               -> 1.3.9
 * [new tag]             1.4.0                                               -> 1.4.0
 * [new tag]             1.4.1                                               -> 1.4.1
 * [new tag]             1.4.2                                               -> 1.4.2
 * [new tag]             1.4.3                                               -> 1.4.3
 * [new tag]             1.5.0                                               -> 1.5.0
 * [new tag]             1.5.1                                               -> 1.5.1
 * [new tag]             1.5.10                                              -> 1.5.10
 * [new tag]             1.5.11                                              -> 1.5.11
 * [new tag]             1.5.12                                              -> 1.5.12
 * [new tag]             1.5.13                                              -> 1.5.13
 * [new tag]             1.5.14                                              -> 1.5.14
 * [new tag]             1.5.2                                               -> 1.5.2
 * [new tag]             1.5.3                                               -> 1.5.3
 * [new tag]             1.5.4                                               -> 1.5.4
 * [new tag]             1.5.5                                               -> 1.5.5
 * [new tag]             1.5.6                                               -> 1.5.6
 * [new tag]             1.5.7                                               -> 1.5.7
 * [new tag]             1.5.8                                               -> 1.5.8
 * [new tag]             1.5.9                                               -> 1.5.9
 * [new tag]             1.6.0                                               -> 1.6.0
 * [new tag]             1.6.1                                               -> 1.6.1
 * [new tag]             1.6.10                                              -> 1.6.10
 * [new tag]             1.6.11                                              -> 1.6.11
 * [new tag]             1.6.12                                              -> 1.6.12
 * [new tag]             1.6.13                                              -> 1.6.13
 * [new tag]             1.6.14                                              -> 1.6.14
 * [new tag]             1.6.15                                              -> 1.6.15
 * [new tag]             1.6.16                                              -> 1.6.16
 * [new tag]             1.6.17                                              -> 1.6.17
 * [new tag]             1.6.2                                               -> 1.6.2
 * [new tag]             1.6.3                                               -> 1.6.3
 * [new tag]             1.6.4                                               -> 1.6.4
 * [new tag]             1.6.5                                               -> 1.6.5
 * [new tag]             1.6.6                                               -> 1.6.6
 * [new tag]             1.6.7                                               -> 1.6.7
 * [new tag]             1.6.8                                               -> 1.6.8
 * [new tag]             1.6.9                                               -> 1.6.9
 * [new tag]             1.7.0                                               -> 1.7.0
 * [new tag]             1.7.1                                               -> 1.7.1
 * [new tag]             1.7.2                                               -> 1.7.2
 * [new tag]             1.7.3                                               -> 1.7.3
 * [new tag]             1.7.4                                               -> 1.7.4
 * [new tag]             1.7.5                                               -> 1.7.5
 * [new tag]             1.7.6                                               -> 1.7.6
 * [new tag]             1.7.7                                               -> 1.7.7
 * [new tag]             1.8.0                                               -> 1.8.0
 * [new tag]             1.8.1                                               -> 1.8.1
 * [new tag]             1.8.2                                               -> 1.8.2
 * [new tag]             1.8.3                                               -> 1.8.3
 * [new tag]             1.8.4                                               -> 1.8.4
 * [new tag]             1.8.5                                               -> 1.8.5
 * [new tag]             1.8.6                                               -> 1.8.6
 * [new tag]             1.9.0                                               -> 1.9.0
 * [new tag]             1.9.1                                               -> 1.9.1
 * [new tag]             1.9.2                                               -> 1.9.2
 * [new tag]             1.9.3                                               -> 1.9.3
 * [new tag]             2.0.0                                               -> 2.0.0
 * [new tag]             2.0.1                                               -> 2.0.1
 * [new tag]             2.0.2                                               -> 2.0.2
 * [new tag]             2.0.3                                               -> 2.0.3
 * [new tag]             2.0.4                                               -> 2.0.4
 * [new tag]             2.0.5                                               -> 2.0.5
 * [new tag]             2.0.6                                               -> 2.0.6
 * [new tag]             2.1.0                                               -> 2.1.0
 * [new tag]             2.1.1                                               -> 2.1.1
 * [new tag]             2.1.10                                              -> 2.1.10
 * [new tag]             2.1.11                                              -> 2.1.11
 * [new tag]             2.1.12                                              -> 2.1.12
 * [new tag]             2.1.13                                              -> 2.1.13
 * [new tag]             2.1.14                                              -> 2.1.14
 * [new tag]             2.1.15                                              -> 2.1.15
 * [new tag]             2.1.16                                              -> 2.1.16
 * [new tag]             2.1.2                                               -> 2.1.2
 * [new tag]             2.1.3                                               -> 2.1.3
 * [new tag]             2.1.4                                               -> 2.1.4
 * [new tag]             2.1.5                                               -> 2.1.5
 * [new tag]             2.1.6                                               -> 2.1.6
 * [new tag]             2.1.7                                               -> 2.1.7
 * [new tag]             2.1.8                                               -> 2.1.8
 * [new tag]             2.1.9                                               -> 2.1.9
 * [new tag]             2.2.0                                               -> 2.2.0
 * [new tag]             2.2.1                                               -> 2.2.1
 * [new tag]             2.2.10                                              -> 2.2.10
 * [new tag]             2.2.11                                              -> 2.2.11
 * [new tag]             2.2.12                                              -> 2.2.12
 * [new tag]             2.2.13                                              -> 2.2.13
 * [new tag]             2.2.14                                              -> 2.2.14
 * [new tag]             2.2.15                                              -> 2.2.15
 * [new tag]             2.2.16                                              -> 2.2.16
 * [new tag]             2.2.17                                              -> 2.2.17
 * [new tag]             2.2.2                                               -> 2.2.2
 * [new tag]             2.2.3                                               -> 2.2.3
 * [new tag]             2.2.4                                               -> 2.2.4
 * [new tag]             2.2.5                                               -> 2.2.5
 * [new tag]             2.2.6                                               -> 2.2.6
 * [new tag]             2.2.7                                               -> 2.2.7
 * [new tag]             2.2.8                                               -> 2.2.8
 * [new tag]             2.2.9                                               -> 2.2.9
 * [new tag]             2.3.0                                               -> 2.3.0
 * [new tag]             2.4.0                                               -> 2.4.0
 * [new tag]             2.4.1                                               -> 2.4.1
 * [new tag]             2.4.10                                              -> 2.4.10
 * [new tag]             2.4.11                                              -> 2.4.11
 * [new tag]             2.4.12                                              -> 2.4.12
 * [new tag]             2.4.13                                              -> 2.4.13
 * [new tag]             2.4.14                                              -> 2.4.14
 * [new tag]             2.4.15                                              -> 2.4.15
 * [new tag]             2.4.16                                              -> 2.4.16
 * [new tag]             2.4.2                                               -> 2.4.2
 * [new tag]             2.4.3                                               -> 2.4.3
 * [new tag]             2.4.4                                               -> 2.4.4
 * [new tag]             2.4.5                                               -> 2.4.5
 * [new tag]             2.4.6                                               -> 2.4.6
 * [new tag]             2.4.7                                               -> 2.4.7
 * [new tag]             2.4.8                                               -> 2.4.8
 * [new tag]             2.4.9                                               -> 2.4.9
 * [new tag]             2.5.0                                               -> 2.5.0
 * [new tag]             2.5.1                                               -> 2.5.1
 * [new tag]             2.5.10                                              -> 2.5.10
 * [new tag]             2.5.11                                              -> 2.5.11
 * [new tag]             2.5.12                                              -> 2.5.12
 * [new tag]             2.5.2                                               -> 2.5.2
 * [new tag]             2.5.3                                               -> 2.5.3
 * [new tag]             2.5.4                                               -> 2.5.4
 * [new tag]             2.5.5                                               -> 2.5.5
 * [new tag]             2.5.6                                               -> 2.5.6
 * [new tag]             2.5.7                                               -> 2.5.7
 * [new tag]             2.5.8                                               -> 2.5.8
 * [new tag]             2.5.9                                               -> 2.5.9
 * [new tag]             2.6.0                                               -> 2.6.0
 * [new tag]             2.6.1                                               -> 2.6.1
 * [new tag]             2.6.2                                               -> 2.6.2
 * [new tag]             2.7.0                                               -> 2.7.0
 * [new tag]             2.7.1                                               -> 2.7.1
 * [new tag]             2.7.2                                               -> 2.7.2
 * [new tag]             2.7.3                                               -> 2.7.3
 * [new tag]             2.7.4                                               -> 2.7.4
 * [new tag]             2.7.5                                               -> 2.7.5
 * [new tag]             2.7.6                                               -> 2.7.6
 * [new tag]             2.7.7                                               -> 2.7.7
 * [new tag]             3.0.0                                               -> 3.0.0
 * [new tag]             3.0.1                                               -> 3.0.1
 * [new tag]             3.0.10                                              -> 3.0.10
 * [new tag]             3.0.11                                              -> 3.0.11
 * [new tag]             3.0.2                                               -> 3.0.2
 * [new tag]             3.0.3                                               -> 3.0.3
 * [new tag]             3.0.4                                               -> 3.0.4
 * [new tag]             3.0.5                                               -> 3.0.5
 * [new tag]             3.0.6                                               -> 3.0.6
 * [new tag]             3.0.7                                               -> 3.0.7
 * [new tag]             3.0.8                                               -> 3.0.8
 * [new tag]             3.0.9                                               -> 3.0.9
 * [new tag]             3.1.0                                               -> 3.1.0
 * [new tag]             3.1.1                                               -> 3.1.1
 * [new tag]             3.1.10                                              -> 3.1.10
 * [new tag]             3.1.11                                              -> 3.1.11
 * [new tag]             3.1.12                                              -> 3.1.12
 * [new tag]             3.1.2                                               -> 3.1.2
 * [new tag]             3.1.3                                               -> 3.1.3
 * [new tag]             3.1.4                                               -> 3.1.4
 * [new tag]             3.1.5                                               -> 3.1.5
 * [new tag]             3.1.6                                               -> 3.1.6
 * [new tag]             3.1.7                                               -> 3.1.7
 * [new tag]             3.1.8                                               -> 3.1.8
 * [new tag]             3.1.9                                               -> 3.1.9
 * [new tag]             3.2.0                                               -> 3.2.0
 * [new tag]             3.2.1                                               -> 3.2.1
 * [new tag]             3.2.10                                              -> 3.2.10
 * [new tag]             3.2.11                                              -> 3.2.11
 * [new tag]             3.2.12                                              -> 3.2.12
 * [new tag]             3.2.13                                              -> 3.2.13
 * [new tag]             3.2.14                                              -> 3.2.14
 * [new tag]             3.2.15                                              -> 3.2.15
 * [new tag]             3.2.16                                              -> 3.2.16
 * [new tag]             3.2.17                                              -> 3.2.17
 * [new tag]             3.2.2                                               -> 3.2.2
 * [new tag]             3.2.3                                               -> 3.2.3
 * [new tag]             3.2.4                                               -> 3.2.4
 * [new tag]             3.2.5                                               -> 3.2.5
 * [new tag]             3.2.6                                               -> 3.2.6
 * [new tag]             3.2.7                                               -> 3.2.7
 * [new tag]             3.2.8                                               -> 3.2.8
 * [new tag]             3.2.9                                               -> 3.2.9
 * [new tag]             3.3.0                                               -> 3.3.0
 * [new tag]             3.3.1                                               -> 3.3.1
 * [new tag]             3.3.10                                              -> 3.3.10
 * [new tag]             3.3.11                                              -> 3.3.11
 * [new tag]             3.3.12                                              -> 3.3.12
 * [new tag]             3.3.13                                              -> 3.3.13
 * [new tag]             3.3.14                                              -> 3.3.14
 * [new tag]             3.3.15                                              -> 3.3.15
 * [new tag]             3.3.16                                              -> 3.3.16
 * [new tag]             3.3.2                                               -> 3.3.2
 * [new tag]             3.3.3                                               -> 3.3.3
 * [new tag]             3.3.4                                               -> 3.3.4
 * [new tag]             3.3.5                                               -> 3.3.5
 * [new tag]             3.3.6                                               -> 3.3.6
 * [new tag]             3.3.7                                               -> 3.3.7
 * [new tag]             3.3.8                                               -> 3.3.8
 * [new tag]             3.3.9                                               -> 3.3.9
 * [new tag]             3.4.0                                               -> 3.4.0
 * [new tag]             3.4.1                                               -> 3.4.1
 * [new tag]             3.4.10                                              -> 3.4.10
 * [new tag]             3.4.2                                               -> 3.4.2
 * [new tag]             3.4.3                                               -> 3.4.3
 * [new tag]             3.4.4                                               -> 3.4.4
 * [new tag]             3.4.5                                               -> 3.4.5
 * [new tag]             3.4.6                                               -> 3.4.6
 * [new tag]             3.4.7                                               -> 3.4.7
 * [new tag]             3.4.8                                               -> 3.4.8
 * [new tag]             3.4.9                                               -> 3.4.9
HEAD is now at 2392078ad Merge pull request #13230 from thezeroalpha/master
==> Tapping homebrew/core
remote: Enumerating objects: 1188675, done.
remote: Counting objects: 100% (239/239), done.
remote: Compressing objects: 100% (114/114), done.
remote: Total 1188675 (delta 149), reused 210 (delta 125), pack-reused 1188436
Receiving objects: 100% (1188675/1188675), 475.09 MiB | 10.13 MiB/s, done.
Resolving deltas: 100% (823971/823971), done.
From https://github.com/Homebrew/homebrew-core
 * [new branch]              master     -> origin/master
HEAD is now at 1275cbf2cb0 click: update 0.6.1 bottle.
==> Installation successful!

==> Homebrew has enabled anonymous aggregate formulae and cask analytics.
Read the analytics documentation (and how to opt-out) here:
  https://docs.brew.sh/Analytics
No analytics data has been sent yet (nor will any be during this install run).

==> Homebrew is run entirely by unpaid volunteers. Please consider donating:
  https://github.com/Homebrew/brew#donations

==> Next steps:
- Run brew help to get started
- Further documentation:
    https://docs.brew.sh
```

## __설치 성공__
- 입력
```bash
$ brew -v
```
- 출력
```bash
Homebrew 3.4.10
Homebrew/homebrew-core (git revision 1275cbf2cb0; last commit 2022-05-07)
```

</details>



<details markdown="1">
<summary><span style="color:red">Fail</span></summary>

```bash
/usr/local/bin/brew
/usr/local/share/doc/homebrew
/usr/local/share/man/man1/brew.1
/usr/local/share/zsh/site-functions/_brew
/usr/local/etc/bash_completion.d/brew
/usr/local/Homebrew
==> The following new directories will be created:
/usr/local/bin
/usr/local/etc
/usr/local/include
/usr/local/lib
/usr/local/sbin
/usr/local/share
/usr/local/var
/usr/local/opt
/usr/local/share/zsh
/usr/local/share/zsh/site-functions
/usr/local/var/homebrew
/usr/local/var/homebrew/linked
/usr/local/Cellar
/usr/local/Caskroom
/usr/local/Frameworks
==> The Xcode Command Line Tools will be installed.
Press RETURN/ENTER to continue or any other key to abort:
```
## __설치 실패__
- 입력
```bash
brew -v
```
- 출력
```bash
zsh: command not found: brew
```
</details>

