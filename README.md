# git-pusher

该脚本用于简化git push，经常用于定时提交. 如配合cron使用

```
* * * * * git-pusher your-project
```

### usage

```
USAGE: ./git-pusher [-h] path [remote [branch]]

DESCRIPTION:
    This script use to simplify git push.

    path - the top path of you project
    remote - the remote name of repository, default is origin
    branch - the branch of repository, default is master

OPTIONS:
    -h                Show this help message and exit
```

