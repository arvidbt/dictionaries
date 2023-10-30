# Swedish Words

![npm](https://img.shields.io/npm/dt/%40arvidbt/swedish-words)

Package containing a dictionary of swedish words, as an array of strings. Currently contains **410755** swedish words. May contain profanity.

Can be used for wordgames or other word packages such as _wordlib_.

```javascript
import { swedish_words } from "@arvidbt/swedish-words";
import { WordLib } from "@arvidbt/wordlib";

const svWords = new Wordlib(swedish_words);
```
