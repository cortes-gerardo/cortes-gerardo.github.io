# cortes-gerardo.github.io
_Resume / Portfolio / Blog_
## Description
This is a personal static site using [Jekyll](https://jekyllrb.com/) to showcase my _Resume / Portfolio / Blog_, you can see the result at [cortes-gerardo.github.io](https://cortes-gerardo.github.io/)

---

## Getting Started
### Prerequisites
- [Docker](https://www.docker.com/): Instead of having to install Ruby and all the gems, I prefer to use docker to keep my PC clean.

### Local Development
For compiling and running the server localy you need to excecute this line 
```bash
# navigate into the project directory
$ cd cortes-gerardo.github.io

# run the container, it starts the server and keep looking for local code changes  
$ docker run --name jekyll --volume="$PWD:/srv/jekyll" -p 8080:4000 -it jekyll/jekyll:latest jekyll serve --watch --drafts
```
the server will be running in [localhost:8080](http://localhost:8080/)

### Code Style
This project works mostly by editting [Markdown](https://jekyllrb.com/docs/configuration/markdown)

For commits, I recomend to use the following [git-styleguide](https://udacity.github.io/git-styleguide/)

---

## Authors
[Gerardo Cortés Oquendo](mailto:gerardo.cortes.o@gmail.com)

## Acknowledgments
- [Thomas Bradley](https://www.youtube.com/playlist?list=PLWjCJDeWfDdfVEcLGAfdJn_HXyM4Y7_k-)
- [Davy De Waele](https://ddewaele.github.io/running-jekyll-in-docker/)