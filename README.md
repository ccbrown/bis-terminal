# bis-terminal

This repo documents "best in slot" (BIS) replacements for common command line utilities, most of which are from the [POSIX command list](https://en.wikipedia.org/wiki/List_of_POSIX_commands).

To be eligible, the BIS alternative must be a drop-in replacement for the original, or close. It doesn't need to have feature parity, but it shouldn't feel like a completely new utility either – anyone familiar with the original should be able to use its basic functionality with little-to-no learning curve.

## Commands

| Command | Description | Best In Slot | BIS Features |
| --- | --- | --- | --- |
| admin | Create and administer SCCS files |
| alias | Define or display aliases |
| ar | Create and maintain library archives |
| asa | Interpret carriage-control characters |
| at | Execute commands at a later time |
| awk | Pattern scanning and processing language |
| basename | Return non-directory portion of a pathname; see also dirname |
| batch | Schedule commands to be executed in a batch queue |
| bc | Arbitrary-precision arithmetic language |
| bg | Run jobs in the background |
| cc/c17 | Compile standard C programs |
| cal | Print a calendar |
| [cat](https://www.man7.org/linux/man-pages/man1/cat.1.html) | Concatenate and print files | [bat](https://github.com/sharkdp/bat) | Syntax highlighting, Git integration, non-printable characters |
| [cd](https://man7.org/linux/man-pages/man1/cd.1p.html) | Change the working directory | [zoxide](https://github.com/ajeetdsouza/zoxide) | Remembers history for smarter navigation |
| cflow | Generate a C-language call graph |
| chgrp | Change the file group ownership |
| chmod | Change the file modes/attributes/permissions |
| chown | Change the file ownership |
| cksum | Write file checksums and sizes |
| cmp | Compare two files; see also diff |
| comm | Select or reject lines common to two files |
| command | Execute a simple command |
| compress | Compress data |
| cp | Copy files |
| crontab | Schedule periodic background work |
| csplit | Split files based on context |
| ctags | Create a tags file |
| cut | Cut out selected fields of each line of a file |
| cxref | Generate a C-language program cross-reference table |
| date | Display the date and time |
| dd | Convert and copy a file |
| delta | Make a delta (change) to an SCCS file |
| df | Report free disk space |
| diff | Compare two files; see also cmp |
| dirname | Return the directory portion of a pathname; see also basename |
| du | Estimate file space usage |
| echo | Write arguments to standard output |
| ed | The standard text editor |
| env | Set the environment for command invocation |
| ex | Text editor |
| expand | Convert tabs to spaces |
| expr | Evaluate arguments as an expression |
| false | Return false value |
| fc | Process the command history list |
| fg | Run jobs in the foreground |
| file | Determine file type |
| find | Find files |
| fold | Filter for folding lines |
| fuser | List process IDs of all processes that have one or more files open |
| gencat | Generate a formatted message catalog |
| get | Get a version of an SCCS file |
| getconf | Get configuration values |
| getopts | Parse utility options |
| gettext | Retrieve text string from messages object |
| [grep](https://man7.org/linux/man-pages/man1/grep.1.html) | Search text for a pattern | [ripgrep](https://github.com/BurntSushi/ripgrep) | **Speed**, automatic filtering, replacements, compressed file search, preprocessing filters |
| hash | Hash database access method |
| head | Copy the first part of files |
| iconv | Codeset conversion |
| id | Return user identity |
| ipcrm | Remove a message queue, semaphore set, or shared memory segment identifier |
| ipcs | Report interprocess communication facilities status |
| jobs | Display status of jobs in the current session |
| join | Merges two sorted text files based on the presence of a common field |
| kill | Terminate or signal processes |
| lex | Generate programs for lexical tasks |
| link | Create a hard link to a file |
| ln | Link files |
| locale | Get locale-specific information |
| localedef | Define locale environment |
| logger | Log messages |
| logname | Return the user's login name |
| lp | Send files to a printer |
| [ls](https://man7.org/linux/man-pages/man1/ls.1.html) | List directory contents | [exa](https://github.com/ogham/exa) | Color coding, speed, Git awareness, wide view |
| m4 | Macro processor |
| mailx | Process messages |
| make | Maintain, update, and regenerate groups of programs |
| man | Display system documentation |
| mesg | Permit or deny messages |
| mkdir | Make directories |
| mkfifo | Make FIFO special files |
| more | Display files on a page-by-page basis |
| msgfmt | Create messages objects from messages object files |
| mv | Move or rename files |
| newgrp | Change to a new group |
| ngettext | Retrieve text string from messages object with plural form |
| nice | Invoke a utility with an altered nice value |
| nl | Line numbering filter |
| nm |  |
| nohup | Invoke a utility immune to hangups |
| od | Dump files in various formats |
| paste | Merge corresponding or subsequent lines of files |
| patch | Apply changes to files |
| pathchk | Check pathnames |
| pax | Portable archive interchange |
| pr | Paginate or columnate files for printing |
| printf | Write formatted output |
| prs | Print an SCCS file |
| ps | Report process status |
| pwd | Print working directory |
| read | Read a line from standard input |
| readlink | Print destination of a symbolic link |
| realpath | Resolve a symbolic link |
| renice | Set nice values of running processes |
| rm | Remove directory entries |
| rmdel | Remove a delta from an SCCS file |
| rmdir | Remove directories, if they are empty. |
| sact | Print current SCCS file-editing activity |
| sccs | Front end for the SCCS subsystem |
| [sed](https://www.man7.org/linux/man-pages/man1/sed.1p.html) | Stream editor | [sd](https://github.com/chmln/sd) | Speed, common sense defaults, intuitive expression syntax |
| sh | Shell, the standard command language interpreter |
| sleep | Suspend execution for an interval |
| sort | Sort, merge, or sequence check text files |
| split | Split files into pieces |
| strings | Find printable strings in files |
| strip | Remove unnecessary information from executable files |
| stty | Set the options for a terminal |
| tabs | Set terminal tabs |
| tail | Copy the last part of a file |
| talk | Talk to another user |
| tee | Duplicate the standard output |
| test | Evaluate expression |
| time | Retrieve and format time and date |
| timeout | Run command with a time limit |
| [top](https://man7.org/linux/man-pages/man1/top.1.html) | Display processes | [htop](https://github.com/htop-dev/htop) | Improved interface |
| touch | Change file access and modification times |
| tput | Change terminal characteristics |
| tr | Translate characters |
| true | Return true value |
| tsort | Topological sort |
| tty | Return user's terminal name |
| type | Displays how a name would be interpreted if used as a command |
| ulimit | Set or report file size limit |
| umask | Get or set the file mode creation mask |
| unalias | Remove alias definitions |
| uname | Return system name | [fastfetch](https://github.com/fastfetch-cli/fastfetch) | Pretty output, more information and extensibility |
| uncompress | Expand compressed data |
| unexpand | Convert spaces to tabs |
| unget | Undo a previous get of an SCCS file |
| uniq | Report or filter out repeated lines in a file |
| unlink | Call the unlink function |
| uucp | System-to-system copy |
| uudecode | Decode a binary file |
| uuencode | Encode a binary file |
| uustat | uucp status inquiry and job control |
| uux | Remote command execution |
| val | Validate SCCS files |
| vi | Screen-oriented (visual) display editor |
| wait | Await process completion |
| wc | Line, word and byte or character count |
| what | Identify SCCS files |
| who | Display who is on the system |
| write | Write to another user's terminal |
| xargs | Construct argument lists and invoke utility |
| xgettext | Extract gettext calls from C source code strings |
| yacc | Yet another compiler compiler |
| zcat | Expand and concatenate data |
