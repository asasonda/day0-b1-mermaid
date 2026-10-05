``` mermaid

flowchart TD
    mulai(mulai)
    a[nilai andi = 80]
    b{lulus?}

    mulai --> a
    a --> b

    b --> |yes| d[Andi Lulus]
    b --> |no| e[Tidak lolos]

    
    e --> a

```
