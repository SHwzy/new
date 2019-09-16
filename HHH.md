```flow
st=>start: 学习计划
s1=>operation: 观看《廖雪峰 git教程》:>https://www.liaoxuefeng.com/wiki/896043488029600/900937935629664
c1=>condition: 学会了吗？
no1=>operation: 你怎么这么蠢
yes1=>operation: 干的不错！下一步
s2=>operation: 观看《菜鸟教程 Markdown教程》:>https://www.runoob.com/markdown/md-tutorial.html
c2=>condition: 学会了吗？
e=>end: 结束学习
yes2=>operation: Nice job!但是要保持冷静
no2=>operation: git不会也就算了Markdown你也不会？

st->s1->c1
c1(yes)->yes1->s2->c2
c1(no)->no1(right)->s1
c2(yes)->yes2
c2(no)->no2(right)->s2
```

