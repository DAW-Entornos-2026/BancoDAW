# BancoDAW
Software en PSeInt para los cajeros automáticos inteligentes de BancoDAW. Incluye acceso por PIN, retirada e ingreso de efectivo con detección de fraude, simulación de préstamos, cambio de divisas y arqueo final del dispensador. Desarrollado con metodología Scrumban en GitHub Projects.

**Código base**

```
Algoritmo BancoDAW_Master
	
	// =========================================================================
	// DECLARACIÓN E INICIALIZACIÓN DE VARIABLES GLOBALES
	// =========================================================================
	Definir operacionesRealizadas, opcionMenu Como Entero
	Definir saldoCuenta, ingresosTotales, retirosTotales, comisionesCobradas Como Real
	Definir cuentaBloqueada Como Logico
	
	// Valores iniciales según plantilla maestra
	saldoCuenta <- 1000.0
	ingresosTotales <- 0.0
	retirosTotales <- 0.0
	comisionesCobradas <- 0.0
	operacionesRealizadas <- 0
	cuentaBloqueada <- Falso
	
	// =========================================================================
	// BUCLE PRINCIPAL DE NAVEGACIÓN Y MENÚ
	// =========================================================================
	Repetir
		Escribir ""
		Escribir "=================================================="
		Escribir "     SISTEMA DE GESTIÓN CENTRALIZADA BancoDAW     "
		Escribir "=================================================="
		Escribir "1. Autenticación PIN y Control de Acceso"
		Escribir "2. Depósitos en Efectivo y Bonificaciones"
		Escribir "3. Retiros de Efectivo y Control de Límites"
		Escribir "4. Pago de Servicios, Comisiones e IVA"
		Escribir "5. Cierre de Jornada, Balance e Informe"
		Escribir "0. Salir del programa"
		Escribir "--------------------------------------------------"
		Escribir "Seleccione una opción (0-5):"
		Leer opcionMenu
		Escribir ""
		
		Segun opcionMenu Hacer
			1:
				// TODO: [Issue #2] Implementado por Developer 1
				Escribir "[PENDIENTE] Caso 1 no integrado. Esperando revisión en Code Review."
				
			2:
				// TODO: [Issue #3] Implementado por Developer 2
				Escribir "[PENDIENTE] Caso 2 no integrado. Esperando revisión en Code Review."
				
			3:
				// TODO: [Issue #4] Implementado por Developer 3
				Escribir "[PENDIENTE] Caso 3 no integrado. Esperando revisión en Code Review."
				
			4:
				// TODO: [Issue #5] Implementado por Developer 4
				Escribir "[PENDIENTE] Caso 4 no integrado. Esperando revisión en Code Review."
				
			5:
				// TODO: [Issue #6] Implementado por Developer 5
				Escribir "[PENDIENTE] Caso 5 no integrado. Esperando revisión en Code Review."
				
			0:
				Escribir "Cerrando el sistema BancoDAW... ¡Hasta pronto!"
				
			De Otro Modo:
				Escribir "[ERROR] Opción no válida. Introduzca un número entre 0 y 5."
		FinSegun
		
	Hasta Que opcionMenu = 0

FinAlgoritmo
```
