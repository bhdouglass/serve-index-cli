# Serve Index CLI

A simple way to serve a directory listing, similar to http-server.
This is just a small wrapper around [serve-index](https://github.com/expressjs/serve-index),
it uses serve-index for all the heavy lifting.

## Install

`npm install -g serve-index-cli`

## Basic Usage

`serve-index`

By default serve-index-cli only listens on localhost:3000 and servers the current directory.

## Extended Usage

All args are optional

`serve-index --port 3000 --ip 0.0.0.0 --dir="/path/to/awesome/files/" --icons=false --hidden=true --stylesheet="files.css" --template="index.html" --view="details"`

For more information about the options, check the [serve-index](https://github.com/expressjs/serve-index) configuration options.

## License

Copyright (C) 2016 [Brian Douglass](http://bhdouglass.com/)

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License version 3, as published
by the Free Software Foundation.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranties of MERCHANTABILITY, SATISFACTORY QUALITY, or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program.  If not, see <http://www.gnu.org/licenses/>.
