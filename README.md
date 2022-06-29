# WTF con javascript ?? 🤔

*WTF con Javascript??* es una guia de distribucion gratuita con la intencion de profundizar en el lenguaje de programacion **Javascript** .

Comentarios bienvenidos, en forma de issues y pull requests.


## Building

Esto genera la salida HTML en `html/`, donde `make` es GNU make:

    npm install
    make html

Para crear el archivo PDF (no se moleste en intentarlo a menos que realmente necesite
ya que esta lista probablemente se ha vuelto a romper y obtener todo esto
configurar es un dolor):

    apt-get install texlive texlive-xetex fonts-inconsolata fonts-symbola texlive-lang-chinese inkscape
    make book.pdf
