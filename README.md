# my_zsh
my zsh setting


zplug 'plugins/bundler', from:oh-my-zsh, if:'which bundle'
zplug 'plugins/colored-man-pages', from:oh-my-zsh
zplug 'plugins/completion', from:oh-my-zsh
zplug 'plugins/extract', from:oh-my-zsh
zplug 'plugins/fancy-ctrl-z', from:oh-my-zsh
zplug 'plugins/git', from:oh-my-zsh, if:'which git'
220 #zplug 'plugins/gpg-agent', from:oh-my-zsh, if:'which gpg-agent'
221 zplug 'plugins/httpie', from:oh-my-zsh, if:'which httpie'
222 zplug 'plugins/nanoc', from:oh-my-zsh, if:'which nanoc'
223 zplug 'plugins/nmap', from:oh-my-zsh, if:'which nmap'
224 zplug 'plugins/tmux', from:oh-my-zsh, if:'which tmux'
225
226 #zplug 'b4b4r07/enhancd', use:init.sh
227 #zplug 'b4b4r07/zsh-vimode-visual', defer:3
228 # Using branch 'next' introduces a color regression, so we fall back to master
229 # ofr now. See https://github.com/bhilburn/powerlevel9k/pull/703 for details.
230 #zplug 'bhilburn/powerlevel9k', use:powerlevel9k.zsh-theme, at:next
231 zplug 'bhilburn/powerlevel9k', use:powerlevel9k.zsh-theme
232 zplug "junegunn/fzf-bin", as:command, from:gh-r, rename-to:"fzf", frozen:1
233 zplug "junegunn/fzf", use:"shell/key-bindings.zsh"
234 zplug 'knu/zsh-manydots-magic', use:manydots-magic, defer:3
235 zplug 'seebi/dircolors-solarized', ignore:"*", as:plugin
236 zplug 'Tarrasch/zsh-bd'
237 zplug 'zsh-users/zsh-autosuggestions'
238 zplug 'zsh-users/zsh-completions', defer:2
239 zplug 'zsh-users/zsh-syntax-highlighting', defer:2
240 zplug 'zsh-users/zsh-history-substring-search'
