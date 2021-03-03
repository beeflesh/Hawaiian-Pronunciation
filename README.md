# Hawaiian-Pronunciation


This challenge was first described at a conference attended by my CSC1301 professor, Dr. Olga Glebova.

Requirements for the challenge are as follows:
-----------------------------------------------------
● The program should validate that the word given by the user only has valid Hawaiian
characters. Spaces and the apostrophe (‘) are valid as well.

● If a word is not valid, warn the user about offending characters and prompt for a
hawaiian word again.

● Spaces are breaks for words and should be kept intact.

● The apostrophe is a hard stop, and should be kept in the word. A word with a’i is
pronounced ah’ee. Without the apostrophe it would be eye.

● Ask the user if they want to do another word. Valid responses are Y, YES, N or NO. If
they want to play more, then they can enter another hawaiian word. If no, then the
program ends.

Development Notes:
-------------------------------------------------------
You won’t be able to just use the .replace() method. You’ll need to evaluate the the
characters entered one at a time according to the rules.
● Using .upper() or .lower() will change all the characters to the given case. Making
comparisons easier.
● Use .capitalize() will capitalize the first character in each word. Makes for a nice output.

Vowel and Consonant Sounds:
--------------------------------------------------------
Consonants:

p, k, h, l, m, n             Pronounced like the english versions.
w - start of word            Either pronounced as a w or a v sound. We shall pronounce it as a
                               w sound.
w - after the letter ‘a’     Either pronounced as a w or a v sound. We shall pronounce it as a
                               w sound.
w - after ‘i’ or ‘e’         Pronounced as a v sound.
w - after ‘u’ or o           Pronounced as a w sound.

Vowels:

a sounds like ah.      eg. Austin - ah-stin
e sounds like eh.      eg. egg - eh-gg
i sounds like ee       eg. bee
o sounds like oh       eg. obey - oh bay
u sounds like oo       eg. mood - m oo d

--------------------------------------------------------


THE CATCH: Vowel Groups:
--------------------------------------------------------
Vowel Groups
ai sounds like eye.             eg. Ice
ae sounds like eye.             Same as ai
ao sounds like ow.              eg. How
au Sounds like ow.              eg. House.
ei Sounds like ay.              eg. Hay
eu Sounds like eh-oo
iu Sounds like ew
oi Sounds like oy
ou Sounds like ow.
ui Sounds like ooey.            Like gooey.
