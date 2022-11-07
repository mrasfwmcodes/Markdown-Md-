# Markdown (Md)
what i learned with Md


# heading
Heading atau judul di markdown dapat dibuat dengan tanda pagar `#`.

```md
# heading 1
```

```md
## heading 2
```

```md
### heading 3
```

```md
#### heading 4
```

```md
##### heading 5
```

```md
###### heading 6
```

> Alternatively, for H1 and H2, an underline-ish style:

```md
Alt-H1
======

Alt-H2
------
```

# table
cara membuat tabel sangat sederhana :


```md
Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3
```

```md
| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |
```


```md
Attempt | #1 | #2 | #3 | #4 | #5 | #6 | #7 | #8 | #9 | #10 | #11
--- | --- | --- | --- |--- |--- |--- |--- |--- |--- |--- |---
Seconds | 301 | 283 | 290 | 286 | 289 | 285 | 287 | 287 | 272 | 276 | 269
```


# Link
Link dapat kita buat dengan tanda kurung seperti ini:

```md
[link ke github mrafwmcodes](https://github.com/mrasfwmcodes)
```

atau bisa ditambahkan dengan title

```md
[link ke github mrafwmcodes](https://github.com/mrasfwmcodes/ "pergi ke github ku?")
```


# Lists
Membuat list dengan mudah contoh dibawah ini:
 
```md
1. First ordered list item
2. Another item
1. Actual numbers don't matter, just that it's a number
4. And another item.

* Unordered list can use asterisks
- Or minuses
+ Or pluses
```


⋅⋅⋅You can have properly indented paragraphs within list items. Notice the blank line above, and the leading spaces (at least one, but we'll use three here to also align the raw Markdown).

⋅⋅⋅To have a line break without a paragraph, you will need to use two trailing spaces.⋅⋅
⋅⋅⋅Note that this line is separate, but within the same paragraph.⋅⋅
⋅⋅⋅(This is contrary to the typical GFM line break behaviour, where trailing spaces are not required.)


```md
1. jam pagi
   1. sarapan
   2. sikat gigi
   3. mandi
2. jam siang
   1. belajar
   2. tidur siang
```

# Format Teks
Jika kamu ingin menulis teks tebal, miring, dan strikeline, maka bisa dilakukan seperti ini:

## Tebal
```md
**Tebal**
__teks tebal__
```


## Miring
```md
_teks miring_
*miring*
```

## Garis Tengah
```md
~~strikeline~~
```


# Footnotes
Catatan kaki adalah catatan yang berada di bagian bawah dari halaman karya ilmiah. 

```md
Here is a simple footnote[^1].

A footnote can also have multiple lines[^2].  

You can also use words, to fit your writing style more closely[^note].

[^1]: My reference.
[^2]: Every new line should be prefixed with 2 spaces.  
  This allows you to have a footnote with multiple lines.
[^note]:
    Named footnotes will still render with numbers instead of the text but allow easier identification and linking.  
    This footnote also has been made with a different syntax using 4 spaces for new lines.
```




