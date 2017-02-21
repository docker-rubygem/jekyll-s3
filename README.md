[![Docker pulls](https://img.shields.io/docker/pulls/rubygem/jekyll-s3.svg)](https://hub.docker.com/r/rubygem/jekyll-s3/)
[![Docker Build](https://img.shields.io/docker/automated/rubygem/jekyll-s3.svg)](https://hub.docker.com/r/rubygem/jekyll-s3/)
[![Latest Tag](https://img.shields.io/github/tag/docker-rubygem/jekyll-s3.svg)](https://hub.docker.com/r/rubygem/jekyll-s3/)
[![Gem Downloads](https://img.shields.io/gem/dt/jekyll-s3.svg)](https://rubygems.org/gems/jekyll-s3/)
# jekyll-s3

Auto-Generated Docker image for jekyll-s3 to allow simple usage without installation.
It is in sync with the original gem.

This allows to use a specific version of your favorite gem and ensures that this image will be supported in future.
The image is generated automatically from a github repository by Docker Hub.
This ensures that you exactly know what is in the image and what not.

It lets you use Ruby Tools without the need to install ruby on your machine.

## Usage

Usage via file system:

`docker run -v $(pwd):/work -ti docker-gems/jekyll-s3`

Usage via Pipe:

`echo "test" | docker run -ti docker-gems/jekyll-s3`

It depends on your specific use case how your want to use it.

### Add Customization

For extension, it could be used as base image.

So instead of struggeling with the installation of a gem, just write

`FROM docker-gems/jekyll-s3`

Then add the customization.

## References

 - [Overview over other rubygem docker images](https://github.com/thinkbot/docker-rubygem)
 - [Gem](https://rubygems.org/gems/jekyll-s3/)
