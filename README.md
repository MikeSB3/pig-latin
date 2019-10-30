Behavior -
1. The program does nothing to non-alphabetical characters, since they do not contain consonants or vowels
2. The program adds "ay" to single-letter words beginning with a vowel
3. For words beginning with one or more consonants, move all of the first consecutive consonants to the end, and add "ay".
4. For words beginning with "y", treat "y" as a consonant.
5. If the first consonants include "qu", move the "u" along with the "q". Don't forget about words like "squeal" where "qu" doesn't come first!


input example -
1. Example Input: 3
2. Example Input: i
3. Example Input: pig
4. Example Input: yellow
5. Example Input: queen

output example -
1. Example Output: 3
2. Example Output: iay
3. Example Output: igpay
4. Example Output: ellowyay
5. Example Output: eenquay
