# ejercicios-3
EJEMPLO (1)

def bolita blanca ()
var compratotal=0
var cantidadfinal=0
println ("Ingresa la compra total")
var compratotal=readfloat()
cantidadfinal=compratotal
println ("vas a pagar"+cantidadfinal)

def bolita verde ()
var compratotal=0
var cantidadfinal=0
println ("Ingresa la compra total")
var compratotal=readfloat()
cantidadfinal=compratotal*10/100
println ("vas a pagar"+cantidadfinal)

def bolita amarilla ()
var compratotal=0
var cantidadfinal=0
println ("Ingresa la compra total")
var compratotal=readfloat()
cantidadfinal=compratotal*25/100
println ("vas a pagar"+cantidadfinal)

def bolita azul ()
var compratotal=0
var cantidadfinal=0
println ("Ingresa la compra total")
var compratotal=readfloat()
cantidadfinal=compratotal/2
println ("vas a pagar"+cantidadfinal)

def bolita roja()
var compratotal=0
var cantidadfinal=0
println ("Ingresa la compra total")
var compratotal=readfloat()
cantidadfinal=compratotal/compratotal
println ("vas a pagar"+cantidadfinal)

println ("¿cual color te salio?)
println ("1)bolita blanca")
println ("2)bolita verde")
println ("3)bolita amarilla")
println ("4)bolita azul")
println ("5)bolita roja")
val opcion=readfloat()
opcion match
{
case 1=> bolita blanca ()
case 2=> bolita verde ()
case 3=> bolita amarilla ()
case 4=> bolita azul ()
case 5=> bolita roja ()
case default=> println ("opcion invalida")

EJEMPLO (2)

var edad=0
val jubilacionedad=0
val antiguedadjoven=0
val antiguedadadulta=0
println ("Ingresa tu edad")
edad=readInt()
println ("Ingresa tus años de empleo")
añosempleo=readInt()



