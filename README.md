getting-started-java
======================

A sample application in Java for wercker.

This application uses the `openjdk` container obtained from the [Docker Hub](https://registry.hub.docker.com/_/openjdk/)

## Setup & Build
Clone this repo and cd into the directory:

```
> git clone git@github.com:wercker/getting-started-java.git
> cd getting-started-java
```

then build using:

```
> wercker build
```

## Run
To run the application, simply execute:

```
> wercker dev --expose-ports
```

Now point your browser at `http://localhost:8080` to see:
```
Hello World!
```

---
Sign up for wercker [here](http://wercker.com)
Learn more on our [dev center](http://devcenter.wercker.com)
