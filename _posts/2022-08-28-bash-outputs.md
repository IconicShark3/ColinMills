---
toc: true
layout: post
categories:
title: Bash Check Outputs
---
Using conditional statement to create a project directory and project
Directory /home/colinmills/vscode exists.
Directory /home/colinmills/vscode/APCSP exists.



Navigate to project, then navigate to area wwhere files were cloned
/home/colinmills/vscode/APCSP

list top level or root of files with project pulled from github
[0m[01;32mGemfile[0m    [01;34m_action_files[0m    [01;34m_layouts[0m    [01;34m_posts[0m  [01;32mdocker-compose.yml[0m
LICENSE    _config.yml      [01;34m_notebooks[0m  [01;34m_sass[0m   [01;34mimages[0m
[01;32mMakefile[0m   [01;34m_fastpages_docs[0m  [01;34m_pages[0m      [01;34m_word[0m   index.html
[01;32mREADME.md[0m  [01;34m_includes[0m        [01;34m_plugins[0m    [01;34massets[0m  [01;34mpython[0m

list again with hidden files pulled from github
[0m[01;34m.[0m                   .gitignore  [01;34m_action_files[0m    [01;34m_pages[0m    [01;32mdocker-compose.yml[0m
[01;34m..[0m                  [01;34m.vscode[0m     _config.yml      [01;34m_plugins[0m  [01;34mimages[0m
.devcontainer.json  [01;32mGemfile[0m     [01;34m_fastpages_docs[0m  [01;34m_posts[0m    index.html
[01;34m.git[0m                LICENSE     [01;34m_includes[0m        [01;34m_sass[0m     [01;34mpython[0m
.gitattributes      [01;32mMakefile[0m    [01;34m_layouts[0m         [01;34m_word[0m
[01;34m.github[0m             [01;32mREADME.md[0m   [01;34m_notebooks[0m       [01;34massets[0m

list all files in long format
total 120
drwxr-xr-x 18 colinmills colinmills  4096 Aug 18 13:01 [0m[01;34m.[0m
drwxr-xr-x  4 colinmills colinmills  4096 Aug 22 18:08 [01;34m..[0m
-rw-r--r--  1 colinmills colinmills   420 Aug 18 13:01 .devcontainer.json
drwxr-xr-x  8 colinmills colinmills  4096 Aug 28 15:27 [01;34m.git[0m
-rw-r--r--  1 colinmills colinmills    84 Aug 18 13:01 .gitattributes
drwxr-xr-x  4 colinmills colinmills  4096 Aug 18 13:01 [01;34m.github[0m
-rw-r--r--  1 colinmills colinmills   917 Aug 18 13:01 .gitignore
drwxr-xr-x  2 colinmills colinmills  4096 Aug 22 18:47 [01;34m.vscode[0m
-rwxr-xr-x  1 colinmills colinmills  1304 Aug 18 13:01 [01;32mGemfile[0m
-rw-r--r--  1 colinmills colinmills 11351 Aug 18 13:01 LICENSE
-rwxr-xr-x  1 colinmills colinmills  1422 Aug 18 13:01 [01;32mMakefile[0m
-rwxr-xr-x  1 colinmills colinmills  3614 Aug 18 13:01 [01;32mREADME.md[0m
drwxr-xr-x  2 colinmills colinmills  4096 Aug 18 13:01 [01;34m_action_files[0m
-rw-r--r--  1 colinmills colinmills  3716 Aug 18 13:01 _config.yml
drwxr-xr-x  2 colinmills colinmills  4096 Aug 18 13:01 [01;34m_fastpages_docs[0m
drwxr-xr-x  2 colinmills colinmills  4096 Aug 18 13:01 [01;34m_includes[0m
drwxr-xr-x  2 colinmills colinmills  4096 Aug 18 13:01 [01;34m_layouts[0m
drwxr-xr-x  4 colinmills colinmills  4096 Aug 28 15:27 [01;34m_notebooks[0m
drwxr-xr-x  2 colinmills colinmills  4096 Aug 28 15:24 [01;34m_pages[0m
drwxr-xr-x  2 colinmills colinmills  4096 Aug 18 13:01 [01;34m_plugins[0m
drwxr-xr-x  2 colinmills colinmills  4096 Aug 28 15:24 [01;34m_posts[0m
drwxr-xr-x  3 colinmills colinmills  4096 Aug 18 13:01 [01;34m_sass[0m
drwxr-xr-x  2 colinmills colinmills  4096 Aug 18 13:01 [01;34m_word[0m
drwxr-xr-x  4 colinmills colinmills  4096 Aug 18 13:01 [01;34massets[0m
-rwxr-xr-x  1 colinmills colinmills  1136 Aug 18 13:01 [01;32mdocker-compose.yml[0m
drwxr-xr-x  5 colinmills colinmills  4096 Aug 28 15:24 [01;34mimages[0m
-rw-r--r--  1 colinmills colinmills  1061 Aug 18 13:01 index.html
drwxr-xr-x  2 colinmills colinmills  4096 Aug 18 13:01 [01;34mpython[0m



Look for posts
/home/colinmills/vscode/APCSP/_posts
total 236
-rw-r--r-- 1 colinmills colinmills 21306 Aug 18 13:01 2022-06-01-TT160-deploy.md
-rw-r--r-- 1 colinmills colinmills  5861 Aug 18 13:01 2022-07-07-PBL-binary.md
-rw-r--r-- 1 colinmills colinmills  3085 Aug 18 13:01 2022-07-08-PBL-grade_calc.md
-rw-r--r-- 1 colinmills colinmills  3698 Aug 18 13:01 2022-07-08-PBL-graph.md
-rw-r--r-- 1 colinmills colinmills  5729 Aug 18 13:01 2022-07-08-PBL-life.md
-rw-r--r-- 1 colinmills colinmills 14387 Aug 18 13:01 2022-07-08-PBL-snake.md
-rw-r--r-- 1 colinmills colinmills   334 Aug 18 13:01 2022-07-10-PBL-database.md
-rw-r--r-- 1 colinmills colinmills  2908 Aug 18 13:01 2022-07-10-PBL-jokes.md
-rw-r--r-- 1 colinmills colinmills  4046 Aug 18 13:01 2022-07-10-PBL-rapidapi.md
-rw-r--r-- 1 colinmills colinmills  6685 Aug 18 13:01 2022-07-19-PBL-calculator.md
-rw-r--r-- 1 colinmills colinmills 23325 Aug 18 13:01 2022-07-25-CSP-workshop.md
-rw-r--r-- 1 colinmills colinmills  2333 Aug 18 13:01 2022-08-15-TP000-student_score_history.md
-rw-r--r-- 1 colinmills colinmills  4363 Aug 18 13:01 2022-08-15-TP100-pseudo_code.md
-rw-r--r-- 1 colinmills colinmills  7968 Aug 18 13:01 2022-08-15-TR100-tool_setup.md
-rw-r--r-- 1 colinmills colinmills 15409 Aug 28 15:24 2022-08-15-TT100-tools.md
-rw-r--r-- 1 colinmills colinmills  5590 Aug 22 18:47 2022-08-15-TT101-vscode-wsl.md
-rw-r--r-- 1 colinmills colinmills  2155 Aug 22 18:47 2022-08-22-TR110-intro_python.md
-rw-r--r-- 1 colinmills colinmills  5173 Aug 18 13:01 2022-08-22-TT110-fastpages.md
-rw-r--r-- 1 colinmills colinmills  2798 Aug 22 18:47 2022-08-22-TT110-focus.md
-rw-r--r-- 1 colinmills colinmills  2196 Aug 28 15:24 2022-08-29-Points-data_abstract.md
-rw-r--r-- 1 colinmills colinmills  2527 Aug 28 15:24 2022-08-29-TR120-data_abstract.md
-rw-r--r-- 1 colinmills colinmills 10683 Aug 18 13:01 2022-08-29-TT120-agile.md
-rw-r--r-- 1 colinmills colinmills  4705 Aug 28 15:24 2022-08-29-TT120-html_fragments.md
-rw-r--r-- 1 colinmills colinmills  9037 Aug 18 13:01 2022-09-05-TP130-create_performance_task.md
-rw-r--r-- 1 colinmills colinmills  7753 Aug 18 13:01 2022-09-05-TP131-create-task-bria.md
-rw-r--r-- 1 colinmills colinmills  8066 Aug 18 13:01 2022-09-05-TR130-creative_development.md
-rw-r--r-- 1 colinmills colinmills  3520 Aug 18 13:01 2022-09-05-TT130-applab.md
-rw-r--r-- 1 colinmills colinmills   720 Aug 18 13:01 README.md
-rw-r--r-- 1 colinmills colinmills   376 Aug 28 15:24 sample.md



Look for notebooks
/home/colinmills/vscode/APCSP/_notebooks
total 152
-rw-r--r-- 1 colinmills colinmills 14243 Aug 18 13:01 2022-06-01-TT150-webapi_tutorial.ipynb
-rw-r--r-- 1 colinmills colinmills  8653 Aug 18 13:01 2022-07-21-PBL-neo4j_intro.ipynb
-rw-r--r-- 1 colinmills colinmills 11694 Aug 24 13:58 2022-08-22-TP110-python_hello.ipynb
-rw-r--r-- 1 colinmills colinmills 20003 Aug 22 18:47 2022-08-22-TT110-anthony_and_sahil.ipynb
-rw-r--r-- 1 colinmills colinmills 12668 Aug 28 15:24 2022-08-22-TT110-bash_tutorial.ipynb
-rw-r--r-- 1 colinmills colinmills 35721 Aug 28 15:27 2022-08-25-tool_check.ipynb
-rw-r--r-- 1 colinmills colinmills 13286 Aug 28 15:24 2022-08-29-TP120-python_lists.ipynb
-rw-r--r-- 1 colinmills colinmills 12632 Aug 18 13:01 2022-09-05-TT130-js_tutorial.ipynb
-rw-r--r-- 1 colinmills colinmills   771 Aug 18 13:01 README.md
drwxr-xr-x 2 colinmills colinmills  4096 Aug 22 18:47 images



Look for images in notebooks, print working directory, list files
/home/colinmills/vscode/APCSP/_notebooks/images
total 100
-rw-r--r-- 1 colinmills colinmills 101617 Aug 22 18:47 kernels.png



Navigate to project, then navigate to area wwhere files were cloned
show the contents of README.md

[//]: # (This template replaces README.md when someone creates a new repo with the fastpages template.)

![](https://github.com/nighthawkcoders/APCSP/workflows/CI/badge.svg) 
![](https://github.com/nighthawkcoders/APCSP/workflows/GH-Pages%20Status/badge.svg) 
[![](https://img.shields.io/static/v1?label=fastai&message=fastpages&color=57aeac&labelColor=black&style=flat&logo=data:image/png;base64,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)](https://github.com/fastai/fastpages)

https://nighthawkcoders.github.io/APCSP/

# My Blog


_powered by [fastpages](https://github.com/fastai/fastpages)_


## What To Do Next?

Great!  You have setup your repo.  Now its time to start writing content.  Some helpful links:

- [Writing Blogs With Jupyter](https://github.com/fastai/fastpages#writing-blog-posts-with-jupyter)

- [Writing Blogs With Markdown](https://github.com/fastai/fastpages#writing-blog-posts-with-markdown)

- [Writing Blog Posts With Word](https://github.com/fastai/fastpages#writing-blog-posts-with-microsoft-word)

- [(Optional) Preview Your Blog Locally](_fastpages_docs/DEVELOPMENT.md)

Note: you may want to remove example blog posts from the `_posts`,  `_notebooks` or `_word` folders (but leave them empty, don't delete these folders) if you don't want these blog posts to appear on your site.

Please use the [nbdev & blogging channel](https://forums.fast.ai/c/fastai-users/nbdev/48) in the fastai forums for any questions or feature requests.

end of README.md



Show the shell environment variables, key on left of equal value on right

SHELL=/bin/bash
PYTHONUNBUFFERED=1
project=/home/colinmills/vscode/APCSP
CONDA_EXE=/home/colinmills/anaconda3/bin/conda
_CE_M=
APPLICATION_INSIGHTS_NO_DIAGNOSTIC_CHANNEL=1
WSL_DISTRO_NAME=Ubuntu
ELECTRON_RUN_AS_NODE=1
VSCODE_AMD_ENTRYPOINT=vs/workbench/api/node/extensionHostProcess
NAME=4030uSad
PWD=/home/colinmills/vscode/APCSP
LOGNAME=colinmills
CONDA_PREFIX=/home/colinmills/anaconda3
project_dir=/home/colinmills/vscode
HOME=/home/colinmills
LANG=C.UTF-8
WSL_INTEROP=/run/WSL/6844_interop
LS_COLORS=rs=0:di=01;34:ln=01;36:mh=00:pi=40;33:so=01;35:do=01;35:bd=40;33;01:cd=40;33;01:or=40;31;01:mi=00:su=37;41:sg=30;43:ca=30;41:tw=30;42:ow=34;42:st=37;44:ex=01;32:*.tar=01;31:*.tgz=01;31:*.arc=01;31:*.arj=01;31:*.taz=01;31:*.lha=01;31:*.lz4=01;31:*.lzh=01;31:*.lzma=01;31:*.tlz=01;31:*.txz=01;31:*.tzo=01;31:*.t7z=01;31:*.zip=01;31:*.z=01;31:*.dz=01;31:*.gz=01;31:*.lrz=01;31:*.lz=01;31:*.lzo=01;31:*.xz=01;31:*.zst=01;31:*.tzst=01;31:*.bz2=01;31:*.bz=01;31:*.tbz=01;31:*.tbz2=01;31:*.tz=01;31:*.deb=01;31:*.rpm=01;31:*.jar=01;31:*.war=01;31:*.ear=01;31:*.sar=01;31:*.rar=01;31:*.alz=01;31:*.ace=01;31:*.zoo=01;31:*.cpio=01;31:*.7z=01;31:*.rz=01;31:*.cab=01;31:*.wim=01;31:*.swm=01;31:*.dwm=01;31:*.esd=01;31:*.jpg=01;35:*.jpeg=01;35:*.mjpg=01;35:*.mjpeg=01;35:*.gif=01;35:*.bmp=01;35:*.pbm=01;35:*.pgm=01;35:*.ppm=01;35:*.tga=01;35:*.xbm=01;35:*.xpm=01;35:*.tif=01;35:*.tiff=01;35:*.png=01;35:*.svg=01;35:*.svgz=01;35:*.mng=01;35:*.pcx=01;35:*.mov=01;35:*.mpg=01;35:*.mpeg=01;35:*.m2v=01;35:*.mkv=01;35:*.webm=01;35:*.ogm=01;35:*.mp4=01;35:*.m4v=01;35:*.mp4v=01;35:*.vob=01;35:*.qt=01;35:*.nuv=01;35:*.wmv=01;35:*.asf=01;35:*.rm=01;35:*.rmvb=01;35:*.flc=01;35:*.avi=01;35:*.fli=01;35:*.flv=01;35:*.gl=01;35:*.dl=01;35:*.xcf=01;35:*.xwd=01;35:*.yuv=01;35:*.cgm=01;35:*.emf=01;35:*.ogv=01;35:*.ogx=01;35:*.aac=00;36:*.au=00;36:*.flac=00;36:*.m4a=00;36:*.mid=00;36:*.midi=00;36:*.mka=00;36:*.mp3=00;36:*.mpc=00;36:*.ogg=00;36:*.ra=00;36:*.wav=00;36:*.oga=00;36:*.opus=00;36:*.spx=00;36:*.xspf=00;36:
CONDA_PROMPT_MODIFIER=(base) 
PYDEVD_USE_FRAME_EVAL=NO
posts=/home/colinmills/vscode/APCSP/_posts
LESSCLOSE=/usr/bin/lesspipe %s %s
VSCODE_HANDLES_SIGPIPE=true
TERM=xterm-256color
_CE_CONDA=
LESSOPEN=| /usr/bin/lesspipe %s
USER=colinmills
PYTHONIOENCODING=utf-8
notebooks=/home/colinmills/vscode/APCSP/_notebooks
CONDA_SHLVL=1
SHLVL=1
PAGER=cat
project_repo=https://github.com/nighthawkcoders/APCSP.git
VSCODE_CWD=/mnt/c/Users/colin/AppData/Local/Programs/Microsoft VS Code
CONDA_PYTHON_EXE=/home/colinmills/anaconda3/bin/python
PS1=[PEXP\[\]ECT_PROMPT>
CONDA_DEFAULT_ENV=base
WSLENV=VSCODE_WSL_EXT_LOCATION/up
VSCODE_WSL_EXT_LOCATION=/mnt/c/Users/colin/.vscode/extensions/ms-vscode-remote.remote-wsl-0.66.3
PATH=/home/colinmills/anaconda3/bin:/home/colinmills/anaconda3/condabin:/home/colinmills/.vscode-server/bin/e4503b30fc78200f846c62cf8091b76ff5547662/bin/remote-cli:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin:/usr/games:/usr/local/games:/usr/lib/wsl/lib:/mnt/c/Program Files/National Instruments/Shared/OpenVINO:/mnt/c/Program Files/Common Files/Oracle/Java/javapath:/mnt/c/WINDOWS/system32:/mnt/c/WINDOWS:/mnt/c/WINDOWS/System32/Wbem:/mnt/c/WINDOWS/System32/WindowsPowerShell/v1.0:/mnt/c/WINDOWS/System32/OpenSSH:/mnt/c/Program Files (x86)/Common Files/Acronis/VirtualFile:/mnt/c/Program Files (x86)/Common Files/Acronis/VirtualFile64:/mnt/c/Program Files (x86)/Common Files/Acronis/FileProtector:/mnt/c/Program Files (x86)/Common Files/Acronis/FileProtector64:/mnt/c/Program Files (x86)/Common Files/Acronis/SnapAPI:/mnt/c/Program Files/Git/cmd:/mnt/c/Program Files/dotnet:/mnt/c/Users/colin/AppData/Local/Microsoft/WindowsApps:/mnt/c/Users/colin/AppData/Local/Programs/Microsoft VS Code/bin:/mnt/c/Program Files (x86)/Nmap
VSCODE_NLS_CONFIG={"locale":"en","availableLanguages":{}}
HOSTTYPE=x86_64
VSCODE_HANDLES_UNCAUGHT_ERRORS=true
OLDPWD=/home/colinmills/vscode/APCSP/_notebooks/images
VSCODE_IPC_HOOK_CLI=/tmp/vscode-ipc-506b47ef-a7b1-4515-b391-3b2113b498ed.sock
_=/usr/bin/env




show the secrets of .git
total 68
-rw-r--r--  1 colinmills colinmills   353 Aug 28 17:06 FETCH_HEAD
-rw-r--r--  1 colinmills colinmills    23 Aug 18 13:01 HEAD
-rw-r--r--  1 colinmills colinmills    41 Aug 28 15:24 ORIG_HEAD
drwxr-xr-x  2 colinmills colinmills  4096 Aug 18 13:00 [0m[01;34mbranches[0m
-rw-r--r--  1 colinmills colinmills   269 Aug 18 13:01 config
-rw-r--r--  1 colinmills colinmills    73 Aug 18 13:00 description
drwxr-xr-x  2 colinmills colinmills  4096 Aug 18 13:00 [01;34mhooks[0m
-rw-r--r--  1 colinmills colinmills 20293 Aug 28 15:27 index
drwxr-xr-x  2 colinmills colinmills  4096 Aug 18 13:00 [01;34minfo[0m
drwxr-xr-x  3 colinmills colinmills  4096 Aug 18 13:01 [01;34mlogs[0m
drwxr-xr-x 74 colinmills colinmills  4096 Aug 26 11:30 [01;34mobjects[0m
-rw-r--r--  1 colinmills colinmills   271 Aug 18 13:01 packed-refs
drwxr-xr-x  5 colinmills colinmills  4096 Aug 18 13:01 [01;34mrefs[0m

look at config file
[core]
	repositoryformatversion = 0
	filemode = true
	bare = false
	logallrefupdates = true
[remote "origin"]
	url = https://github.com/nighthawkcoders/APCSP.git
	fetch = +refs/heads/*:refs/remotes/origin/*
[branch "master"]
	remote = origin
	merge = refs/heads/master



File listing and status
-rw-r--r-- 1 colinmills colinmills 809 Aug 28 17:07 sample.md
 15 132 809 sample.md

Command 'mdless' not found, did you mean:

  command 'dless' from deb phast (1.5+dfsg-1)

Try: sudo apt install <deb name>