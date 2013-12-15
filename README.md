haskell-base Cookbook
=============
haskell cookbook to install ghc/cabal/haskell-platform

Requirements
------------

#### support os
- ubuntu
- debian

Attributes
----------
* default['haskell']['user'] : set user name
* default['haskell']['dir'] : specify install directory

Usage
-----

#### haskell-base::default

```json
{
  "haskell": {
    "user":'vagrant',
    "dir":'/home/vagrant'
  },
  "run_list": [
    "haskell-base"
  ]
}
```

Contributing
------------

1. Fork the repository on Github
2. Create a named feature branch (like `add_component_x`)
3. Write your change
4. Write tests for your change (if applicable)
5. Run the tests, ensuring they all pass
6. Submit a Pull Request using Github

License and Authors
-------------------
Authors: cosmo0920
