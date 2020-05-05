---
layout: post
title: docs
---

#### notes  

* spacesmacs  
  - fix package download err
    > emacs --insecure   
    > SPC q q 退出 Emacs 并杀掉服务器  

  - vim 

  - python  
    > SPC m V w -> work on virtual environment in WORKON_HOME
    > SPC m c c -> Execute current file in a comint shell 

    

  - keys  
    + SPC + h -> help  
    + SPC f e R 来重载配置  
    + SPC b b -> list all buffer  
    + 
    + normal and insert editor state <- use 'ESC' key to be in normal state, and 'i' to be in insert editor   

  - reference
    + [Spacemacs Basics](https://search-and-deploy.gitlab.io/cheat-sheets/spacemacs-basics/)
    + [spacemacs](https://wiki.archlinux.org/index.php/Spacemacs#Install_Spacemacs)

* emacs  
  - autoload emacs daemon when logining  
    > launchctl unload /Users/zhaowenlong/Library/LaunchAgents/gnu.emacs.daemon.plist
    > launchctl load -w /Users/zhaowenlong/Library/LaunchAgents/gnu.emacs.daemon.plist 

  -  also could use "emacs --fg-daemon" to start the daemon mode  

  - python in emacs  
    + [elpy](https://elpy.readthedocs.io/en/latest/index.html)  
      > C-c C-c evaluates the current script  
      > C-c C-z switches between script and the interactive shell  

    + using 'workon' in emacs based on $WORKON_HOME
      > M-x pyvenv-workon RET codeenv RET  
    + using ipython to 

#### goodbooks  
* [The Lean Startup](https://www.amazon.com/Lean-Startup-Entrepreneurs-Continuous-Innovation/dp/B005MM7HY8/ref=sr_1_1?crid=SVIK2EFUKTBZ&dchild=1&keywords=the+lean+startup&qid=1588064286&sprefix=the+lean+startup%2Caps%2C330&sr=8-1)
* [The Great CEO Within](https://www.goodreads.com/book/show/48691943-the-great-ceo-within)
* [The Effective Executive](https://www.goodreads.com/book/show/48019.The_Effective_Executive?ac=1&from_search=true&qid=76WiM1JVBT&rank=1)  
