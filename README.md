# Contenerización y Despliegue de una aplicación web usando las tecnologías CoreOS, Docker y Amazon Web Services

## Memoria del TFT
Utilizas la gema [softcover](https://github.com/softcover/softcover), que a su vez utiliza un sublenguaje de Latex.

El fichero Gemfile contiene las dependecias, la versión de ruby está especificada a la 3.0.0, también utiliza un gemset lo cual implica instalar [rvm](https://rvm.io/).

Primero, la gema [bundler](http://bundler.io/) usa el fichero Gemfile

```
$ gem install bundle
```
Luego softcover

```
$ bundle install
```

### La gema softcover

Picha [aquí](http://manual.softcover.io/book) para el manual

Antes de continuar, comprobar la instalación

```
$ softcover check
```

Para crear el pdf
```
$ cd doc_tfm
$ softcover build:pdf
```
