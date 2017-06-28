# Snippets

## HTTPS redirection

Do

`$_SERVER['HTTP_X_FORWARDED_FOR']`

`$_SERVER['HTTP_X_FORWARDED_PROTO']`

Don't 

`$_SERVER['REMOTE_ADDR']`

`$_SERVER['HTTPS']`
