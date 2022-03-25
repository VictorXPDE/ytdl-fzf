# ytdl-fzf 
Um script simples para baixar vídeos do YouTube, Twitter, Reddit e outros sites com um Fuzzy Finder.

[[English version]][english readme]

[english readme]: https://github.com/VictorXPDE/ytdl-fzf/blob/master/README-English.md

#### Dependências:

* [yt-dlp](https://github.com/yt-dlp/yt-dlp)
* [fzf](https://github.com/junegunn/fzf)

#### Instalação:
Clone o repósitorio do projeto e dê permissões de execução para o script.
```
$ git clone https://github.com/VictorXPDE/ytdl-fzf
$ cd ytdl-fzf
$ chmod +x ytdl-fzf
```
Agora mova o script para `/usr/local/bin` ou qualquer outro diretório do seu `$PATH`
```
$ sudo mv ytdl-fzf /usr/local/bin
```

#### Uso:
```
ytdl-fzf <formato> <url>
```
Onde `<formato>` seria:

* `a` para áudio.
* `v` para vídeo.
* `a+v` ou `v+a` para áudio e vídeo junto.

Exemplo:
```
$ ytdl-fzf a+v https://www.youtube.com/watch?v=Wb3UrJjAac4
```
