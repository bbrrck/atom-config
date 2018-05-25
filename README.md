# atom-config

## Set Up

```bash
git clone git@github.com:bbrrck/atom-config.git ~/.atom
cd ~/.atom
apm install --packages-file my-packages.txt
```

## Generate list of packages

```bash
cd ~/.atom
ls packages | xargs -n 1 echo | cut -d/ -f1 > my-packages.txt
```

README from [ksindi/atom-config](https://github.com/ksindi/atom-config)
