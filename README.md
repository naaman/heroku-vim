heroku-vim
==========

Install's vim in a dyno and starts a bash session.

## Install

```
$ heroku plugins:install https://github.com/naaman/heroku-vim
```

## Use

```
heroku vim
```

## Example Output
```
$ heroku vim
Running `mkdir vim
curl https://s3.amazonaws.com/heroku-vim/vim-7.3.tar.gz --location --silent | tar xz -C vim
export PATH=$PATH:/app/vim/bin
bash` attached to terminal... up, run.2135
~ $ vim
```
