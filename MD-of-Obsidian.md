---
created: {{date:YYYY-MM-DD}}T{{time:HH:mm}} (UTC +09:00)
tags:
aliases:
---

# Headline1
## Headline2
### Headline3
#### Headline4
##### Headline5
###### Headline6

Headline1
=
Headline2
--

This is **bold text**.
This is __bold text__.

This is *italic text*.
This is _italic text_.

This is ==highlighted text==.

This is <u>underlined text<\u>.

This is ~~strikethrough text~~.

1. Ordered List1
	1. Indented Ordered List1-1
	2. Indented Ordered List1-2
2. Ordered List2

- Unordered List1
	- Indented Unordered List1-1
	- Indented Unordered List1-2
- Unordered List2

```
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