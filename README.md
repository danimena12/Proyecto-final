# Proyecto-final
Proyecto final
var precio_base =2000

var edad_18 = 0.1
var edad_25 = 0.2
var edad_50 = 0.3

var casado = 0.1
var casado = 0.2 
var casado = 0.3 

var hijos_recargo = 0.1

var hijos_recargo = 0.2
var hijos_recargo = 0.3 

var recargo = 0
var recargo_total = 0


var edad_numero = parseIntprompt("Cuantos años tiene?Ingreso solo la edad")
var edad_conyuge_numero =parseInt(edad)

if("SI"== casado.toUpperCase()){
  edad_conyuge_numero = parseInt(edad_conyugue)
}

var hijos =prompt("¿Tiene hijos o hijas")
var cantidad_hijos


if(edad_numero>=18 && edad_numero<25){

    recargo =precio_base *edad_18 
}
    recargo_total= recargo_total + recargo
    
  if (edad_numero>=25 && edad_numero<49){
    recargo =precio_base *edad_25 
    
    recargo_total= recargo_total + recargo
    
    if(edad_numero>=50 && edad_numero<50)
    recargo =precio_base *edad_50

    recargo_total= recargo_total + recargo
}else{ console.log("Edad limite") 
  }

 var precio_base  
