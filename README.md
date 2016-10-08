#Syntax guide
Here’s an overview of Markdown syntax that you can use anywhere on GitHub.com or in your own text files.

##段落和换行
一个 **Markdown** 段落是由一个或多个连续的文本行组成，它的前后要有一个以上的空行（空行的定义是显示上看起来像是空的，便会被视为空行。比方说，若某一行只包含空格和制表符，则该行也会被视为空行）。普通段落不该用空格或制表符来缩进。

`「由一个或多个连续的文本行组成」`这句话其实暗示了 **Markdown** 允许段落内的强迫换行（插入换行符），这个特性和其他大部分的 *text-to-HTML* 格式不一样（包括 _Movable Type_ 的_「Convert Line Breaks」_选项），其它的格式会把每个换行符都转成` <br />` 标签。

如果你确实想要依赖 **Markdown** 来插入 `<br />` 标签的话，在插入处先按入两个以上的空格然后回车。

的确，需要多费点事（多加空格）来产生 `<br />` ，但是简单地`「每个换行都转换为 <br />」`的方法在 **Markdown** 中并不适合， **Markdown** 中 *email* 式的 `区块引用` 和多段落的 `列表` 在使用换行来排版的时候，不但更好用，还更方便阅读。
 
