# [Dot_files](https://youtu.be/y6XCebnB9gs?si=u9g03qcuPGH9sUrm)
 - Dependencies
    - macOS
       - brew
         `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"` 
       - git
         `brew install git`
       - GNU stow
         `brew install stow`
       - Tree
         `brew install tree`
       - [fzf](https://github.com/junegunn/fzf.git)
         `brew install fzf`
       - [zoxide](https://github.com/ajeetdsouza/zoxide.git)
         `brew install zoxide`
       
         
     - Ubuntu
       - git
         `sudo apt install git`
       - GNU stow
         `sudo apt install stow`
       - Tree
         `sudo apt install tree`
       - [fzf](https://github.com/junegunn/fzf.git)
         `sudo apt install fzf`
       - [zoxide](https://github.com/ajeetdsouza/zoxide.git)
         `curl -sSfL https://raw.githubusercontent.com/ajeetdsouza/zoxide/main/install.sh | sh`
 
    

    
  
### Add these lines to .zshrc
    eval "$(zoxide init zsh)"
    source <(fzf --zsh)


