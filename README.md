Screencast: https://cl.ly/0e2h1h3l1A0r

File structure

```
[benjiox:~/Code/RubyMine2017-bug] 5s % tree
.
└── interactors
    ├── add_user
    │   └── persist.rb
    └── add_user.rb

2 directories, 2 files
```

When trying to jump to source from `interactors/add_user/persist.rb` to `interactors/add_user.rb` it does not work.
Note that this work perfectly in all version of RubyMine 2016.
I've been trying all version of 2017, EAP included, and this never worked.
