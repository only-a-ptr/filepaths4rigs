
# Notes on Unix/Linux systems

One quote says it all: "[(it’s crazy that) there’s no standard encoding for filenames across all Unix/Linux/POSIX
systems](https://www.dwheeler.com/essays/fixing-unix-linux-filenames.html#utf8)"

Apparently *nix filesystems do not have a defined encoding
and they don't even prohibit dangerous characters (like control characters).
An excellent overview of the situation: https://www.dwheeler.com/essays/fixing-unix-linux-filenames.html

Mozilla requires all Linux paths to be UTF-8: https://support.mozilla.org/en-US/kb/utf-8-only-file-paths TODO: What about Android/BSD?
