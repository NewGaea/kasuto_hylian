# All Hylian Words

```dataview
TABLE englishGloss as "English", contributors as "Contributed by:"
FROM "lexicon" and #lexicon
FLATTEN englishGloss
SORT (file.name)ASC
```
