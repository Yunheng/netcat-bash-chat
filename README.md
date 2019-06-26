# Netcash-Bash-Chat

## Introduction

Born out of a simple nc client with pipes...

(Technically) One-Liner Bash Chat Client for Linux using only base image packages

Features:
* AES256 Encryption with Key
* Multi-Client on single ncat server
* Text Formatting (Bold, Underline, Blink, Highlight, Colour)
* Timestamp on incoming messages

## Setup

### Server

Setting up

1. ncat --listen -p [port] --broker

### Client

1. Copy and paste script.sh into the terminal on all clients.
2. Change the nc IP Address and port to the server

## Usage

`*bold*` - Bolds Text

`%highlight%` - Inverts Text

`_underline_` - Underline Text

`^blink^` - Blink

`@[colour code]` - Colour code according to what bash supports
