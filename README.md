# study-cli
command line flash cards

# Installation
> pip install study-cli

To get the git version, run:

> git clone git://github.com/fawzisal/study-cli.git

## Usage

```
study [-h] [-F FILTER] [-M MODE] [-t [TAGS]] [-a ASKED] [-c CORRECT] [-s SCORE] [-o YOUNG] [-O OLD]
             [-m N_MAX] [-f [FILENAME]] [-π] [-N NEW_TERM NEW_TERM] [-d] [-b] [-L LIST]

Study some more...

optional arguments:
  -h, --help            show this help message and exit
  -F FILTER             [filter] filter (n: new; p: previously asked; h: hidden; a: all)
  -M MODE               [filter] mode (o: ordered; r: random; e: exact answers;
                                       E: exact answers if simple; r: review (scores are not stored);
                                       u: unforgiving; c: case-sensitive)
  -t [TAGS]             [filter] only include items matching tags
  -a ASKED              [filter] asked before # times
  -c CORRECT            [filter] correct before
  -s SCORE              [filter] score [0-10]
  -o YOUNG              [filter] young (<= x days old)
  -O OLD                [filter] old (> x days old)
  -m N_MAX              [filter] maximum number of questions to ask
  -f [FILENAME]         [add ] filname
  -π                    [add ] new terms (in new.json)
  -N NEW_TERM NEW_TERM  [add ] term [x] with definition [y]
  -d                    [debug ] debug mode
  -b                    [debug ] backup database
  -L LIST               [debug ] list (t: terms; i: information; c: information in csv format;
                                       T: tags; s: detailed statistics) & exit
```

To quit, enter q or press ctrl + d

## Bug reports
To report bugs, please use the chemicals's Bug Tracker at:
>    https://github.com/fawzisal/study-cli/issues

## License information
See ``LICENSE.txt`` for information on the terms & conditions for usage of this software, and a DISCLAIMER OF ALL WARRANTIES.
