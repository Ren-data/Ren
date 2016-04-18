# Ren

[![Join the chat at https://gitter.im/Ren-data/Ren](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/Ren-data/Ren?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Ren is a lightweight data-exchange text format. It is programming language independent with familiar conventions. 

Goals:

- Improve the data signal-to-noise ratio
- Be easy for humans to read and write
- Keep it simple, but not too simple
- Define common, useful datatypes
- Be easy to parse and generate

Uses:

- Communication between people and machines
- Document-oriented databases
- Embedded data storage
- Configuration files
- Messaging

It looks like this:

    "Ren Example 1"		; string
    []					; empty list
    #[]					; empty map
    [a 1 true #three]	; non-empty list
    #[a: 1 b: "two"]	; non-empty map
    -42					; number
    98.6				; another number
    true				; literal true
    false				; literal false
    none				; literal nil/null/nada
    #[					; a bigger map
        quote:	 "? saying: ^"? rocks!^""
        utf-8:    "^(CE91) to ^(cf89)"
        sci-phi:  0.1618e1
        tax-rate: 3.9%
        price:    $79.99
        url:      http://www.ren-data.org/
        email:    info@ren-data.org
        hashtag:  #ren
        date:     2013-04-17/18:37:39-06:00
        warning:  00:02:00  ; = 00:00:120.0
        ip-addr:  127.0.0.1
        geo-pos:  43.6x116.7x817
        hex:      16#{DECAFBAD CAFE 00FF}
        base-64:  64#{UmVuIGlzIGRhdGE=}  
    ]

For more information, see http://www.ren-data.org
