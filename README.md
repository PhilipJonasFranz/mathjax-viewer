# mathjax-viewer
Simple page to preview LaTeX equations and such.

## Installation

Requires Docker to be installed on your system.

Clone the repository, navigate into the root directory and run commands:

```
$ docker build -t mathjax-viewer .
$ docker run -d -it --restart unless-stopped --name="mathjax-viewer" -p 80:80 mathjax-viewer
```
