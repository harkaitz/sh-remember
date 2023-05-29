# SH-REMEMBER

A collection for project and todo management.

## Help

alert

    Usage: alert -i RCFILE | -e | MESSAGE
    
    Write an alert to ~/ALERTS.md FILE. The contents of this file will
    be printed on each new shell every 2H.

alog

    Usage: alog -r|p|d
    
    Record and play 30 second audiologs "alog.wav". This is usefull to
    know where you left some work.

changes

    Usage: changes
    
    Print the 10 most recently touched files. If the current directory
    is a git repo, it will only consider commited files.

note

    Usage: note OPTS... | NOTE...
    
    Add a note to the notes file.
    
        -v      : Show configuration.
        -e      : Edit with *${EDITOR:-vi}* or *${EDITOR_X:-xdg-open}*
        -l      : List notes.
        -d      : Delete last note.

run

    Usage: run [-V] [ACTION]
    
    Define an action list for a working directory. Each action is a
    script, inside `./run/ACTION` or `$RUN_DIR/COLLECTION/ACTION`.
    
    To know which collection applies to a working directory it
    executes `$RUN_DIR/COLLECTION/match.sh`.

todo

    Usage: todo -e | MESSAGE
    
    Edit the TODO.md FILE in the working directory.

trash

    Usage: trash FILES... DIRS...
    
    Move files to ~/TRASH/YYYY-MM-DD.

## Collaborating

For making bug reports, feature requests and donations visit
one of the following links:

1. [gemini://harkadev.com/oss/](gemini://harkadev.com/oss/)
2. [https://harkadev.com/oss/](https://harkadev.com/oss/)
