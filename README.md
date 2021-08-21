# re-r-tribble
//CLASE

/**
* Esta Excepcion sirve para indicar si hay un coctel con el mismo nombre 
*/

public class coctelRepetidoException  Extends  Exception

{


//------------------
//ATRIBUTOS
//------------------

/**
* Nombre del coctel repetido  
*/

private String nombreCoctelRepetido ();

//------------------
//CONSTRUCTOR
//------------------

/**
* Esta excepción se crea indicando una causa del error y además el nombre del coctel repetido 
*@param causa- este parámetro se invoca el constructor de la clase Exception
*@param nombreCocteles- en este parametro Se guarda la cadena de caracateres 
*/

public coctelRepetidoException (String causa, String nombrecoctel)
{
  super( causa );
  nombreCoctelRepetido = nombrecoctel;

}

/**
* Nos retorna el nombre del coctel repetido 
*@return Nombre del cotel repetido
*/

 public String darNombreCoctelRepetido( )
 {
        return nombreCoctelRepetido ;
  }


}






