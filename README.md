For your own sanity, bind ESC to CapsLock\
Everything here is case sensitive\
This is just my personal knowledge, sharing with others

## Viewer mode -> ESC | Insert Mode -> i
#### Notes
    yank = copy
    yank and delete go to the same buffer, this means if you delete something, p will paste what you delete
#### Single Commands
    h, j, k, l -> left, down, up, right
    dd -> delete entire line
    u -> undo
    r -> redo
    p -> paste
    y -> yank
    / -> start searching, your query appears at the bottom in VSCode
    n -> iterate down through search results
    enter -> exit search/down a line
    o -> down a line and brings you into insert mode
    O -> up a line and brings you into insert mode
    v -> start highlight
    a -> insert mode to the right of your cursor
    
#### Combo Commands
    d + e -> delete word
    c + e -> delete from cursor to end of word
    g + d -> go to definition
    ctrl + o -> go backs
    shift + n -> iterate up through search results
    v + e -> highlight to end of word
    v + i + ' -> highlight between quotes on the line
    d + i + ' -> delete between quotes on the line 
    c + i + ' -> copy between quotes on the line
    f + a -> puts your cursor to the first a of the line, a is replaceable with any char
    t + a -> puts your cursor right before the first a of the line, a is replaceable with any char
