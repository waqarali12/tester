Gijeli Docker Server
=============
## Repositories

1. [GitHub Reo....]
2. [(https://registry.hub.docker.com/u/praqma/gijeli/)]

## Docker Image

Contents of this repo. are used as context for building docker image of Praqma's gijeli server.
Each change committed to this repo. triggers an automated build in jenkins from where every successful build pushes gijeli server image to Praqma's docker repo. 
Praqma's jenkins page for this job can be visited [here](http://code.praqma.net/ci/view/GiJeLi/job/GiJeLi%20Docker%20Server/)...


## Usage

You can render your Jekyll website from <site-source> by using the following command:

```
docker run --rm -v [<site-source>]:/data -p [<port>]:4000 praqma/gijeli:[<version-namber>] serve --watch --force_polling -H 0.0.0.0

```

Available is a test script for building and execution the server.

The [\<site-source>]() is the directory on the Docker host with the source for the site. The site can be view as html on [http://\<host-ip>:\<port>]()


## Support 

You are invited to seek support or put a request for new features by e-mailing our support team at [support@praqma.net]() 

_Note:_ Please, mention **Praqma/gijeli** in your subject while mailing to our support team
