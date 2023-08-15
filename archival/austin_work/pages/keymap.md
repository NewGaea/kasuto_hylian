# Hylian Typing - Key and Character Map

So you've downloaded one of the Hylian fonts available here or on [kasuto.net](http://kasuto.net), and it looks cool, but you aren't sure how to get all of the Hylian letters to show up? This is the place to be, my friend: there are three types of fonts available, and each uses its own mapping of keystrokes to Hylian letters, but this is the place to learn how to type all of them.

## Keymaps

The three font mappings are Kasuto's Original, Kasuto Unicode, and Conlang Script Unicode Mapping. Kasuto's Original keymap is a Windows-1252 character map using various aliases to represent the non-Latin letters present in Hylian. Though Windows-1252 is long out of date, this is the encoding still used on Kasuto's website, and is maintained for legacy purposes. If you ever spot errors on the original website, this is the reason -- change your browser to read the pages as Windows-1252 and it should display properly. Kasuto Unicode is a mapping based on Kasuto's Original, but using UTF-8 encoded Unicode text (which is, by and large, the standard for the modern internet) and diacritics to allow most properly transcribed Hylian text to display properly -- provided that the transcription uses one Latin character per Hylian character. Both of these keymaps allow you to type Hylian with a standard keyboard and, at most, an International keymap available with your OS -- the US International keymap will allow every character to be properly typed.

Finally, Conlang Script Unicode Mapping uses a reserved private-use area of Unicode to store the letters, and uses a custom keymap that you will need to install: the brand new US Hylian keymap. The advantage to this mapping is that you can include Hylian text in the same font as other languages, such as Japanese, English, or Tengwar (J.R.R. Tolkien's script created for Elvish writing). The disadvantage is that the so-called ConScript Unicode Registry is entirely unofficial and is, at the best, a guideline that serves only for those languages included in it. The keymap will also use whatever characters are stored in the current font at the addresses it looks for, so you will need a CSUR-mapped Hylian font.

### For Font-Makers

If you wish to contribute a font, it should follow the layouts presented in the [font mapping](font_mapping.md) page. Kasuto Original fonts should overwrite the normal ASCII Latin letters outlined there, Kasuto Unicode fonts should use the extended Latin map, and CSUR Mapping should use the dedicated region outlined.

## The Charts

Below is a table (and an image) for each of the keymaps. The tables assume you are using a U.S. keyboard with the QWERTY layout.

Default Keystrokes:

| \` | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 0 | - | = | BKSP |<br />
| TAB | q | w | e | r | t | y | u | i | o | p | \[ | \] | \\ |<br />
| CAP | a | s | d | f | g | h | j | k | l | ; | ' | ENTER |<br />
| SHIFT | z | x | c | v | b | n | m | , | . | / | SHIFT |<br />
| CTRL | WIN | ALT | SPACE | ALT | WIN | ALTGR | CTRL |

Shift Keystrokes:

| ~ | ! | @ | # | $ | % | ^ | \& | \* | ( | ) | \_ | + | BKSP |<br />
| TAB | Q | W | E | R | T | Y | U | I | O | P | \{ | \} | \| |<br />
| CAP | A | S | D | F | G | H | J | K | L | : | \" | ENTER |<br />
| SHIFT | Z | X | C | V | B | N | M | \< | \> | ? | SHIFT |<br />
| CTRL | WIN | ALT | SPACE | ALT | WIN | ALTGR | CTRL |

If you are using a different keyboard layout, the Kasuto style charts and images will not reflect the keyboard layout you use!

### Kasuto Original (From Kasuto.net)

The table here uses the names of the letters rather than their Hylian form -- the images contain the Latin letter and Hylian letter on each key. If you need to review the names of the letters, refer to the [alphabet page](alphabet.md).

Because Hylian does not have majuscule and miniscule forms for letter (uppercase and lowercase), the Kasuto mapping maps some letters which are normally a variant or digraph to the uppercase mode.

Default Keystrokes:

| \` | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 0 | - | = | BKSP |<br />
| TAB | _ | wante | ete | rote | tote | yote | ute | ite | ote | pate | \[ | \] | \\ |<br />
| CAP | akte | sate | date | fete | gante | hënte | jate | kate | lete | ; | ' | ENTER |<br />
| SHIFT | zante | _ | kate | vete | bete | note | mate | , | . | / | SHIFT |<br />
| CTRL | WIN | ALT | SPACE | ALT | WIN | ALTGR | CTRL |

Shift Keystrokes:

| ~ | ! | @ | # | $ | % | ^ | \& | \* | ( | ) | \_ | + | BKSP |<br />
| TAB | _ | wante | ënte | rote | thate | yote | ünte | ïnte | oite | pate | \{ | \} | \| |<br />
| CAP | äkte | shïnte | date | fete | gante | hënte | jhete | kate | lete | : | \" | ENTER |<br />
| SHIFT | zante | _ | kate | vete | bete | note | mate | \< | \> | ? | SHIFT |<br />
| CTRL | WIN | ALT | SPACE | ALT | WIN | ALTGR | CTRL |

Other symbols require use of alt codes, international input methods, or the Character Map tool in your OS:

| **Hylian Name** | **Char** | **Unicode** | **US International Input** |<br />
| akte asenta | á or Á | U+00E1 or U+00C1 | \'a \'A |<br />
| äkte asenta | à or À | U+00E0 or U+00C0 | \`a \`A |<br />
| ete asenta | é or É | U+00E9 or U+00C9 | \'e \'e |<br />
| ënte asenta | è or È | U+00E8 or U+00C8 | \`e \`e |<br />
| ite asenta | í or Í | U+00ED or U+00CD | \'i \'i |<br />
| ïnte asenta | ì or Ì | U+00EC or U+00CC | \`i \`i |<br />
| ute asenta | ú or Ú | U+00FA or U+00DA | \'u \'u |<br />
| ünte asenta | ù or Ù | U+00F9 or U+00D9 | \`u \`u |<br />
| aite | ã | U+00E3 | \~a |<br />
| aite asenta | Ã | U+00C3 |\~A |<br />
| aute | â | U+00E2 | \^a |<br />
| aute asenta | Â | U+00C2 | \^A |<br />
| iute | î | U+00EE | \^i |<br />
| iute asenta | Î | U+00CE | \^I |<br />
| oite asenta | ô | U+00F4 | \^o |<br />
| toate | õ | U+00F5 | \~o |<br />
| toate asenta | Õ | U+00D3 | \~o |<br />

And even after all of this, [several letters that were added to the language](http://kasuto.net/phpbb3/viewtopic.php?f=10&t=9127) are not mapped in the original version of this font! To fill in the gaps, the following mappings are presented in the Version 3.0 download available on this site:

| **Hylian Name** | **Char** | **Unicode** | **US International Input** |<br />
| khate | K | U+004B | K |<br />
| dhënte | D | U+0044 | D |<br />
| ûkte | û | U+00FB | \^u |<br />
| acete | c | U+0063 | c |<br />
| chäte | C | U+0043 | C |<br />
| añate | ñ | U+00F1 | \~n |<br />

Where these conflict with the chart above, the later description is the most current, but only if you are using fonts provided from the Hylian Language Institute Mirror.

### Kasuto Unicode

Kasuto Unicode is compatible with modern web browsers and applications, and minimizes the font's reliance on tricks to overcome keyboard limitations, meaning that the Kasuto Unicode mapping stores certain characters in appropriate positions in the Unicode font table, without putting them into their own area.

The advantage of this is that even standard transliterated Hylian should put the same letters on the screen whether you type them as an uppercase or lowercase letter. The disadvantage is that to type it entirely from your keyboard, you will need to use the Hylian Simple input method, which will use the standard transliteration and US International techniques to allow typing Hylian.

Default Keystrokes:

| \` | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 0 | - | = | BKSP |<br />
| TAB | _ | wante | ete | rote | tote | yote | ute | ite | ote | pate | \[ | \] | \\ |<br />
| CAP | akte | sate | date | fete | gante | hënte | jate | kate | lete | ; | ' | ENTER |<br />
| SHIFT | zante | xate | acete | vete | bete | note | mate | , | . | / | SHIFT |<br />
| CTRL | WIN | ALT | SPACE | ALT | WIN | ALTGR | CTRL |

If you are using the US input method, this is all you will get, whether you use uppercase or lowercase. However, if you use US International or Hylian Simple the following keystrokes will act as dead keys:

- \' will allow you to mark the next letter (vowels only) as _asënta_ and will put the _asënta_ form of a normal vowel -- the form transliterated with an acute accent.
- \" will allow you to mark the next letter (vowels only) as _kibara_ and will put the alternate form of a normal vowel -- the form transliterated with a dieresis marker.
- \^ will allow you to mark the next letter (vowels only) as _kibara asenta_ and will put the _asenta_ form of a _kibara_ vowel -- the form transliterated with a circumflex marker.
- \~n will allow you to type **ñ**.

In addition to the above, if you are using Hylian Simple, the following features are available:

- The following characters will create a dead character before printing, waiting for the listed characters to follow them.
  - **c**, **d**, **j**, **k**, **s**, and **t** will each create a dead stroke waiting for the letter \/h\/ to decide if their default form or digraph variant should be used. This is the recommended way of generating _chäte_, _dhënte_, _jhete_, _shïnte_, and _thate_. While not recommended, it will still properly produce _xate_.
  - **n** will create a dead stroke waiting for the letter \/g\/, in order to produce _añate_.
  - The vowels which begin diphthongs will also create dead strokes:
    - **a** will look for \/i\/ or \/u\/ to complete _aite_ or _aute_
    - **á** will look for \/i\/, \/u\/, \/í\/ or \/ú\/ to complete _aite asente_ or _aute asenta_
    - **i** will look for \/u\/ to complete _iute_
    - **í** will look for \/u\/ or \/ú\/ to complete _iute asenta_
    - **o** will look for \/a\/ or \/i\/ to complete _toate_ or _oite_
    - **o** will look for \/a\/, \/i\/, \/á\/ or \/i\/ to complete _toate asenta_ or _oite asenta_
    - **u** will look for \/u\/ to complete _ûkte_.
- **\~** will allow you to use all of the "old-style" keystrokes to complete any consonant that transliterates as a digraph:
  - **\~c** will create _chäte_
  - **\~d** will create _dhënte_
  - **~j** will create _jhete_
  - **\~k** will create _xate_ (this is not recommended, as _xate_ is mapped to x, but is allowed)
  - **\~s** will create _shïnte_
  - **\~t** will create _thate_
