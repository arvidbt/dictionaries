# Spanish Words

![npm](https://img.shields.io/npm/dt/%40arvidbt/spanish-words)

Package containing a dictionary of spanish words, as an array of strings. Currently contains **636598** spanish words. May contain profanity.

Can be used for wordgames or other word packages such as _wordlib_.

```javascript
import { spanish_words } from "@arvidbt/spanish-words";
import { WordLib } from "@arvidbt/wordlib";

const esWords = new Wordlib(spanish_words);
```
