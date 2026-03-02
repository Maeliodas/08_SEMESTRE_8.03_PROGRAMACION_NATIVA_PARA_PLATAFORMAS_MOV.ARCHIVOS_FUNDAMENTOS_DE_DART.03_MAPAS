Contenido del codigo del tercer archivo, el cual son los mapas en dart, este es el codigo, en donde usamos a los pokemones asignandoles habilidades y creamos un mapa dentro de otro mapa
esto nos sirve para almacenar información bajo etiquetas
```dart
void main() {
  final Map<String, dynamic>pokemon = {
    'name': 'Ditto',
    'HP':100,
    'isAlive':true,
    'abilities':<String>['impostor'],
    'sprites': <int, String>{
      1:'Ditto/front.png',
      2:'Ditto/back.png'
    } //Mapa dentro de un mapa
  }; //Los mapas se contruyen con {} o el contenido deb ser pares llaves valor, es decir, identificador con valor del mismo
  
  print(pokemon);
}
