# srtmy
```
x l d g w  q b o u ;
s r t m y  p n a i e
z j k c v  f h , . /
```
Pronounced: cert (as in certify) my

For the entire board and the multiple variations available (including numrow flip and symbols for qwerty) refer to the xkb configuration file
If I forget to update it here there may be a more up to date version in my repo called conf. The symbol alterations are what I believe will be helpful in programming (specifically the languages I use, you might want something different). I have both qwerty, qwerty with srtmy symbols, and srtmy, the first as a backup and also because I need the numrow to switch, the second to help me learn the symbols even if I'm not ready to use srtmy yet. Swapping the positions of , and . yields meaningful improvements in oxeylyzer but I'm skeptical of the real world value, and for me it's more work than it's worth (you can see these results if you scroll down).

Oxeylyzer:
```
graphite                       srtmy
b l d w z  ' f o u j           x l d g w  q b o u ;
n r t s g  y h a e i           s r t m y  p n a i e
q x m c v  k p . - ,           z j k c v  f h , . /
Sfb:                0.996%      Sfb:                0.773%
Dsfb:               6.260%      Dsfb:               5.888%
Finger Speed:       21.990      Finger Speed:       18.537
Scissors:           0.306%      Scissors:           0.324%
Lsbs:               1.191%      Lsbs:               1.679%
Pinky Ring Bigrams: 1.620%      Pinky Ring Bigrams: 1.163%

Inrolls:            21.54%      Inrolls:            23.07%
Outrolls:           22.93%      Outrolls:           23.78%
Total Rolls:        44.47%      Total Rolls:        46.85%
Onehands:           1.716%      Onehands:           1.776%

Alternates:         34.34%      Alternates:         29.63%
Alternates Sfs:     7.81%       Alternates Sfs:     5.78%
Total Alternates:   42.15%      Total Alternates:   35.41%

Redirects:          1.789%      Redirects:          3.076%
Redirects Sfs:      0.796%      Redirects Sfs:      2.541%
Bad Redirects:      0.264%      Bad Redirects:      0.404%
Bad Redirects Sfs:  0.133%      Bad Redirects Sfs:  0.161%
Total Redirects:    2.983%      Total Redirects:    6.183%

Bad Sfbs:           0.507%      Bad Sfbs:           0.668%
Sft:                0.025%      Sft:                0.010%
```

Oxeylyzer same punctuation:
```
srtmy1                         graphite
x l d g w  q b o u '           b l d w z  ' f o u j
s r t m y  p n a i e           n r t s g  y h a e i
z j k c v  f h . , -           q x m c v  k p . - ,
Sfb:                0.844%      Sfb:                0.996%
Dsfb:               5.824%      Dsfb:               6.260%
Finger Speed:       19.922      Finger Speed:       21.990
Scissors:           0.366%      Scissors:           0.306%
Lsbs:               1.688%      Lsbs:               1.191%
Pinky Ring Bigrams: 1.233%      Pinky Ring Bigrams: 1.620%

Inrolls:            23.19%      Inrolls:            21.54%
Outrolls:           24.19%      Outrolls:           22.93%
Total Rolls:        47.38%      Total Rolls:        44.47%
Onehands:           1.850%      Onehands:           1.716%

Alternates:         30.07%      Alternates:         34.34%
Alternates Sfs:     5.92%       Alternates Sfs:     7.81%
Total Alternates:   35.99%      Total Alternates:   42.15%

Redirects:          3.231%      Redirects:          1.789%
Redirects Sfs:      2.571%      Redirects Sfs:      0.796%
Bad Redirects:      0.413%      Bad Redirects:      0.264%
Bad Redirects Sfs:  0.169%      Bad Redirects Sfs:  0.133%
Total Redirects:    6.383%      Total Redirects:    2.983%

Bad Sfbs:           0.715%      Bad Sfbs:           0.507%
Sft:                0.012%      Sft:                0.025%
```

Oxey Layout Playground:
```
Finger usage:
finger 0: 	6.69% 	finger 9: 	11.89%
finger 1: 	10.31% 	finger 8: 	11.05%
finger 2: 	13.32% 	finger 7: 	16.53%
finger 3: 	12.30% 	finger 6: 	17.16%

Left hand: 42.62% 	Right hand: 56.63%
Left center: 4.794% 	Right center: 4.302%
Home keys usage: 57.14%

Sfb% per finger:
finger 0: 	0.002% 	finger 9: 	0.033%
finger 1: 	0.090% 	finger 8: 	0.138%
finger 2: 	0.014% 	finger 7: 	0.130%
finger 3: 	0.224% 	finger 6: 	0.200%

Sfb:  0.832%
Dsfb: 6.051%
Lsb:  2.984%
Inrolls: 23.128%
Outrolls: 23.743%
Total Rolls: 46.871%
Onehands: 1.859%
Alternates: 29.762%
Alternates (sfs): 5.811%
Total Alternates: 35.573%
Redirects: 5.723%
BadRedirects: 0.569%
Total Redirects: 6.293%
```

Oxeylyzer improvement gained by swapping , and . (I'm skeptical that this can actually matter that much, especially when programming)
```
srtmy                          srtmy2
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
