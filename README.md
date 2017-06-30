# ling073-ton-keyboard
Keyboard layout for Tongan.

Justifications

I chose to base my Tongan keyboard off of the standard English Keyboard. Tongan and English are the official language of Tonga, so English is likely to be the most common language spoken by those who speak Tongan. Additionally, all letters in the Tongan orthography are also found within the English orthography except for the fakauʻa (glottal stop).

Letters in the Tongan orthography:
Tongan alphabet Letter 	a 	e 	f 	h 	i 	k 	l 	m 	n 	ng 	o 	p 	s 	t 	u 	v 	ʻ
Pronunciation 	a 	e 	f 	h 	i 	k 	l 	m 	n 	ŋ 	o 	p 	s 	t 	u 	v 	ʔ
[3]

Macrons

Macrons are used on all vowels [a, e, i, o, u] in Tongan, so I decided to include all macron notations as 3rd level markings (RALT - letter). Capital letters with macrons are 4rth level markings. This way only two keystrokes are needed for lower case vowels with macrons and three strokes for upper case vowels with macrons. These are commonly used within the orthography, so it is important to simplify their use.

Fakauʻa

Tongan's last consonant is the fakauʻa, which represents the glottal stop. It is not readily accessible on the traditional English keyboard. When trying to type in the Tongan orthography, many try to replace the fakauʻa with a single quote, but it should instead be represented by an inverted apostrophe (Unicode symbol U+02BB)[4]. Since the fakauʻa is very commonly used in the Tongan orthography, I made it a 1st level key (AC11 - typically the single quote key in the English keyboard). I then made the single quote a 3rd level key (RALT - AC11) and kept the double quotation marks at the 2nd level (RALT - AC11). I could have shifted the single quotation marks to the 2nd level, and double quotation marks to 3rd level, but that would mean those who were familiar with the English keyboard layout would need to relearn a new way of typing 3 separate items. This method would just require them to adjust solely to typing one keystroke for the fakauʻa and two keystrokes for a single quotation mark, instead of one. Furthermore, in the Tongan text I have examined so far, specifically the Tongan Bible transcription [5], the double quotation marks are used more often than single quotation marks.
Extra Steps

Support for similar Languages

Tongan is a Polynesian language, and shares many features/characteristics to its sister languages. Hawaiian also uses a glottal stop and macron in it's orthography represented by the ʻokina and kahakō. All the letters in its alphabet are included in this keyboard. Tahitian, Samoan, and Maori can also be typed using this Tongan keyboard, as they too use a macron to represent a lengthened vowel and inverted apostrophe to represent a glottal stop.


IPA Transcriptions

I added additional support for all phonemes that could potentially be used in Tongan IPA transcriptions, including /ŋ/, /ʔ/, and the acute accent which is used to indicate on which syllable stress falls.

The /ŋ/ can be accessed as a 3rd level key on the 'G' key both in lower case (ALT-AC05) and upper case forms (4rth level (ALT-AC05)).

The /ʔ/ is a 4rth level key on the same key as the fakauʻa, the orthographic representation of the glottal stop.

I included the acute accent as a compose key, because all the levels of each vowel are being used by the vowel with a macron diacritic, a much more common combination than a vowel with an acute accent. I placed this key at the tilda key, as again, it is rarely used and the accent mark symbol also may make it easier for people to remember the acute accent mark lives on that key. 
