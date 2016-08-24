# cha

Search English word from youdao and translate it to Chinese using Linux Shell.

### Install

> sudo pip install cha

### Basic Usage 基本用法


> c some


It will show the Chinese meaning of word **some**.
它将会显示单词some的中文解释。

If you want to search English phrase, you can do it in shell: 
如果你需要查询英语词组，可以在Shell中按照下面的方式做：

> c "be aware of"

then it will give the result.
然后，它将会给出结果。

### Advanced Usage 高级用法

- show your top N search words:`c --top 10` or `c -t 20`
- show your last N seach words:`c --last 10` or `c -l 20`
- delete some your have learned word by word id: `c -di 1`, will delete word of id 1
- delete some your have learned word by word itself: `c -dw some`, will delele **some**

