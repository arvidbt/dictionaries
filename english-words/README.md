# English Words

![npm](https://img.shields.io/npm/dt/%40arvidbt/english-words)

Package containing a dictionary of English words, as an array of strings. Currently contains **370101** english words. May contain profanity.

Can be used for wordgames or other word packages such as _wordlib_.

```javascript
import { english_words } from "@arvidbt/english-words";
import { WordLib } from "@arvidbt/wordlib";

const enWords = new Wordlib(english_words);
```
