FROM ubuntu:latest

RUN apt-get update && apt-get upgrade &&\
	apt-get install -y software-properties-common &&\
	apt-get install -y python-software-properties &&\
	apt-get install -y python-dev python-pip python3-dev python3-pip &&\
	add-apt-repository -y ppa:neovim-ppa/stable &&\
	apt-get update &&\
	apt-get install -y neovim

# TODO: install Golang, install neovim config and plugins.

