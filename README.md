//Actividad 1 Identificar número Par o Impar
var saludoIni = "Hola Este programa le ayuda a identificar si el número que proporciona es Par o Impar \n"

print(saludoIni)

print("Digite un número a identificar: \n")
var dato = readLine()!
var numeroIni = Int (dato)!

var resultado = numeroIni/2

if resultado == 0 {
  print("\(numeroIni) es un número par")
} else {
    print("\(numeroIni) es un número impar")
  }
