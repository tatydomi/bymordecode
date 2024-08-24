#### DECIFRANDO CÓDIGO MORSE

Imagine que você é um agente especial que possui a missão de interceptar mensagens secretas. Por meio da sua rede de informantes você descobre que tais mensagens estão sendo transmitidas por meio de uma frequência de rádio não utilizada em código morse.

<img src="./img/missao_morse.png" style="max-width:500px; "/>

Sua missão é:
- Interceptar estas mensagens;
- Decodificar, sabendo que as letras estão espaçadas por um espaço;
- Salvar as mensagens em um arquivo em texto claro;
- Salvar o datetime da decodificação da mensagem;

<img src="./img/morse.png" style="max-width:300px; "/>

Para cumprir sua missão sem levantar suspeitas você deverá realizar a decodificação através de uma ou mais funções que :
- Recebe a mensagem como argumento;
- O "de-para morse" não deve estar hard coded;
- Path do arquivo não deve estar hard coded;
- Messagem deve ser passada através do keyboard.

### Como utilizar:

1. Crie um ambiente virtual
```
python -m venv env
```
2. Ative o ambiente virtual
3. Instale o requirements (se necessário)
```
pip install -r requirements.txt
```
4. Execute o script passando a mensagem em morse
```
python decode_morse.py ''
```

----

