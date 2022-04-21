# Regex - Regular Expressions

## Meta caracteres

    .    -> qualquer caracter(char)
    *    -> serve para definir uma quantidade de chars
    {qt} -> serve para definir uma quantidade específica
    \d   -> qualquer digito


## Exemplos

    CNPJ: **15.123.321/8883-22**

    Regex: \d{2}\.\d{3}\.\d{3}\/\d{4}\-\d{2}

    IP:  `126.1.112.34` `128.126.12.244 192.168.0.34`

    Regex: \d{1,3}\.\d{1,3}\.\d{1,3}\.\d{1,3}

    CEP: **20040-030**

    Regex: \d{5}\-\d{3}

    Telefone: **(21) 3216-2345**

    Regex: \(\d{2}\) \d{4}-\d{4}
