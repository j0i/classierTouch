# ZSH Theme - classierTouch
# Author: j0i <z_series@protonmail.ch>
# Prompt is the Oh-my-zsh version of user yarisgutierrez on https://github.com/yarisgutierrez/classyTouch_oh-my-zsh

if [[ $UID -eq 0 ]]; then
    local user_host='%{$terminfo[bold]$fg[white]%}%n@%m%{$reset_color%}'
    local user_symbol='#'
else
    local user_host='%{$terminfo[bold]$fg[white]%}%n@%m%{$reset_color%}'
    local user_symbol='$'
fi

local current_dir='%{$fg[white]%}[%{$reset_color%}%~% %{$fg[white]%}]%{$reset_color%}'
local git_branch='$(git_prompt_info)%{$reset_color%}'


PROMPT="%(?,%{$fg[white]%}┌─╼ ${user_host} ${current_dir}%{$reset_color%} ${git_branch}
%{$fg[white]%}└────╼%{$reset_color%} ,%{$fg[white]%}┌─╼${current_dir}%{$reset_color%} ${git_branch}
%{$fg[white]%}└╼ %{$reset_color%} "

ZSH_THEME_GIT_PROMPT_PREFIX="%{$fg[yellow]%}["
ZSH_THEME_GIT_PROMPT_SUFFIX="] %{$reset_color%}"
