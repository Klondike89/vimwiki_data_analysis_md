= Basic Vim References =


=== Yank and Paste ===

To *copy an entire line* place the cursor at the beginning of the line and type:
- yy

To copy multiple lines:
- 3yy

=== How to jump to a specific line ===
- {line_number}<shift>G

=== How to record and run a macro ===

To Record
- {Be in NORMAL mode}
- 0   | "Start at begining of line to avoid confusion"
- q<Maco Name>  | "This starts the recording process" "Name a-z"
- {Preform your Macro here}
- Esc
- q

To replay
- Enter number of times to repeat
- @
- Maco Name

Macro Tricks
- Ctrl a    | "Increments number"

