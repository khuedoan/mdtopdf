# Markdown to PDF

Simple and easy to use Markdown to PDF converter

## Getting Started

### Prerequisites

- `wkhtmltopdf`

### Installation

Download the binary and copy to `$PATH`, for example:

```sh
$ curl -OL https://github.com/khuedoan/md2pdf/releases/download/v1.0/md2pdf
$ chmod +x md2pdf
$ sudo mv md2pdf /usr/local/bin/
```

### Usage

```sh
$ md2pdf input.md output.pdf
``````

## Build from source

### Run directly

```sh
go generate
go run . input.md output.pdf
```

### Compile

```sh
go generate
go build
```

## Acknowledgments

- [GitHub Markdown CSS by iamcco](https://github.com/iamcco/markdown-preview.nvim/blob/master/app/_static/markdown.css)
