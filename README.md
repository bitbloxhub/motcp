# `MOTCP`: Messages Over TCP


## About

With `MOTCP`, you can send messages in [BSON](https://bsonspec.org/) over a `TCP` connection.

If you need encryption, we reccomend [ghosttunnel](https://github.com/ghostunnel/ghostunnel).

## A Message

A message is composed of a 32-bit `length`, and a `length` bytes message in BSON

## The Protocol

The client can send messages to the server simply by sending the mesage over tcp to the server, and vice versa
