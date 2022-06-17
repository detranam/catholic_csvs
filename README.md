# catholic_csvs

## NOTE

All CSV files have an end of line of \r\n, and their delimiter is always a tab. ('\t'). The first line is always the header.  
Yes, I know the title is 'csv' and I'm using tsv. It's easier for some to use.

## General TSV Files

These are all files that might be useful for application development for religious (Catholic, most likely) applications. Feel free to use any of them!

### Saints and Feast Days

You never know when someone would want a nicely formatted CSV to know the saints, their feast days, and their patronages.  
This is formatted as: 'Saint;Date;Patronage'

### Marian Antiphons

(brk) signifies a line break if you wanted to make these songs look 'pretty', otherwise when parsed you can simply remove all instances of (brk) and replace them with a single space without any confusion.  
This is formatted as: 'Time Sung;Name;Latin;English'

### Common Prayers English Latin

(brk) signifies a line break if you wanted to make these songs look 'pretty', otherwise when parsed you can simply remove all instances of (brk) and replace them with a single space without any confusion.  
This is meant to be a comprehensive collection of many Catholic prayers in both Latin and English to allow for memorization / offline prayer.  
This is formatted as: 'Name;English;Latin'

### TODO

- [x] Saints and their feast days
- [x] Marian Antiphons, latin and english, times they're sung
- [ ] Marian Feast days
- [ ] All basic prayers (hail mary, our father, etc) in both english and latin
