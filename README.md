# SensitiveWord
参考博客https://www.jianshu.com/p/2e84eacc3cc8
实现的DFA算法检测敏感词，对检测方法做了一定修改，原来的方法存在一些问题，当采用最大匹配模式时，假设敏感词中有"中国"，"中国人民"，当输入"中国人"时，输出匹配到的敏感词应该是"中国"，但原方法会输出"中国人"，所以进行了优化
