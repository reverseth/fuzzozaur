./fuzzosaur -h                                       
fuzzosaur 0.1.0
Simple program to fuzz web servers… but in Rust !

USAGE:
    fuzzosaur --wordlist <WORDLIST> --target <TARGET>

OPTIONS:
    -h, --help                   Print help information
    -t, --target <TARGET>        Target to fuzz
    -V, --version                Print version information
    -w, --wordlist <WORDLIST>    Wordlist to use




./fuzzosaur -t https://doc.rust-lang.org/ -w dico.txt
