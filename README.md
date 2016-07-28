# LabUtilities
Melting pot of useful scripts from lab members

## For the initial clone

Once you clone this repository, `cd` into it and run the following command:

```shell
git submodule update --init --recursive
```

**This only needs to be done once**


## Updating the submodules

To update each submodule, run the following command from the `LabUtilities` directory:

```shell
git submodule foreach git pull origin master
```

You can then commit and push these changes so everyone else gets access to these updates:

```shell
git commit -am "Update utilities directories"
git push
```
