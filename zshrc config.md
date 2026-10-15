# Zsh Configuration

parse_git_branch() {
    git branch 2> /dev/null | sed -n -e 's/^\* \(.*\)/[\1]/p'
}
setopt PROMPT_SUBST
PROMPT=$'%B%F{red}______________\n%n: %1~ >%f %F{green} $(parse_git_branch)  %b%f\n'


# Standard aliases
alias ll='ls -la'
alias la='ls -A'
alias l='ls -lF'
alias grep='grep --color=auto'

alias zs="source ~/.zshrc"
alias zo="code ~/.zshrc"

alias gs="git status"
alias gcm="git commit -m "
alias gurl="git remote get-url origin"
alias gacm="git add -u .; git status; git commit -m "
alias ga="git add .; git status"
alias gau="git add -u"
alias gl="git branch"
alias gch="git checkout "
alias gurl="git remote -v"
alias gpuo="git push --set-upstream origin \$(git branch --show-current)"
alias gcpr="gh pr create"
alias grepo="gh repo view --web"
alias gpr="gh pr view --web"
alias grh="git reset head~1"
alias gca="git status; git commit --amend --no-edit; git status"
alias grim="git rebase -i main"
alias gfa="git fetch --all"
alias grom="git fetch --all && git rebase origin/main"
alias grum="git rebase upstream main"
alias gbd="git branch -d "
alias gbbd="git branch -D "


