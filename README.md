MyVimFile
=========
<h1><a name="gitandvundle" class="anchor" href="#gitandvundle"><span class="mini-icon mini-icon-link"></span></a>git及vundle安装</h1>

1, 安装git  www.github.com

将git目录加入到系统环境变量path中

;\GitHub\PortableGit\bin  
;\GitHub\PortableGit\libexec\git-core

若出现缺少xxxx.dll
则将将Git\bin\下的xxxxx.dll复制到Git\libexec\git-core\下即可

输入: git --version

如果安装成功则显示git版本信息

2, 将otherfiles中的curl.exe放入git-core中

3, Vundle安装  
Linux $ git clone https://github.com/gmarik/vundle.git ~/.vim/bundle/vundle  
PC    $ git clone https://github.com/gmarik/vundle.git $VIM/vimfiles/bundle/vundle  

========
<h1><a name="vundleop" class="anchor" href="#vundleop"><span class="mini-icon mini-icon-link"></span></a>Vundle支持三种格式</h1>

"格式1：Github上其他用户的仓库（非vim-scripts账户里的仓库，所以要加Github用户名）  
Bundle 'tpope/vim-fugitive' 

"格式2：vim-scripts里面的仓库，直接打仓库名即可。   
Bundle 'FuzzyFinder' 

"格式3：非Github的Git仓库   
Bundle 'git://vim-latex.git.sourceforge.net/gitroot/vim-latex/vim-latex'

========
<h1><a name="vundle" class="anchor" href="#vundle"><span class="mini-icon mini-icon-link"></span></a>Vundle常用指令</h1>

Vundle常用指令  
:BundleList     列出已经安装的插件  
:BundleInstall  安装所有配置文件中的插件  
:BundleInstall! 更新所有插件  
:BundleSearch   搜索插件  
:BundleClean!   根据配置文件删除插件  

=========
<h1><a name="colorscheme" class="anchor" href="#colorscheme"><span class="mini-icon mini-icon-link"></span></a>三个colorscheme</h1>

molokai     https://github.com/vim-scripts/molokai  
jellybeans  https://github.com/nanotech/jellybeans.vim  
smyck       https://github.com/hukl/Smyck-Color-Scheme

=========
<h1><a name="keyword" class="anchor" href="#keyword"><span class="mini-icon mini-icon-link"></span></a>快捷键</h1>
C-W
C-Tab
C-] 
C-T
C-O
C-P
