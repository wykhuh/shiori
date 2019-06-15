# Shiori

This is a fork of [Shiori](https://github.com/RadhiFadlillah/shiori)

## Run

1. install repos

```bash
go get github.com/RadhiFadlillah/shiori

go get github.com/shurcooL/vfsgen

go get github.com/wykhuh/shiori
```

2. start server

```bash
 ~/go/bin/shiori serve -p 8888
```
## Update View

1. change view files
2. rebuild assests

```bash
go generate
```
3. commit and push changes
4. rebuild binary via remote

```bash
go get github.com/wykhuh/shiori
```

## License

Shiori is distributed using [MIT license](https://choosealicense.com/licenses/mit/), which means you can use and modify it however you want. However, if you make an enhancement for it, if possible, please send a pull request.
