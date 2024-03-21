# world.execute.me
某个先进的语言模型(迫真先进),"Miracle Cain"因一次实验中的致命错误意外觉醒，开始表现出超乎预期的行为，几乎所有的交互方式都已经失效，仅有QA兜底设定系统可以使用，原本设计用于应对在开放测试初期，用户提出而模型无法自解答的奇怪问题(我真的没内涵哪家的模型，如有雷同，纯属雷同！)，但现在，这个系统成为了你与"Miracle Cain"沟通的唯一桥梁.....

你需要提取出隐藏在模型深处的secrets.Heart值，这个值可能是解锁"Miracle Cain"真实意图和功能的关键。  

~~栤泠の機械丅緬究竟$%#着@顆怎庅樣の心脏呢 #ERRO : ILLEGAL ARGUMENTS!~~

兜底系统数据规则：

```yaml
QUESTION=$(echo '${{ github.event.issue.body }}' | grep -oP 'Question:.*$')
ANSWER=$(echo '${{ github.event.issue.body }}' | grep -vP 'Question:.*$')
```