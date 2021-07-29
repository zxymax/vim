vimtutor
url: https://www.vim.org
url: https://vim-advenntures.com
command:
:qa!
:w
:e
:ctrl-c or Esc
/
?

h,j,k,l
[
]
{
}
n
gg
shift-g


"窗口分割
<c-w>s 水平分割
<c-w>v 垂直分割

"重排窗口
:h window-resize 改变窗口的大小
<C-w>= 使所有窗口等宽、等高
<C-w>_ 最大化活动窗口的高度
<C-w>| 最大化活动窗口的宽度
[N]<C-w>_ 把活动窗口的高度设为[N]行
[N]<C-w>| 把活动窗口的宽度设为[N]列

"Tab标签操作
:tabe[dit] {filename} 在新标签页中打开{filename}
<C-w>T 把当前窗口移到一个新标签页
:tabc[lose] 关闭当前标签页及其中的所有窗口
:tabo[nly] 只保留活动标签页，关闭所有其它标签页
"Tab标签页切换操作
:tabn[ext] {N}  {N}gt 切换到编号为{N}的标签页
:tabn[ext] gt 切换到下一个标签页
:tabn[revious] gT 切换到上一个标签页

"文本对象操作方式
[number]<command>[text object]
number表示次数，command是命令，d(delete),c(change),y(yank)
text object 是要操作的文本对象，比如单词w,句子s,段落p
iw 表示inner word
aw 表示a word 不会选中当前单词，会包含当前单词之后的空格

ci{ 删除括号里的内容

\U \u 大小写切换


