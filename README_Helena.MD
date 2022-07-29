The first letter has index zero, the second letter has index one etc.
To specify the position of letters to be coloured, after the 'colour' flag type:

"_#"   for example: --color=blue_1   will colour the second letter.
"_##"  for example: --color=blue_12  will colour the second and the third letters.
"_#:"  for example: --color=blue_1:  will colour letters from the second to the last.
"_###" for example: --color=blue_124 will colour the second, the third, and the fifth letters.
"_#:#" for example: --color=blue_1:4 will colour all letters between the second and the fifth letter.

Only single digit indexes are inplemented.
A missing "_#" suffix will result in the entire word being coloured.

