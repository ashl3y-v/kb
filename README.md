# srtmy
```
x l d g w  q b o u ;
s r t m y  p n a i e
z j k c v  f h . , /
```
Pronounced: cert (as in certify) my

Whole board (no numrow flip):
```
` 1 2 3 4 5 6 7 8 9 0 { }
  x l d g w  q b o u ; = _ |
  s r t m y  p n a i e '
  z j k c v  f h . , /

~ ! @ # $ % ^ & * ( ) [ ]
  X L D G W  Q B O U : + - \
  S R T M Y  P N A I E "
  Z J K C V  F H < > ?
```

For the multiple variations available (including numrow level flip and symbols for qwerty) refer to the xkb configuration file
If I forget to update it here there may be a more up to date version in my repo called conf. The symbol alterations are what I believe will be helpful in programming (specifically the languages I use, you might want something different, e.g. [] and {}, ;/:).

Oxeylyzer:
```
graphite                       srtmy
b l d w z  ' f o u j           x l d g w  q b o u ;
n r t s g  y h a e i           s r t m y  p n a i e
q x m c v  k p . - ,           z j k c v  f h . , /
Sfb:                0.996%      Sfb:                0.762%
Dsfb:               6.260%      Dsfb:               5.705%
Finger Speed:       21.990      Finger Speed:       18.193
Scissors:           0.306%      Scissors:           0.315%
Lsbs:               1.191%      Lsbs:               1.688%
Pinky Ring Bigrams: 1.620%      Pinky Ring Bigrams: 1.142%

Inrolls:            21.54%      Inrolls:            23.07%
Outrolls:           22.93%      Outrolls:           23.79%
Total Rolls:        44.47%      Total Rolls:        46.86%
Onehands:           1.716%      Onehands:           1.778%

Alternates:         34.34%      Alternates:         29.65%
Alternates Sfs:     7.81%       Alternates Sfs:     5.77%
Total Alternates:   42.15%      Total Alternates:   35.41%

Redirects:          1.789%      Redirects:          3.080%
Redirects Sfs:      0.796%      Redirects Sfs:      2.536%
Bad Redirects:      0.264%      Bad Redirects:      0.406%
Bad Redirects Sfs:  0.133%      Bad Redirects Sfs:  0.163%
Total Redirects:    2.983%      Total Redirects:    6.186%

Bad Sfbs:           0.507%      Bad Sfbs:           0.663%
Sft:                0.025%      Sft:                0.010%
```

Oxeylyzer same punctuation:
```
graphite                       srtmy_graphite_punct
b l d w z  ' f o u j           x l d g w  q b o u '
n r t s g  y h a e i           s r t m y  p n a i e
q x m c v  k p . - ,           z j k c v  f h . , -
Sfb:                0.996%      Sfb:                0.844%
Dsfb:               6.260%      Dsfb:               5.824%
Finger Speed:       21.990      Finger Speed:       19.922
Scissors:           0.306%      Scissors:           0.366%
Lsbs:               1.191%      Lsbs:               1.688%
Pinky Ring Bigrams: 1.620%      Pinky Ring Bigrams: 1.233%

Inrolls:            21.54%      Inrolls:            23.19%
Outrolls:           22.93%      Outrolls:           24.19%
Total Rolls:        44.47%      Total Rolls:        47.38%
Onehands:           1.716%      Onehands:           1.850%

Alternates:         34.34%      Alternates:         30.07%
Alternates Sfs:     7.81%       Alternates Sfs:     5.92%
Total Alternates:   42.15%      Total Alternates:   35.99%

Redirects:          1.789%      Redirects:          3.231%
Redirects Sfs:      0.796%      Redirects Sfs:      2.571%
Bad Redirects:      0.264%      Bad Redirects:      0.413%
Bad Redirects Sfs:  0.133%      Bad Redirects Sfs:  0.169%
Total Redirects:    2.983%      Total Redirects:    6.383%

Bad Sfbs:           0.507%      Bad Sfbs:           0.715%
Sft:                0.025%      Sft:                0.012%
```

Oxey Layout Playground:
```
Finger usage:
finger 0: 	6.69% 	finger 9: 	11.89%
finger 1: 	10.31% 	finger 8: 	10.97%
finger 2: 	13.32% 	finger 7: 	16.62%
finger 3: 	12.30% 	finger 6: 	17.16%

Left hand: 42.62% 	Right hand: 56.63%
Left center: 4.794% 	Right center: 4.302%
Home keys usage: 57.14%

Sfb% per finger:
finger 0: 	0.002% 	finger 9: 	0.033%
finger 1: 	0.090% 	finger 8: 	0.129%
finger 2: 	0.014% 	finger 7: 	0.128%
finger 3: 	0.224% 	finger 6: 	0.200%

Sfb:  0.821%
Dsfb: 5.855%
Lsb:  2.993%
Inrolls: 23.125%
Outrolls: 23.757%
Total Rolls: 46.882%
Onehands: 1.860%
Alternates: 29.774%
Alternates (sfs): 5.800%
Total Alternates: 35.573%
Redirects: 5.722%
BadRedirects: 0.574%
Total Redirects: 6.295%
```

Oxeylyzer improvement gained by swapping , and .
```
srtmy_reg_punct                srtmy
x l d g w  q b o u ;           x l d g w  q b o u ;
s r t m y  p n a i e           s r t m y  p n a i e
z j k c v  f h , . /           z j k c v  f h . , /
Sfb:                0.773%      Sfb:                0.762%
Dsfb:               5.888%      Dsfb:               5.705%
Finger Speed:       18.537      Finger Speed:       18.193
Scissors:           0.324%      Scissors:           0.315%
Lsbs:               1.679%      Lsbs:               1.688%
Pinky Ring Bigrams: 1.163%      Pinky Ring Bigrams: 1.142%

Inrolls:            23.07%      Inrolls:            23.07%
Outrolls:           23.78%      Outrolls:           23.79%
Total Rolls:        46.85%      Total Rolls:        46.86%
Onehands:           1.776%      Onehands:           1.778%

Alternates:         29.63%      Alternates:         29.65%
Alternates Sfs:     5.78%       Alternates Sfs:     5.77%
Total Alternates:   35.41%      Total Alternates:   35.41%

Redirects:          3.076%      Redirects:          3.080%
Redirects Sfs:      2.541%      Redirects Sfs:      2.536%
Bad Redirects:      0.404%      Bad Redirects:      0.406%
Bad Redirects Sfs:  0.161%      Bad Redirects Sfs:  0.163%
Total Redirects:    6.183%      Total Redirects:    6.186%

Bad Sfbs:           0.668%      Bad Sfbs:           0.663%
Sft:                0.010%      Sft:                0.010%
```
