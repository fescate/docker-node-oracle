# docker-node-oracle


Docker image to be used for building a container ready with Oracle instant client binaries and all necessary environment variables needed to use the primary Node.js Oracle Database driver librarie

[node-oracledb](https://github.com/oracle/node-oracledb)


## Usage

Within your Dockerfile:

```
FROM fescate/docker-node-oracle
```


## Versions

Edit the docker file with your prefered node version and make a build

```
FROM node:{VERSION}
```


### :latest

Using "latest" (FROM fescate/docker-node-oracle) as the version will use "FROM NODE:6" as it's base image.  It is recommended that you use a specific version (X.X.X) but if you only want the latest version of Node 6.X.X then latest will work.


### forked from
https://github.com/CollinEstes/docker-node-oracle/branches