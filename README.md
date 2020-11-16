# PDS---Baseline

Esse repositório contém código para uma interface gráfica para um equalizador de som em tempo real.

Você deve alterar o código no arquivo widgets/filter.py, que é onde você deve definir os filtros. Você também deve alterar o código em screens/bar_screen.py, que é onde a classe Filter, definida em widgets/filter.py, é instanciada.

Os filtros que estão implementados são apenas para que a aplicação funcione (eles fazem uma filtragem com 'ifs' no domínio da frequência) e você deve projetar o seu e implementá-lo no código.

O arquivo requirements.txt contém as bibliotecas usadas, mas provavelmente você terá que instalar algumas na mão (ex: Kivy, Pyaudio).

Para executar o código, basta rodar em seu terminal o comando ```python main.py``` que uma interface gráfica abrirá. Depois basta clicar em "pronto" e então clicar no símbolo de "play". Com isso a música vai começar a tocar.
