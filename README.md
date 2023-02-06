# efficient-trie
A Java library for efficient implementation of prefix trie and suffix trie


## Usage
Example for prefix trie and suffix trie construction:

```java
String[] words = {"abcde", "abc", "ab", "abbd", "ee"};
Integer[] values = {1,2,3,4,5};
int[] scores = {11,14,1,2,3};
PrefixTrie<Integer> prefixTrie = new PrefixTrie<Integer>(words, values, scores);
PrefixTrie<Integer> prefixTrie2 = new PrefixTrie<Integer>(words, values);
String[] words2 = {"abcde", "cde", "de", "bdde", "aa"};

SuffixTrie<Integer> suffixTrie = new SuffixTrie<Integer>(words2, values, scores);
SuffixTrie<Integer> suffixTrie2 = new SuffixTrie<Integer>(words2, values);
```

