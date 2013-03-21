tini_autovirtualenv
===================

bash helper to auto active python virtualenv, works well under tmux

when you first enter into a dicrector which contains a .env file and the .env file contains one line which is a virtualenv name. Then, the virtualenv will be actived automatically.

If you change path to the sub dicrector of the work place, nothing will be changed. However, when you leave the work palace, the virtualenv will be deactived.

As Tmux could only use the .bash_profile. What we could do is just execute the .bashrc file in the .bash_profile. All in all, this works well under Tmux.

Just enjoy it.

My Email: jefferson.lyu@gmail.com
