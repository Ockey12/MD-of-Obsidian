---
tags:
- ここにタグを書く
aliases:
- ここにファイルの別名(エイリアス)を書く
---

# 見出し1
## 見出し2
### 見出し3
#### 見出し4
##### 見出し5
###### 見出し6

下に=で見出し1
=
下に--で見出し2
--

\**で挟んで**太字**．

\__で挟んでも__太字__(うまく解析できない場合があるのでアスタリスクの方が良いらしい)．

\*で挟んで*斜体*．

\_で挟んでも_斜体_(これもアスタリスクの方が良いらしい)．

\==で挟んで==ハイライト==．

HTMLの\<u>タグで挟んで<u> アンラーライン </u> ．

\~~で挟んで~~取り消し線~~．

1. 行の先頭に"数字. "で番号付き箇条書き
	1. 番号付き箇条書き1-1
	2. 番号付き箇条書き1-2
2. 番号付き箇条書き2

- 行の先頭に"- "で箇条書き
	- 箇条書き1-1
	- 箇条書き1-2
- 箇条書き2

> 行の先頭に>で引用
> 上下に空行が必要
>> \>>でネストした引用
>>>さらにネストした引用

```
```で上下を挟んでコードブロック

struct ContentView: View {
   var body: some View {
       VStack {
           Image(systemName: "globe")
               .imageScale(.large)
               .foregroundStyle(.tint)
           Text("Hello, world!")
       }
       .padding()
   }
}
```

> 引用にコードブロックを入れられる
> ```
>struct ContentView: View {
>   var body: some View {
>       VStack {
>           Image(systemName: "globe")
>               .imageScale(.large)
>               .foregroundStyle(.tint)
>           Text("Hello, world!")
>       }
>       .padding()
>   }
>}
>```
>引用終わり