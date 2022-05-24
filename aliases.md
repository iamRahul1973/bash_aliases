# Common
* alias wr='cd /var/www/html'
* alias open='nautilus --browser'

# Laravel Stuff
* alias art='php artisan'
* alias sail='[ -f sail ] && bash sail || bash vendor/bin/sail'
* alias setIde4Lara='composer require --dev barryvdh/laravel-ide-helper && php artisan clear-compiled && php artisan ide-helper:generate'
* alias testf='art test --filter='

# Spatie Multitenancy
* function tenartdb { php artisan tenants:artisan "$1 --database=tenant"; }
* function tenart { php artisan tenants:artisan "$2 --database=tenant" --tenant=$1; }

# Git Stuff
* alias ga='git add'
* alias gaa='git add .'
* alias gc='git commit -m '
* alias gp='git push'
* alias gs='git status'
* alias gl='git log'
* alias glog='git log --graph --pretty=format:'\''%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset'\'' --abbrev-commit'
* alias gco='git checkout'
* alias gd='git diff'
* alias gfs='git flow feature start'
* alias gff='git flow feature finish'

# CodeIgniter
* alias citest='vendor/bin/phpunit -c application/tests/'
