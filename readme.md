To limit the speed of a SSH session to display VT100 files properly as they would have on slower serial linues.

To simular 9600 bit/s (divide by 10 to get 960 B/s)

`cat XXXX.vt | pv --quiet --rate-limit 960`


Archive of VT100/ANSI drawings: http://artscene.textfiles.com/vt100/
