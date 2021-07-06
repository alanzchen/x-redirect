# x-redirect

A http(s) interface to custom url scheme.

## Usage

Let's say you have a custom url scheme that Notion refuses to accept:

`x-devonthink-item://870E7555-1953-45D6-B143-B2D857F8FD0C`

Now, append it with `x.zenan.ch/` so that it becomes:

`x.zenan.ch/x-devonthink-item://870E7555-1953-45D6-B143-B2D857F8FD0C`

This link will work with Notion and it will redirect you to `x-devonthink-item://870E7555-1953-45D6-B143-B2D857F8FD0C`.

## Motivation

Allowing custom url scheme to work cross-platform on notion.so.
