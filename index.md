# Project management software
Здесь фиксирую то, что наковырял про софт для project management, ибо забывается легко. Первичным источником информации пока служит только [википедия](https://en.wikipedia.org/wiki/Category:Free_project_management_software) (см. [сравнение](https://en.wikipedia.org/wiki/Comparison_of_project_management_software)), так же есть интересная страничка со средствами для [code review](https://en.wikipedia.org/wiki/List_of_tools_for_code_review). Ещё в статье про git немного интересного [упоминается](https://en.wikipedia.org/wiki/Git_%28software%29#Git_server). Ещё одна немаловажная [страничка](https://en.wikipedia.org/wiki/Comparison_of_source_code_hosting_facilities).

# Таблица с общей информацией

Name | Wikipedia | Website | Demo | Debian package | Annotation | Details | Issue tracking | Time tracking | Code hosting | Code review | Wiki | Worthwhile?
---- | --------- | ------- | ---- | -------------- | ---------- | ------- | :------------: | :-----------: | :----------: | :---------: | :--: | :---------:
Trac | [есть](https://en.wikipedia.org/wiki/Trac) | [есть](http://trac.edgewall.org/) | [3d-party, огорожено](http://www.opendemo.org/trac-demo) | [есть](http://packages.debian.org/trac) | project management | [есть](Project_management_software#Trac) | да | нет | наполовину | нет | да | да
Redmine | [есть](https://en.wikipedia.org/wiki/Redmine) | [есть](http://www.redmine.org/) | [есть своё](https://balhome.matwey.name/redmine/) | [есть наполовину](http://packages.debian.org/redmine) | project management | [есть](Project_management_software#Redmine) | да | да | наполовину | нет | да | да
FusionForge | [есть](https://en.wikipedia.org/wiki/FusionForge) | [есть](http://www.fusionforge.org/) | [сломано](http://fusionforge.fusionforge.org/) | [есть](http://packages.debian.org/fusionforge) | project management | [есть](Project_management_software#FusionForge) | да | [да?](https://en.wikipedia.org/wiki/Comparison_of_project_management_software#Monetary_features) | да? | да? | да | да
Phabricator | [есть](https://en.wikipedia.org/wiki/Phabricator) | [есть](http://phabricator.org/) | [есть, огорожено](https://admin.phacility.com/); [есть](https://phab-01.wmflabs.org/) | [есть](http://packages.debian.org/phabricator) | project management | [есть](Project_management_software#Phabricator) | да | [будет](https://secure.phabricator.com/tag/phrequent/) | да | да | да | да
GitLab | [есть](https://en.wikipedia.org/wiki/GitLab) | [есть](https://about.gitlab.com/) | [есть, огорожено](https://gitlab.com/explore/projects/trending) | [есть, их репозиторий](https://about.gitlab.com/downloads/#debian8) | github-like |  | да | [3d-party](https://github.com/randx/gitlab-time-tracking) | да? | да | да | да
Tryton | [есть](https://en.wikipedia.org/wiki/Tryton) | [есть](http://www.tryton.org/) | [есть](http://demo3.8.tryton.org/ "Login: demo, password: demo.") | [есть](http://packages.debian.org/tryton) | application platform |  | ? | ? | ? | ? | ? | нет
Gogs | нет | [есть](https://gogs.io/) | [есть, огорожено](https://try.gogs.io/explore) | [есть. 3d-party](https://packager.io/gh/pkgr/gogs) | github-like |  | да | нет | да? | да | да | нет
Gitolite | нет | [есть](http://gitolite.com/gitolite/) | [?](http://gitolite.com/gitolite/req.html#trying) | [есть](https://packages.qa.debian.org/g/gitolite3.html) | git hosting |  | нет | нет | да | нет | нет | нет
Gitblit | нет | [есть](http://gitblit.com/) | [есть, огорожено](https://dev.gitblit.com/repositories/) | [нет](http://gitblit.com/setup.html) | git hosting |  | нет | нет | да | нет | нет | нет
GNATS | [есть](https://en.wikipedia.org/wiki/GNATS) | [есть](https://www.gnu.org/software/gnats/) | ? | [есть](http://packages.debian.org/gnats) | bug tracking |  | да | нет | нет | нет | нет | нет
Roundup | [есть](https://en.wikipedia.org/wiki/Roundup_%28issue_tracker%29) | [есть](http://roundup-tracker.org/) | ? | [есть](http://packages.debian.org/roundup) | bug tracking |  | да | нет | нет | нет | нет | нет
Kallithea | [есть](https://en.wikipedia.org/wiki/Kallithea_%28software%29) | [есть](https://kallithea-scm.org/) | ? | нет | code review |  | нет | нет | да | да | нет | нет
Review Board | [есть](https://en.wikipedia.org/wiki/Review_Board) | [есть](https://www.reviewboard.org/) | [есть](http://demo.reviewboard.org/r/) | ? | code review |  | нет | нет | нет | да | нет | нет
Collabtive | [есть](https://en.wikipedia.org/wiki/Collabtive) | [есть](http://collabtive.o-dyn.de/) | [есть](http://collabtive.o-dyn.de/demo/) | [есть](http://packages.debian.org/collabtive) | project management | [есть] (Project_management_software#Collabtive) | да | да | нет | нет | нет | нет
OpenProject | [есть](https://en.wikipedia.org/wiki/OpenProject) | [есть](https://www.openproject.org/) | [есть, огорожено](https://start.openproject.com/) | [есть, 3d-party](https://packager.io/gh/opf/openproject-ce) | project management | [есть] (Project_management_software#Collabtive) | да | да | нет | нет | да | нет

Форки, переименования и миграции: GForge -> FusionForge, Rhodecode -> Kallithea, [Gitorious](https://en.wikipedia.org/wiki/Gitorious) -> GitLab.

Мертвецы: [InDefero](http://www.indefero.net), [ChiliProject](https://www.chiliproject.org/).

Неохваченные: http://web2project.net/ , https://bestpractical.com/ , http://www.kimai.org/ , https://taiga.io/, https://www.gerritcodereview.com/ (дофига [плагинов](https://gerrit.googlesource.com/?format=HTML), кстати) , [WeKan](https://wekan.io/), [Gitboard](http://adewes.github.io/gitboard/index.html), [odoo](https://www.odoo.com/), [Anuko](https://www.anuko.com/time_tracker/), [Taskwarrior](https://taskwarrior.org/).

Проприетарщина поганая: [Stash](https://en.wikipedia.org/wiki/Stash_%28software%29), [Trello](https://trello.com/).

# Redmine
При установке редмайна сразу следует в Administration -> Settings -> Text formatting включить Markdown.
Cheatsheet смотреть [здесь](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).

## Недостатки
1. Нет для debian stretch (сейчас testing), только debian jessie (сейчас stable). Потратил кучу времени (~5 часов) в попытках поставить под debian stretch. Оказалось, что у redmine в кишках жёстко вшиты зависимости от старых рубей, а старые руби (точнее passenger) ломаются от нового libstdc++6. Проще убиться, короче.

## Достоинства
* Легко настривается.
* Issues
* Time Tracking
* Wiki
* Account Administraction
* Project Administration (create, modify, delete)

## Plugins
* Плагины разработчиков редмайна искать [здесь](http://www.redmine.org/plugins).
* Плагины на гитхабе ищутся вот [так](https://github.com/search?utf8=✓&q=redmine+latex&type=Repositories&ref=searchresults).
* Про то, как плагины устанавливать, читать [здесь](http://www.redmine.org/projects/redmine/wiki/Plugins).

## LaTeX
Какая-то интересная [хрень](http://www.redmine.org/issues/1994) про LaTeX в ишусах редмайна.

# Collabtive
Классная штука, но достаточно примитивная. Есть нормальные tasklists, time tracking, но нет source code browsing, например.

# OpenProject
Ещё более классная штука, чем Collabtive. Помимо всяких тасков и скрамов, есть таймлайны (гант считай), есть вики, есть анализ расходов. Но это чисто менеджерская штука, а-ля MS Project. У них, кстати, нормальные и короткие [видео-туториалы](http://www.youtube.com/user/OpenProjectCommunity/videos). Зарегался и создал "компанию" у них в [сайте](https://lablablab.openproject.com/).

# FusionForge
Неплохо, но развивается вяло, кривой интерфейс, беда с time tracking. Зато полноценная wiki.

# Trac

## Недостатки
* Совсем беда с настройкой, [без шуток](http://trac.edgewall.org/wiki/TracInstall#RunningTraconaWebServer). Помню, безболезненно только удавалось настроить на один(!) проект с питоновским встроенным вебсервером, причём без администрирования аккаунтов.
* Ориентирован на плагины, их куча, и какие из них смотреть -- хрен знает. [Сайт](https://trac-hacks.org/), призванный это облегчить, лежит.

# Phabricator

При установке в debian нужно махнуть пару [действий](http://povilasb.com/phabricator/install.html#setup-mysql) в настройке мускуля (либо марии).

## Доки
Официальные доки [здесь](https://secure.phabricator.com/book/phabricator/). На mediawiki тоже [дока](https://www.mediawiki.org/wiki/Phabricator/Help) есть.

## Настройки ssh-хостинга (diffusion)
Чтобы заработал ssh-хостинг проектов, надо сделать несколько телодвижений по мотивам [этой доки](https://secure.phabricator.com/book/phabricator/article/diffusion_hosting/):

~~~
$ adduser blablabla(не отработано) vcs-data # надо ещё shadow править, мрак, короче
$ /usr/share/phabricator/bin/config set phd.user phabricator
$ /usr/share/phabricator/bin/config set diffusion.ssh-user vcs-data
$ /usr/share/phabricator/bin/config set diffusion.ssh-port 2222 # не надо вестись у них на поводу и ставить хостинг проектов на 22ой порт
~~~

А так же создать один файл `/etc/sudoers.d/phabricator` следующего содержания:

~~~
vcs-data ALL=(phabricator) SETENV: NOPASSWD: /usr/bin/git-upload-pack, /usr/bin/git-receive-pack, /usr/bin/hg, /usr/bin/svnserve
www-data ALL=(phabricator) SETENV: NOPASSWD: /usr/bin/git-http-backend, /usr/bin/hg
~~~

И ещё два файла в `/etc/phabricator/`. Один `sshd_config`:

~~~
# NOTE: You must have OpenSSHD 6.2 or newer; support for AuthorizedKeysCommand
# was added in this version.

# NOTE: Edit these to the correct values for your setup.

AuthorizedKeysCommand /etc/phabricator/ssh-hook.sh
AuthorizedKeysCommandUser vcs-data
AllowUsers vcs-data

# You may need to tweak these options, but mostly they just turn off everything
# dangerous.

Port 2222
Protocol 2
PermitRootLogin no
AllowAgentForwarding no
AllowTcpForwarding no
PrintMotd no
PrintLastLog no
PasswordAuthentication no
AuthorizedKeysFile none

PidFile /var/run/sshd-phabricator.pid
~~~


Другой `ssh-hook.sh`:

~~~
#!/bin/sh

# NOTE: Replace this with the username that you expect users to connect with.
VCSUSER="vcs-data"

# NOTE: Replace this with the path to your Phabricator directory.
ROOT="/usr/share/phabricator"

if [ "$1" != "$VCSUSER" ];
then
  exit 1
fi

exec "$ROOT/bin/ssh-auth" $@
~~~

Надо как-то отдельно потом запускать sshd. Ну, делать юнит, наверное.
