# Dart.__GB__
get starget
# DART

`javascrip
main(){ //?function main
  var nombre; //? variable declarada
  print(nombre); //? esto va a dar null en la consola
  if(nombre is String) print ('nombre es string')
    else print('nombre es de otro tipo')
  nombre = 'miguel' //? variable asignada a 'miguel'
  print(nombre) //? 'miguel'
  
  conocerTipo(dynamic variable){
    if (variable is String) print('nombre es string')
      else print('nombre es de otro tipo')
  }
  
var _nombre; //? "el guion bajo adelante del nombre de la variable significa que la variable es
                  privada solo es visible en el espacio que la usamos"
                  
final pi = '3.1416' //? el valor final de esta variable es el declarado no dependen de alguna otra variable
const radio = algo *2 ; //? si puede depender de otro resultado pero no puede usar una variable final como argumento

//int
var x = 1;
int x = int.parse('1') //? String --> int
String x = uno.toString()

// double
var y = 1.1;
double real = 1;//? 1.0'
double real = double.parse('1.1') //? String --> double
String real = real.toString()
String ydecimales = y.toStringAsFixed(1) //? devuelve el numero con la ccantidad de decimales especificados

}`

## propiedades de los numeros
`
var num = -1;
print(num.abs()) //? inprime el valor absoluto 1'
         .ceil() //? obtiene el umero entero superior al actual 2'
         .floor() //? redondeo a la baja
         


`
## string
`dart
main(){
var string = 'hola';
var string = "hola";
var string = ' yo dije: \'hola\''; //? esto me deja poner comillas dentro de comillas

var string = 'hola' 'hola' //? esto conccatena las string
var string1 = 'chau';
print(string+string1) //? concatena las string
var num = 15;
string frase = 'mi edad es ${num+string1}'//? te trae la variable y puedes poner evaluaciones de expreciones
}

`

## booleans
`
main(){
bool existe = true;
if (existe)
  print('existe es  ${existe}')
  else
  print('existe es  ${existe}')
    
}
`
