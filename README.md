# FreeBSD Google Indexing API

## Getting Started
https://www.unixwinbsd.site/2023/11/blogger-indexing-api-with-npm-node.html

### Build from Source

root@ns7:/usr/local/etc/FreeBSD_Google_Indexing_API # go mod init github.com/unixwinbsd/FreeBSD_Google_Indexing_API


root@ns7:/usr/local/etc/FreeBSD_Google_Indexing_API # go mod tidy

root@ns7:/usr/local/etc/FreeBSD_Google_Indexing_API # go get github.com/unixwinbsd/FreeBSD_Google_Indexing_API

root@ns7:/usr/local/etc/FreeBSD_Google_Indexing_API # go get google.golang.org/api/indexing/v3

root@ns7:/usr/local/etc/FreeBSD_Google_Indexing_API # go get google.golang.org/api/option

The final step, we create a binary file to execute the application.

root@ns7:/usr/local/etc/FreeBSD_Google_Indexing_API # go build -o index FreeBSD_Indexing_API.go

### Usage

Run the "Google Indexing API" application with the "index" command.

root@ns7:/usr/local/etc/FreeBSD_Google_Indexing_API # ./index

## License

Distributed under the MIT License. See [LICENSE](./LICENSE) for more information.

## Acknowledgements

- Full Article
  - https://www.unixwinbsd.site
