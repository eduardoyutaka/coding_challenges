### Aula 2

#### Warmup

##### [1480. Running Sum of 1d Array](https://leetcode.com/problems/running-sum-of-1d-array/description/)
<details>
  <summary>Follow up question 1</summary>
  Você conseguiria resolver o problema utilizando `for` loops?
</details>

<details>
  <summary>Follow up question 2</summary>
  Você conseguiria resolver o problema em O(N)?
</details>

#### Problemas

##### [1768. Merge Strings Alternately](https://leetcode.com/problems/merge-strings-alternately/)
<details>
  <summary>Dica 1</summary>
  Você conseguiria resolver o problema com strings do mesmo tamanho?
</details>

##### [1071. Greatest Common Divisor of Strings](https://leetcode.com/problems/greatest-common-divisor-of-strings/)
<details>
  <summary>Dica 1</summary>
  Tente resolver na força bruta
</details>
<details>
  <summary>Dica 2</summary>
  Você consegue concluir algo concatenando `str1` e `str2`?
</details>
<details>
  <summary>Dica 3</summary>
  Caso exista um `x` que divide `str1` e `str2`, qual o tamanho dele?
</details>

##### [1431. Kids With the Greatest Number of Candies](https://leetcode.com/problems/kids-with-the-greatest-number-of-candies/description/)
<details>
  <summary>Dica 1</summary>
  Qual criança deve ser superada ou igualada com a ajuda dos `extra_candies`?
</details>

##### [605. Can Place Flowers](https://leetcode.com/problems/can-place-flowers/description/)
<details>
  <summary>Dica 1</summary>
  Existe uma estratégia gananciosa para resolver o problema?
</details>

##### [345. Reverse Vowels of a String](https://leetcode.com/problems/reverse-vowels-of-a-string/description/)
<details>
  <summary>Dica 1</summary>
  Tente filtrar apenas as vogais de `s`
</details>
<details>
  <summary>Dica 1</summary>
  Reverta as vogais de `s`
</details>
<details>
  <summary>Dica 2</summary>
  Reverta as vogais de `s`
</details>
<details>
  <summary>Dica 3</summary>
  Percorra `s` e atualize as vogais para a nova ordem
</details>

##### [151. Reverse Words in a String](https://leetcode.com/problems/reverse-words-in-a-string/description/)
<details>
  <summary>Dica 1</summary>
  Você consegue transformar `s` em um Array de palavras?
</details>
<details>
  <summary>Dica 2</summary>
  Você consegue reverter o Array de palavras?
</details>
<details>
  <summary>Dica 3</summary>
  Você consegue transofrmar o Array de palavras na ordem inversa em uma String novamente?
</details>

##### [238. Product of Array Except Self](https://leetcode.com/problems/product-of-array-except-self/description/)
<details>
  <summary>Dica 1</summary>
  Think how you can efficiently utilize prefix and suffix products to calculate the product of all elements except self for each index. Can you pre-compute the prefix and suffix products in linear time to avoid redundant calculations?
</details>
<details>
  <summary>Dica 2</summary>
  Can you minimize additional space usage by reusing memory or modifying the input array to store intermediate results?
</details>

##### [334. Increasing Triplet Subsequence](https://leetcode.com/problems/increasing-triplet-subsequence/description/)

##### [443. String Compression](https://leetcode.com/problems/string-compression/)
<details>
  <summary>Dica 1</summary>
  Como você sabe se chegou ao fim de um grupo de caracteres consecutivos?
</details>

#### Referência

- Control Expressions
  - [for](https://docs.ruby-lang.org/en/master/syntax/control_expressions_rdoc.html#label-for+Loop) 

- Integer
  - Public Instance Methods
    - [gcd](https://docs.ruby-lang.org/en/master/Integer.html#method-i-gcd)

- Array
  - Methods for fetching
    - [Array#max](https://docs.ruby-lang.org/en/master/Array.html#method-i-max)
    - [Array#min](https://docs.ruby-lang.org/en/master/Array.html#method-i-min)
  - Methods for converting
    - [Array#join](https://docs.ruby-lang.org/en/master/Array.html#method-i-join)

- String
  - Methods for creating a String
    - [::new](https://docs.ruby-lang.org/en/master/String.html#method-c-new)
  - Methods for modifying a String
    - [<<](https://docs.ruby-lang.org/en/master/String.html#method-i-3C-3C)
  - String Slices
    - [String#\[\]](https://docs.ruby-lang.org/en/master/String.html#method-i-5B-5D)
    - [String#\[\]=](https://docs.ruby-lang.org/en/master/String.html#method-i-5B-5D-3D)
  - Public Instance Methods
    - [*](https://docs.ruby-lang.org/en/master/String.html#method-i-2A)
  - Converting to Non-String
    - [String#split](https://docs.ruby-lang.org/en/master/String.html#method-i-split)
  - Modifying
    - [String#reverse](https://docs.ruby-lang.org/en/master/String.html#method-i-reverse)

- Enumerable
  - Other Methods
    - [Enumerable#reduce](https://docs.ruby-lang.org/en/master/Enumerable.html#method-i-reduce)

