# canonical-greekLit

The repository includes the canonical greekLit collection from perseus
as a submodule so before you proceed with any parsing/indexing please
init/update the submodule:

```
git submodule update --init
```

First pass:

Parsing homer is working but not all lines from all books are parsed
yet. Working on it...:

```
  # gives back all lines of homers <book_num>
  # represented as json data points
  ./greek_lit.rb <book_num>
```

TODO:

- generic indexer/parser for homer
- move on to generalize the parser to all authors of prose
- move on to include different categories of text
