---
title: نمایش کد در مارک داون (Markdown)  
author: محمد رضا کریمی  
description: در مارک داون برای نمایش متن و یا بهتر است بگوییم نمایش کد، کافیست آن قطعه کد را بین دو علامت بک‌‌ تیک (`) قرار دهید. که به این نوع نمایش کد، Inline Code می‌گویند.
dateModified: 2018/05/16  
datePublished: 2018/05/16  
uid: It/Markdown/CodeWriting  
---

**راهنمای مطالب**

- [کد درون خطی (Inline Code)](#کد-درون-خطی-inline-code)
- [بلاک کد](#بلاک-کد)
- [نمایش کد به صورت رنگی](#نمایش-کد-به-صورت-رنگی)

## کد درون خطی (Inline Code)
برای نمایش متن و یا بهتر است بگوییم نمایش کد، کافیست آن قطعه کد را بین دو علامت بک‌‌ تیک (`) قرار دهید.که به این نوع نمایش کد، Inline Code می‌گویند.

مثال:

```
I think you should use an
`code here` element here instead
```

خروجی:

I think you should use an
`code here` element here instead

هرچیزی که داخل دو علامت بک تیک (`) قرار دهید به همان شکل نشان داده می شوند.

## بلاک کد

اگر شما قصد نمایش یک بلاک کد را دارید کافیست در ابتدا و انتهای آن، سه علامت بک تیک (`) قرار دهید.

مثال :

````
Some basic Git commands are:
```
git status
git add
git commit
```
````

خروجی:

Some basic Git commands are:
```
git status
git add
git commit
```
## نمایش کد به صورت رنگی
شما میتوانید زبان قطعه کد  را بنویسید تا با رنگ‌های بهتری نمایش داده شود.

مثال :

````
```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```
````

خروجی:

```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```

[کد درون خطی (Inline Code)]: #کد-درون-خطی-inline-code
[بلاک کد]: #بلاک-کد
[نمایش کد به صورت رنگی]: #نمایش-کد-به-صورت-رنگی