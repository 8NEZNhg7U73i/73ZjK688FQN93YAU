# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | Php removed | GB freed | GB free
ubuntu-18.04 |  |  |  |  | 7 | 49
ubuntu-18.04 |  |  | true |  | 9 | 51
ubuntu-18.04 |  | true |  |  | 11 | 53
ubuntu-18.04 |  | true | true |  | 13 | 55
ubuntu-18.04 | true |  |  |  | 18 | 60
ubuntu-18.04 | true |  | true |  | 20 | 62
ubuntu-18.04 | true | true |  |  | 21 | 63
ubuntu-18.04 | true | true | true |  | 23 | 65
ubuntu-20.04 |  |  |  |  | 7 | 45
ubuntu-20.04 |  |  | true |  | 9 | 47
ubuntu-20.04 |  | true |  |  | 11 | 49
ubuntu-20.04 |  | true | true |  | 13 | 51
ubuntu-20.04 | true |  |  |  | 19 | 57
ubuntu-20.04 | true |  | true |  | 21 | 59
ubuntu-20.04 | true | true |  |  | 23 | 61
ubuntu-20.04 | true | true | true |  | 25 | 63
