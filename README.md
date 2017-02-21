## About

Simple shell script that automatically installs the latest version of PhpMyAdmin on a Laravel Homestead box.

## Usage

1. SSH into your Homestead box using `homestead ssh` or `vagrant ssh`
2. `cd` to your code/projects directory (by default `~/Code`)
3. `$ curl -sS https://raw.githubusercontent.com/meness/pma/master/pma.sh | sh`
4. Open the `/etc/hosts` file on your main machine and add `127.0.0.1  phpmyadmin.app`
5. Go to [http://phpmyadmin.app:8000](http://phpmyadmin.app:8000). Default credentials are username `homestead` and password `secret`

## License

> MIT License

> Copyright (c) 2017 Alireza Eskandarpour Shoferi

> Permission is hereby granted, free of charge, to any person obtaining a copy
> of this software and associated documentation files (the "Software"), to deal
> in the Software without restriction, including without limitation the rights
> to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
> copies of the Software, and to permit persons to whom the Software is
> furnished to do so, subject to the following conditions:

> The above copyright notice and this permission notice shall be included in all
> copies or substantial portions of the Software.

> THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
> IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
> FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
> AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
> LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
> OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
> SOFTWARE.