# Backsteingotik

A pixel art font.

## Table of Contents

- [Supported Characters](#supported-characters)
  - [Unicode](#unicode)
- [Limitations](#limitations)
  - [Enclosed CJK Letters and Months](#enclosed-cjk-letters-and-months)
  - [CJK Compatibility](#cjk-compatibility)
  - [CJK Unified Ideographs](#cjk-unified-ideographs)

## Supported Characters

> [!NOTE]
> The font currently only supports the South Korean standard of CJK Ideographs.
> Support for other standards is planned.

### Unicode

| Block                                                  | No. Glyphs | Percentage |
|--------------------------------------------------------|------------|------------|
| Basic Latin (U+0000 - U+007F)                          | 95/95      | 100.00%    |
| Latin-1 Supplement (U+0080 - U+00FF)                   | 96/96      | 100.00%    |
| Latin Extended-A (U+0100 - U+017F)                     | 128/128    | 100.00%    |
| Latin Extended-B (U+0180 - U+024F)                     | 20/208     | 9.62%      |
| Cyrillic (U+0400 - U+04FF)                             | 249/256    | 97.27%     |
| Latin Extended Additional (U+1E00 - U+1EFF)            | 91/256     | 35.55%     |
| Hangul Jamo (U+1100 - U+11FF)                          | 67/256     | 26.17%     |
| General Punctuation (U+2000 - U+206F)                  | 71/111     | 63.96%     |
| Kangxi Radicals (U+2F00 - U+2FDF)                      | 214/214    | 100.00%    |
| Ideographic Description Characters (U+2FF0 - U+2FFF)   | 16/16      | 100.00%    |
| CJK Symbols and Punctuation (U+3000 - U+303F)          | 54/64      | 84.38%     |
| Hiragana (U+3040 - U+309F)                             | 91/93      | 97.85%     |
| Katakana (U+30A0 - U+30FF)                             | 96/96      | 100.00%    |
| Bopomofo (U+3100 - U+312F)                             | 43/43      | 100.00%    |
| Hangul Compatibility Jamo (U+3140 - U+318F)            | 51/94      | 54.26%     |
| Kanbun (U+3190 - U+319F)                               | 16/16      | 100.00%    |
| Enclosed CJK Letters and Months (U+3200 - U+32FF)      | 251/255    | 98.43%     |
| CJK Compatibility (U+3300 - U+33FF)                    | 255/256    | 99.61%     |
| CJK Unified Ideographs Extension A (U+3400 - U+4DBF)   | 5/6592     | 0.08%      |
| Yijing Hexagrams (U+4DC0 - U+4DFF)                     | 64/64      | 100.00%    |
| CJK Unified Ideographs (U+4E00 - U+9FFF)               | 1441/20992 | 6.86%      |
| Hangul Syllables (U+AC00 - U+D7AF)                     | 743/11172  | 6.65%      |
| Halfwidth and Fullwidth Forms (U+FF00 - U+FFEF)        | 224/225    | 99.56%     |
| CJK Unified Ideographs Extension B (U+20000 - U+2A6DF) | 10/42720   | 0.02%      |
| CJK Unified Ideographs Extension H (U+31350 - U+323AF) | 1/4192     | 0.02%      |

## Limitations

> [!NOTE]
> If you find a character that is illegible, please
> [submit an issue](https://github.com/salademalade/backsteingotik/issues)
> on GitHub.

The following characters are known to be unlikely to be supported due to
limitations with the pixel art:

### Enclosed CJK Letters and Months

| Character | Codepoint | Name                                 | Alternatives |
|-----------|-----------|--------------------------------------|--------------|
| ㈝        | U+321D    | PARENTHESIZED KOREAN CHARACTER OJEON | `(오전)`     |
| ㈞        | U+321E    | PARENTHESIZED KOREAN CHARACTER OHU   | `(오후)`     |
| ㉼        | U+327C    | CIRCLED KOREAN CHARACTER CHAMKO      | `(참고)`     |
| ㉽        | U+327D    | CIRCLED KOREAN CHARACTER JUEUI       | `(주의)`     |

### CJK Compatibility

| Character | Codepoint | Name               | Alternatives |
|-----------|-----------|--------------------|--------------|
| ㍿        | U+337F    | SQUARE CORPORATION |              |
