# a2gif

a2gif is a script for generating GIF animations from asciicast JSON files.

## Installation

Clone the repository:

    git clone https://github.com/asciinema/a2gif.git

Install leiningen & compile scripts:

    TODO: describe

Install dependencies (PhantomJS):

    npm install

## Usage

    a2gif [-t theme] [-s speed] [-S scale] [-w cols] [-h rows] <input-json-path-or-url> <output-gif-path>

For example:

    a2gif https://asciinema.org/a/42383.json output.gif
    a2gif -t solarized-dark -s 2 -S 1 -w 80 -h 24 demo.json output.gif

## License

Copyright &copy; 2017 Marcin Kulik.
