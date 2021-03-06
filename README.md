# wavtobeep
Converts a wav file to a sequence of *beep* PC-speaker calls through frequency analysis using the fft transform.

## Getting started

1. Install python, [scipy](https://pypi.python.org/pypi/scipy) and the beep packages.
2. Download the script.
3. Check the PC-speaker module is loaded<sup>1</sup>:
    `~$ modprobe pcspkr`
4. Run!
    `~$ python wavtobeep.py [-h] [-w TIME] [--verbose] [--silent] wav_file`
 
#### Lovely example included!

 `~$ python wavtobeep.py monkey-island-sample.wav`
 
 <img src="http://25.media.tumblr.com/tumblr_l2x51ruzhE1qbpj1fo1_400.gif" height="200" />
 *Stan is happy with the PC Speaker version of his favourite song!*
 
<sup>[1] In case you don't have a PC Speaker (too bad!), you can hear the result of the automatic conversion here https://clyp.it/wsslu5xs</sup>

