## Probably, this is most optimized Trie structure in the World ! Thats all what you need know about this project :)

**HArrayInt** - Key\Value In Memory structure for 32bit keys

**HArrayVarRAM** - Key\Value In Memory structure for keys with variety size

------------------

## Why we love Trie ? Because it has much more functionality and stability than Hashtables and much more faster than Binary Trees. Let's compare properties:

![alt tag](https://s16.postimg.org/6zis60mol/functionality.png)

------------------

# [Start overview from Benchmarks](https://github.com/Bazist/HArray/blob/master/Benchmarks.md)

------------------

## Trie ? I heard about Trees and Hastables but don't know anything about Trie
# [Explain me as for Beginners](https://github.com/Bazist/HArray/blob/master/Trie_for_beginners.md)

------------------
### Overview

- **High optimized** Trie structure implemented in more than **8K lines**
- Tested on **1 Billion keys** succesfully
- **Without any Stop World** events such as Rebuild/Rehashing on Insert key.
- **Without any Hash Functions**, the container has adpative algorithm for different nature of keys
- **Scan by Prefix/Scan by Range** of keys features as bonus
- **All Keys are sorted**. Ability to set your **Custom Order** of Keys 
- **Predictible** behaviour even in worst case: smoothly consuming memory, almost constantly latency on insert/lookup
- **Fair Delete** operation with smoothly dismantling each Key. 
  (Dead fibres are used for insert new keys, so structure perfect works in massive insert/delete scenarios)

### Examples

```c++
Comming soon ...
```

### License

The code is licensed under the MIT license, see the [LICENSE file](LICENSE) for details.
