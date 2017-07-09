## Page1
### タイトル
配列とは

### 内容
- 配列の定義
- 配列をそのまま出力する

### コード
index.rb
```rb
# 変数languagesに、複数の文字列を要素に持つ配列を代入してください
languages = ["日本語", "英語", "スペイン語"]

# 変数languagesを出力してください
puts languages
```

## Page2
### タイトル
配列を使ってみよう

### 内容
- インデックス番号
  - 配列の各要素を取得する方法
  - 変数展開

### コード
index.rb
```rb
languages = ["日本語", "英語", "スペイン語"]

# インデックス番号が1の要素を出力してください
puts languages[1]

# インデックス番号が0の要素を使って出力してください
puts "#{languages[0]}を話せます"
```

## Page3
### タイトル
each文

### 内容
- 繰り返し処理の説明
- each文の文法

### コード
index.rb
```rb
languages = ["日本語", "英語", "スペイン語"]

# each文を用いて、要素ごとに「○○を話せます」と出力してください
languages.each do |language|
  puts "#{language}を話せます"
end
```

## Page4
### タイトル
変数の使える範囲

### 内容
- スコープについて
  - each文を用いて説明する

### コード
index.rb
```rb
languages = ["日本語", "英語", "スペイン語"]
border = "---------------------"

languages.each do |language|
  # 変数borderを出力してください
  puts border
  puts "#{language}を話せます"
end

# 以下のコードを削除してください
puts language
```
