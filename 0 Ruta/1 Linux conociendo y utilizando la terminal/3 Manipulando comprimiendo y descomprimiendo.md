Manipulando, comprimiendo y descomprimiendo archivos
===================================================

![alt text](image-2.png)

## `cp` copiar archivos y directorios

![alt text](image-3.png)

- `cp -R`: copia un directorio y su contenido de forma recursiva


## `mv` mover archivos y directorios, también se puede usar para renombrar archivos y directorios

![alt text](image-4.png)

![alt text](image-5.png)

## Creando y abriendo ZIP

![alt text](image-6.png)

- En oracle Linux, el comando `zip` no está instalado por defecto. Para instalarlo, puedes usar el siguiente comando:

```bash
sudo yum install zip
```

![alt text](image-7.png)

- Para crear un archivo ZIP, puedes usar el siguiente comando:

```bash
zip work.zip ./otros_
```

![alt text](image-8.png)

- Para ver el contenido de un archivo ZIP, puedes usar el siguiente comando:

```bash
unzip -l work.zip
```

![alt text](image-9.png)


- pero como podemos ver no se comprimieron todos los archivos, es necesario ejecutar el comando de manera recursiva, para eso se utiliza el parámetro `-r`:

```bash
zip -r work.zip ./otros_
```

![alt text](image-10.png)

- para descomprimir un archivo ZIP, puedes usar el siguiente comando:

```bash
unzip work.zip

## silecioso
unzip -q work.zip
```

- comprimido silencioso y recursivo:

```bash
unzip -rq work.zip
```



