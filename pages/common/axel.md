# axel

> Download accelerator
> Supports HTTP, HTTPS, and FTP

- Download a URL to a file

`axel {{url}}`

- Download and specify filename

`axel {{url}} -o {{filename}}`

- Download with multiple connections

`axel -n {{connections_num}} {{url}}`

- Search for mirrors (can specify numbers)

`axel -S {{mirrors_num}} {{url}}`

- Limit download speed (bytes per second)

`axel -s {{speed}} {{url}}`