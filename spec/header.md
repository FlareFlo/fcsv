Headers consist of multiple attributes.  
Each header attribute is seperated by `;`, each header is seperated by opening and closing `<>`.  
Each header has a `name`, `type` and optionally padding length.  
Padding is declared by the `p` parameter, optionally fixed to a length of ASCII chars using `p=30` padding to 30 chars.

Example header:  
`<name;string><age;u8><born;u64;p>`

### String options

A type of`string`signifies it's enclosing character as either a default pair of`"`.  
The type of char can be optionally declared`<name;string=1>`, where 0 means `"` and 1 means `'`.