# Interactive CLI Sorter

Challenge: Input: words and numbers separated by spaces, output: data sorted or filtered according to the selected command (alphabetical, numeric order, word length, or unique values).
Commands:
- `a` - Sort words alphabetically
- `b` - Sort numbers ascending
- `c` - Sort numbers descending
- `d` - Sort words by length
- `e` - Show unique words
- `f` - Show unique values from the entire set
- `x` - Exit

To see the result, just run the file: node index.ts or bun index.ts

Built this to work with interactive terminal streams in TypeScript. The main goal was practicing strict command mapping with custom type guards, mapped types, and native Node.js readline promises for continuous CLI loops.
