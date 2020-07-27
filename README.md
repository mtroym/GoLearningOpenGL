Learning OpenGL by Go Language.
---

For some reason, Java version (JOGL) is not maintained for now.

You should install Go Language. We suppose to use opengl binding `go-gl` to do this. This is my environment config.
```$xslt
$ go version
go version go1.13.14 darwin/amd64
```
Set up your go, modified GOROOT, GOPATH in your ide. I choose Jetbrains' intelliJ IDEA. What you only need to do is to add Go Language support via Marketplace in plugin and to config your SDK, GOPATH and GOROOT.


Install your ``go-gl``
----------
Use official Go package manager to fetch the ``go-gl`` package. Of course you will need ``glfw`` as well.
Maybe you need proxy in China.

```$xslt
$ go get -u github.com/go-gl/glfw/v3.2/glfw
$ go get -u github.com/go-gl/gl/v{3.2,3.3,4.1,4.2,4.3,4.4,4.5,4.6}-{core,compatibility}/gl
$ go get -u github.com/go-gl/gl/v3.1/gles2 
$ go get -u github.com/go-gl/gl/v2.1/gl
```

Use your ``go-gl``
----------
See tutorials for details.