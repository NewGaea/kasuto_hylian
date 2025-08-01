# All Hylian Words

```dataview
TABLE englishGloss as "English", contributors as "Contributed by:"
FROM "lexicon" and #lexicon
FLATTEN englishGloss
SORT (englishGloss)ASC
SORT (file.name)ASC
```
