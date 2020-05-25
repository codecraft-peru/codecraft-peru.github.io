# Software Crafters Perú

Link del blog: https://codecraft-peru.github.io/

## ¿Qué necesito para publicar un post?

>Clonar el repositorio
```
$ git clone https://github.com/codecraft-peru/codecraft-peru.github.io.git
```

>Instalar las dependencias requeridas por [jekyll](https://jekyllrb.com/)
```
$ bundle install
```

>Escribir un post usando como base (en nombre de archivo, estructura y contenido) los archivos de la carpeta **_posts**

```
$ ls _posts/
2020-05-21-hello-world.html
2020-05-24-the-beauty-of-craftsmanship.html
```

>Para ver el blog en modo local
```
$ bundle exec jekyll serve
```

>Para publicar el post en el blog  
```
$ git commit -m 'Add post about...'
$ git push
```