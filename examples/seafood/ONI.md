## How to spin up an ONI

Get latest version of oni-express

```shell script 
git clone https://github.com/UTS-eResearch/oni-express.git
```

This will generate a folder oni-express

Get the latest version of oni-indexer

```shell script
git clone https://github.com/UTS-eResearch/oni-indexer.git
```

```
.../oni-express
.../oni-indexer

    ** It is crucial that these two repo's are sibling folders.
```

Change directories to oni-express. This will be the main working directory of an ONI

```shell script
cd oni-express
```

Edit your config files 

Run docker-compose

```shell script
docker-compose up
```
