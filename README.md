# DownLoad TranScript (DLTS) Natural Language Processing Project

This tool leverages a YouTube Transcript Downloader tool and prototypes some linguistic analysis.

## Install

* Python 3.x
* `pip3 install -r /requirements.txt`


## Usage

`python3 dlts <youtube-hash> (<...more hashes>)`


## Example

Get yourself a list of YouTube hashes that have Closed Captioning.  I've only ever used this to run profiles of people or people in channels.

So take for example some hashes that you gather about someone... just append them to the command like so:

```
python3 dlts x5XUNkpuW7s SWPvVsVj_rU H52W87A2-L0 VAWWqu3c4FY qnjYyfkcaNI
```

The sample output:

```
Bigrams:

high school
fun size
youtube channel
please subscribe
lift miss
yoga mat
channel new
new videos
my youtube
known as
some sort
handing out
at least
videos every
make sure
how much
let me
every day
gym bro
really good
thinking about
...


Trigrams:

my youtube channel
new videos every
this lift miss
please subscribe to
reps for Jesus
...
```


