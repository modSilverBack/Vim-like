# vim-like
A vim-inspired text editor using ncurses and C++

I was pretty interested to see how text editors like vim worked, so I
decided to try my hand at making my own editor. I'm using ncurses here
because it's much easier to use than escape sequences, and C++ because 
I like it better than C, and because I'd never written anything this big
in C++ before.


## Usage

```
./vim-like [path_to_file_here]
```

Cursor movement work like vim's, but vimperor doesn't support adding numbers before motions. Typing "3j" to move the cursor down 3 lines won't work; you'll have to type "j" 3 times to do that.

Press the escape key to go to Normal mode, "i" to go to Insert mode, and "R" to go to Replace mode. In vimperor these modes work very much like vim's, although Normal mode is slightly different. While in Normal mode, press "s" to save a file, and "q" to exit vimperor.

Vimperor also supports the "x", "w", and "b" motions. They work similar to vim's implementation of these motions.
