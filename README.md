
<h1 align="center">
  <br>
  <img src="https://img.salih.co/liman/logo.png" alt="Liman" width="200">
  <br>
  Liman
  <br>
</h1>

<h4 align="center">Basic docker monitoring web application. Written with Go.</h4>

<p align="center">
  <a href="https://travis-ci.org/salihciftci/liman">
    <img src="https://travis-ci.org/salihciftci/liman.svg?branch=master"
         alt="Travis-CI">
  </a>
  <a href="https://goreportcard.com/report/github.com/salihciftci/liman">
      <img src="https://goreportcard.com/badge/github.com/salihciftci/liman">
  </a>
  <a href="http://makeapullrequest.com">
    <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg">
  </a>
</p>

![screenshot](https://img.salih.co/liman/featured.png)

## Features

* Containers - See containers statuses
* Stats - Monitor container's stats
* Logs - See container logs
* Images - See images
* Volumes - See volumes

## Installation

Liman works with host and docker container.

### Docker

```
docker pull salihciftci/liman
docker run -dit --name liman -e pass=PASS -v /var/run/docker.sock:/var/run/docker.sock salihciftci/liman
```

## Host

You can download the lastest version of liman from releases. Or you can build with Go.

```
go get github.com/salihciftci/liman
make build
```

### Screenshots

 <table border="1">
  <tr>
    <td><img src="https://img.salih.co/liman/containers.png"></td>
    <td><img src="https://img.salih.co/liman/stats.png"></td>
  </tr>
  <tr>
    <td><img src="https://img.salih.co/liman/logs.png"></td>
    <td><img src="https://img.salih.co/liman/images.png"></td>
  </tr>
  <tr>
    <td><img src="https://img.salih.co/liman/volumes.png"></td>
    <td><img src="https://img.salih.co/liman/login.png"></td>
  </tr>
</table> 

## License

MIT