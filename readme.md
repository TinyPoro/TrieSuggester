# Poro\TrieSuggester

Project thực hành trie

## Usage

- Khởi tạo đối tượng 


```
$trie = new \Poro\TrieSuggester\TrieSuggester();
```

- load danh sách các từ vào cây Trie

```
$trie->loadDict($word_array);

```
 
- Lấy ra danh sách các từ gợi ý từ dữ liệu nhập vào. (Lấy ra các từ bắt đầu với từ được nhập vào, không phân biệt hoa thường của input)

```
$trie->suggest($string);
$trie->alternateSuggest($string);

``` 
## Note
