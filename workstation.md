
<h1>Table of Contents<span class="tocSkip"></span></h1>
<div class="toc"><ul class="toc-item"><li><span><a href="#我的本地设置" data-toc-modified-id="我的本地设置-1"><span class="toc-item-num">1&nbsp;&nbsp;</span>我的本地设置</a></span><ul class="toc-item"><li><span><a href="#最常用的terminal-commands" data-toc-modified-id="最常用的terminal-commands-1.1"><span class="toc-item-num">1.1&nbsp;&nbsp;</span>最常用的terminal commands</a></span></li><li><span><a href="#如何安装常用软件" data-toc-modified-id="如何安装常用软件-1.2"><span class="toc-item-num">1.2&nbsp;&nbsp;</span>如何安装常用软件</a></span></li><li><span><a href="#vim如何剪切，复制，粘贴，保存" data-toc-modified-id="vim如何剪切，复制，粘贴，保存-1.3"><span class="toc-item-num">1.3&nbsp;&nbsp;</span>vim如何剪切，复制，粘贴，保存</a></span></li><li><span><a href="#如何做vim常规搜索" data-toc-modified-id="如何做vim常规搜索-1.4"><span class="toc-item-num">1.4&nbsp;&nbsp;</span>如何做vim常规搜索</a></span></li><li><span><a href="#最常用的vim操作" data-toc-modified-id="最常用的vim操作-1.5"><span class="toc-item-num">1.5&nbsp;&nbsp;</span>最常用的vim操作</a></span></li><li><span><a href="#如何安装vim,-使用ctags,-启用python-syntax" data-toc-modified-id="如何安装vim,-使用ctags,-启用python-syntax-1.6"><span class="toc-item-num">1.6&nbsp;&nbsp;</span>如何安装vim, 使用ctags, 启用python syntax</a></span></li><li><span><a href="#构建.vimrc" data-toc-modified-id="构建.vimrc-1.7"><span class="toc-item-num">1.7&nbsp;&nbsp;</span>构建.vimrc</a></span></li><li><span><a href="#Conda" data-toc-modified-id="Conda-1.8"><span class="toc-item-num">1.8&nbsp;&nbsp;</span>Conda</a></span></li><li><span><a href="#Jupyter-notebook" data-toc-modified-id="Jupyter-notebook-1.9"><span class="toc-item-num">1.9&nbsp;&nbsp;</span>Jupyter notebook</a></span></li><li><span><a href="#git" data-toc-modified-id="git-1.10"><span class="toc-item-num">1.10&nbsp;&nbsp;</span>git</a></span><ul class="toc-item"><li><ul class="toc-item"><li><span><a href="#如何免去用户名和密码" data-toc-modified-id="如何免去用户名和密码-1.10.0.1"><span class="toc-item-num">1.10.0.1&nbsp;&nbsp;</span>如何免去用户名和密码</a></span></li><li><span><a href="#如何快速git-push" data-toc-modified-id="如何快速git-push-1.10.0.2"><span class="toc-item-num">1.10.0.2&nbsp;&nbsp;</span>如何快速git push</a></span></li><li><span><a href="#-如何在原fastai-repo和你的fork-repo之间更新？" data-toc-modified-id="-如何在原fastai-repo和你的fork-repo之间更新？-1.10.0.3"><span class="toc-item-num">1.10.0.3&nbsp;&nbsp;</span><a name="fork"></a> 如何在原fastai repo和你的fork repo之间更新？</a></span></li><li><span><a href="#如何创建branch并将master更新给branch" data-toc-modified-id="如何创建branch并将master更新给branch-1.10.0.4"><span class="toc-item-num">1.10.0.4&nbsp;&nbsp;</span>如何创建branch并将master更新给branch</a></span></li><li><span><a href="#如何做版本内容修改和测试" data-toc-modified-id="如何做版本内容修改和测试-1.10.0.5"><span class="toc-item-num">1.10.0.5&nbsp;&nbsp;</span>如何做版本内容修改和测试</a></span></li><li><span><a href="#如何做PR" data-toc-modified-id="如何做PR-1.10.0.6"><span class="toc-item-num">1.10.0.6&nbsp;&nbsp;</span>如何做PR</a></span></li></ul></li></ul></li><li><span><a href="#ipdb" data-toc-modified-id="ipdb-1.11"><span class="toc-item-num">1.11&nbsp;&nbsp;</span>ipdb</a></span></li><li><span><a href="#构建bash_profile" data-toc-modified-id="构建bash_profile-1.12"><span class="toc-item-num">1.12&nbsp;&nbsp;</span>构建bash_profile</a></span></li><li><span><a href="#构建pdbrc" data-toc-modified-id="构建pdbrc-1.13"><span class="toc-item-num">1.13&nbsp;&nbsp;</span>构建pdbrc</a></span></li><li><span><a href="#Jupyter-notebook-extensions" data-toc-modified-id="Jupyter-notebook-extensions-1.14"><span class="toc-item-num">1.14&nbsp;&nbsp;</span>Jupyter notebook extensions</a></span></li><li><span><a href="#jn-color-theme" data-toc-modified-id="jn-color-theme-1.15"><span class="toc-item-num">1.15&nbsp;&nbsp;</span>jn color theme</a></span></li><li><span><a href="#youtube-dl" data-toc-modified-id="youtube-dl-1.16"><span class="toc-item-num">1.16&nbsp;&nbsp;</span>youtube-dl</a></span><ul class="toc-item"><li><span><a href="#其他参考链接" data-toc-modified-id="其他参考链接-1.16.1"><span class="toc-item-num">1.16.1&nbsp;&nbsp;</span>其他参考链接</a></span></li><li><span><a href="#如何为视频做语音解说" data-toc-modified-id="如何为视频做语音解说-1.16.2"><span class="toc-item-num">1.16.2&nbsp;&nbsp;</span>如何为视频做语音解说</a></span></li></ul></li></ul></li></ul></div>

# 我的本地设置

[details="最常用的terminal commands"]
## 最常用的terminal commands
```bash
# find out the size of directory folders
du -sh *  
# move cursor to the front or end of a line
ctrl + a = to the end of a line
ctrl + e = to the start of a line
ctrl + u = clear the line before the cursor
ctrl + k = clear the line after the cursor
cmd + k = clear the terminal
ctrl + f = move forward a character
ctrl + b = backward
esc + f = move forward by a word 
esc + b = move backward by a word
```
[/details]
[details="如何fastai本地安装"]
## 如何安装常用软件
	- 下载安装conda 
		- [下载最新Conda, Mac选择pkg比较方便](https://conda.io/en/latest/miniconda.html) 
		- 双击安装
		- 更新 `condo update conda` outside condo env
	- 创建独立工作环境
		- `conda create -n fastai python=3`  或者明确一个版本3.5
		- `conda activate fastai` 开启实验环境
		- `conda deactivate` 关闭实验环境
		- `conda remove --name fastai --all` 删除环境
	- 下载安装pdbpp 适配python 3.6而非3.7，所以先装更好
		- `conda install pdbpp` is a must
		- not `pip3 install pdbpp`
	- 下载安装Jupyter notebook
		- 更新 pip:  `python3 -m pip install --upgrade pip`
		- 下载更新Jupyter: `python3 -m pip install jupyter`
	- 下载安装 Pytorch和fastai libraries
		- 一步安装：`conda install -c pytorch -c fastai fastai pytorch`
		- 更新  ` conda update conda -y `  outside env
		- 更新 ` conda update -c fastai fastai ` inside env
		- 检验 `conda list` `pip show`

[/details]
[details="vim如何剪切，复制，粘贴，保存"]
## vim如何剪切，复制，粘贴，保存
```vim
: how to cut, under normal mode
: 1. put cursor to where you want to cut
: 2. press v and move cursor to select characters 
: 2. press V and move cursor to select lines
: 3. press d to cut, press y to copy
: 4. move to where to paste, 
: 5; press P to paste before cursor
: 5: press p to paset after cursor
: 6. insert mode, press :w and enter
```
[/details]
[details="如何做vim常规搜索"]
## 如何做vim常规搜索
[Searching | Vim Tips Wiki | FANDOM powered by Wikia](http://vim.wikia.com/wiki/Searching)
```vim
/ls   ;; 我们在搜索ls, 前面不要有space空格
?*.ls
/path.ls
;; inside .vimrc
set ignorecase
```

[/details]
[details="最常用的vim操作"]
## 最常用的vim操作
```vim
# 如何退出
:q = to quit without save
:q! = to quit without save
:wq = save and quit 

# 如何对文件夹做tag
" select a directory you want to work in, and open vim
:MakeTags " to create tags for the entire directory, or 
" this is an alias in .vimrc by the following
command! MakeTags !ctags -R .
command MT MakeTags 

" to find the function or class in the directory and open it
:tag untar_data 

# 如何探索代码
" put cursor on a function you want to dive and press 
ctrl + ] = dive in
ctrl + t = pull back
ctrl + w, ctrl + ] = dive in from another horizontal split
ctrl + w, up or dn = switch between splits
ctrl + \ = dive in from a new tab 
ctrl + a, left or right = switch between tabs
" made possible in .vimrc by 
map <C-a><up> :tabr<cr>
map <C-a><down> :tabl<cr>
map <C-a><left> :tabp<cr>
map <C-a><right> :tabn<cr>


" ctrl + \ made automatic in .vimrc by the following
map <C-\> :tab split<CR>:exec("tag ".expand("<cword>"))<CR>


" when classes can't be find then trace its library file 
:find pathlib
" inside the library file you can find 
:tag Path 

" fold up all functions within a file
:set foldmethod=indent
" already made automatic in .vimrc by 
set foldmethod=indent

" move cursor to the + or - sign to open and close folding with 
za 

" to display the full file address
:echo expand('%:p')
" already made automatic in .vimrc by 
command FileAddress echo expand('%:p')
```

[/details]
[details="如何安装vim, 使用ctags, 启用python syntax"]
## 如何安装vim, 使用ctags, 启用python syntax

```bash
### How to install vim
brew install vim
brew upgrade vim
vim # to run vim

### How to configure vim
nano ~/.vimrc

### How to install and use ctags
brew install ctags
nano .vimrc 
# add 
set tags=tags
# at project directory
ctags -R
# go to definition 
CTRL ]
# go back 
CTRL t

### How to enable python syntax
syntax on
set background=dark
filetype indent plugin on

```

[/details]
[details="构建.vimrc"]
## 构建.vimrc

```vim
set tags=tags
set foldcolumn=3
set foldmethod=indent
set ignorecase

command FileAddress echo expand('%:p')

syntax on
set background=dark
filetype indent plugin on

""""" current millenium
set nocompatible
syntax enable
filetype plugin on

""""" file finder or fuzzy search
set path+=**

""""" display all matching files when tab
set wildmenu

""""" Tag Jumping
command! MakeTags !ctags -R .
command MT MakeTags

""""" tag jump with new tab horizontally or vertically
map <C-\> :tab split<CR>:exec("tag ".expand("<cword>"))<CR>

"""" switch tabs in vim 
map <C-a><up> :tabr<cr>
map <C-a><down> :tabl<cr>
map <C-a><left> :tabp<cr>
map <C-a><right> :tabn<cr>

"""""""""""""""" make presentation with vim files
au VimEnter no_plugins.vim setl window=66
au VimEnter no_plugins.vim normal 8Gzz
au VimEnter no_plugins.vim command! GO normal M17jzzH
au VimEnter no_plugins.vim command! BACK normal M17kzzH
au VimEnter no_plugins.vim command! RUN execute getline(".")
" au VimEnter no_plugins.vim unmap H
" au VimEnter no_plugins.vim unmap L
" why dont these work :(
au VimEnter no_plugins.vim nnoremap ^f :GO<CR>
au VimEnter no_plugins.vim nnoremap ^b :BACK<CR>

```

[/details]
[details="Conda"]

## Conda
```bash
# download miniconda https://docs.conda.io/en/latest/miniconda.html
conda --version # check version:
conda update conda # update conda: , install outside env
conda create -n mesa-abm python=3.6 anaconda # build environment
source activate mesa-abm
source deactivate
conda info --envs # check envs
conda env list # all envs to view
conda create --name new_env --clone existed_env # clone an env
conda remove --name old_env --all # delete an env
conda env export > environment.yml # 输出env
conda env create -f environment.yml # build env from yml
```

[/details]
[details="Jupyter notebook"]

## Jupyter notebook
```
# If you have Python 3 installed (which is recommended):

python3 -m pip install --upgrade pip
python3 -m pip install jupyter

jupyter notebook # to start 
```

[/details]
[details="git"]
## git

#### 如何免去用户名和密码
```bash
# Permanently authenticating with Git repositories
$ git config credential.helper store
$ git push https://github.com/repo.git

Username for 'https://github.com': <USERNAME>
Password for 'https://USERNAME@github.com': <PASSWORD>

```

#### 如何快速git push
```bash

# create a new repo on github
# go to your Mac directory 
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/EmbraceLife/NetLogo-Modeling.git
git push -u origin master
git reset # to undo git add .

# go to .bash_profit to automate it
function lazygit() {
    git add .
    git commit -a -m "$1"
    git push
}
```

#### <a name='fork'></a> 如何在原fastai repo和你的fork repo之间更新？

```bash
# step1: fork from official
# step2: git clone from your fork
git clone https://github.com/EmbraceLife/my-fork
cd my_fork
tools/run-after-git-clone # fastai tools
git remote add upstream official-url-git # link to official repo
git remote -v # check all branches local and remote

git pull upstream master # pull from official repo, or 
######## suggested by fastai is better I guess
git fetch upstream
git checkout master
git merge --no-edit upstream/master
git push
######## suggested by fastai

git push # update my-fork 
git pull # pull from my-fork
```

####  如何创建branch并将master更新给branch
```

git branch # check all branches
git branch new_branch_name # create a branch from where we are
git branch -m a_new_name # rename
git branch -d branch_to_go # delete
git checkout new_branch # switch to a new branch
git merge master # inside new-branch, bring updated master into new-branch
git push --set-upstream origin new-branch-name # 
git push origin --delete new_branch_name # to delete a branch remote in github
svn checkout url-folder-replace-tree/master-with-trunk # only download part of a repo

```

#### 如何做版本内容修改和测试
```bash
conda uninstall -y fastai
cd fastai-fork
pip install -e ".[dev]"
tools/run-after-git-clone
# 做版本内容修改，接下来做测试

## 如果是源代码测试
make test
pytest

## 如果是docsrc 测试 (无需！！！）
cd docs_src
./run_tests.sh
```

#### 如何做PR
[四步法](https://docs.fast.ai/gen_doc_main.html#process-for-contributing-to-the-docs)
第一步：完成fork本地下载和官方对接[指南](#fork)      
第二步：创建一个branch来做你的修改[指南](#branch)      
第三步：进行修改，测试[指南](#test)      
第四步：push修改版本到fork的branch中更新上传[指南](#push)      
第五步：前往你的fork on github,选择branch，点击new pull request      

[/details]
[details="ipdb "]
## ipdb 
```python
python -m pdb file-name.py
# 原来进入代码，输入insert import pdb; pdb.set_trace() 来debug已经不需要了
sticky # 看到全局代码
ll # 从debug跳回到全局代码
# l 20
# l 1, 20: see line from 1 to 20
s # step into a function
n # 运行下一行
w # call stack, where I started and where I am in source code, d go down a stack, u to go up a stack
b 88 # 运行到88行，暂停
# b file.py:41 or b func_name
# b 11, this_year==2017: conditional breakpoint, at line 11 to breakpoint, if this_year == 2017
cl 1 # 删除第一个breakpoint
r # 运行所在 function
c # 运行直到结束
q # 终止
? # 查看文档
hit return # 重复上一次操作
pp variable_name # 友好打印 该变量
# 完成当前loop: until
```

[/details]
[details="构建bash_profile"]

## 构建bash_profile
```bash
cd # go to home directory
nano .bash_profile # go inside .bash_profile:

alias ex='cd /Users/Natsume/Documents/experiments; conda activate fastai'
alias ft='cd /Users/Natsume/Documents/fastai_treasures/plantseedling/; conda activate fastai'
alias v3='cd /Users/Natsume/Documents/course-v3/nbs/dl1; conda activate fastai'
alias fastai='cd /Users/Natsume/Documents/fastai; conda activate fastai'
alias sfastai='cd /Users/Natsume/miniconda3/envs/fastai/lib/python3.7/site-packages/fastai'
alias pdbpp='python -m pdb'
alias de='conda deactivate'
alias xcode="open -a Xcode"
alias jn='jupyter notebook'


function lazygit() {
    git add .
    git commit -a -m "$1"
    git push
}

export PS1="\w "







export LC_ALL=zh_CN.UTF-8
export LANG=zh_CN.UTF-8

export LC_ALL=en_US.UTF-8
export LANG=en_US.UTF-8

# added by Anaconda3 5.2.0 installer
export PATH="/anaconda3/bin:$PATH"
# added by Miniconda3 4.5.12 installer
# >>> conda init >>>
# !! Contents within this block are managed by 'conda init' !!
__conda_setup="$(CONDA_REPORT_ERRORS=false '/Users/Natsume/miniconda3/bin/conda' shell.bash hook 2> /dev/null)"
if [ $? -eq 0 ]; then
    \eval "$__conda_setup"
else
    if [ -f "/Users/Natsume/miniconda3/etc/profile.d/conda.sh" ]; then
        . "/Users/Natsume/miniconda3/etc/profile.d/conda.sh"
        CONDA_CHANGEPS1=false conda activate base
    else
        \export PATH="/Users/Natsume/miniconda3/bin:$PATH"
    fi
fi
unset __conda_setup
# <<< conda init <<<
# added by Miniconda3 4.5.12 installer
# >>> conda init >>>
# !! Contents within this block are managed by 'conda init' !!
__conda_setup="$(CONDA_REPORT_ERRORS=false '/Users/Natsume/miniconda3/bin/conda' shell.bash hook 2> /dev/null)"
if [ $? -eq 0 ]; then
    \eval "$__conda_setup"
else
    if [ -f "/Users/Natsume/miniconda3/etc/profile.d/conda.sh" ]; then
        . "/Users/Natsume/miniconda3/etc/profile.d/conda.sh"
        CONDA_CHANGEPS1=false conda activate base
    else
        \export PATH="/Users/Natsume/miniconda3/bin:$PATH"
    fi
fi
unset __conda_setup
# <<< conda init <<<


```

[/details]
[details="构建pdbrc"]

## 构建pdbrc
[如何构建和安装pdbrc video](https://www.bilibili.com/video/av16754002/)
[如何使用pdbpp来实验代码](https://www.bilibili.com/video/av16753161/)

```python
## located at ~ directory, named .pdbrc, no need for source, just save it

alias dr pp dir(%1) # 查看everything underneath the object
alias dt pp %1.__dict__ # 查看object's dictionaries
alias pdt for k, v in %1.items(): print(k, ": ", v) # 查看一个纯 python dictionary
alias loc locals().keys() # local variables
alias doc from inspect import getdoc; from pprint import pprint; pprint(getdoc(%1)) # documents
alias sources from inspect import getsourcelines; from pprint import pprint; pprint(getsourcelines(%1)) # source code
alias module from inspect import getmodule; from pprint import pprint; pprint(getmodule(%1)) # module name
alias fullargs from inspect import getfullargspec; from pprint import pprint; pprint(getfullargspec(%1)) # all arguments names
alias opt_param optimizer.param_groups[0]['params'][%1] # all parameters
alias opt_grad optimizer.param_groups[0]['params'][%1].grad # all gradients of parameters
```

[/details]
[details="Jupyter notebook extensions"]
## Jupyter notebook extensions
3 steps to install
```
conda install jupyter_contrib_nbextensions
jupyter contrib nbextension install --user
jupyter nbextension enable toc2/main  # in terminal or notebook cell, both are fine
# edit/notebook_config (at bottom of the droplist)
```
[/details]
[details="jn color theme"]
## jn color theme 
```
conda install jupyterthemes
jt -t onedork 
#| grade3 | oceans16 | chesterish | monokai | solarizedl | solarizedd
```

[/details]
[details="youtube-dl"]
## youtube-dl
[youtube-dl](https://github.com/rg3/youtube-dl/blob/master/README.md#readme)

```
--write-sub                      Write subtitle file
--write-auto-sub                 Write automatic subtitle file (YouTube only)
--all-subs                       Download all the available subtitles of the video
--list-subs                      List all available subtitles for the video
--sub-format FORMAT              Subtitle format, accepts formats preference, for example: "srt" or "ass/srt/best"
--sub-lang LANGS                 Languages of the subtitles to download (optional) separated by commas, use IETF language tags like 'en

youtube-dl --write-auto-sub  --sub-lang en  --sub-format srt https://youtu.be/1ZhtwInuOD0

youtube-dl -f 'best[ext=mp4]'  --write-auto-sub  --sub-lang en  --sub-format srt https://www.youtube.com/playlist?list=PLfYUBJiXbdtSIJb-Qd3pw0cqCbkGeS0xn


```
[transcript transform](https://subtitletools.com/convert-to-srt-online)

[/details]
[details="其他参考链接"]
### 其他参考链接

[How to Customize your Terminal Prompt  |   OSXDaily](http://osxdaily.com/2006/12/11/how-to-customize-your-terminal-prompt/)     
[inspect — Inspect live objects — Python 3.7.2 documentation](https://docs.python.org/3/library/inspect.html)    
[20 Terminal shortcuts developers need to know - TechRepublic](https://www.techrepublic.com/article/20-terminal-shortcuts-developers-need-to-know/)

[如何修改谷歌浏览器语言设置for colab](chrome://settings/?search=language)

[/details]
[details="如何为视频做语音解说"]
### 如何为视频做语音解说
	- 使用ytcropper做视频截取，循环播放
	- mac音量调到最低
	- 用quicktime做屏幕录制，提供语音解读，音量调节适中

[/details]


```python

```
