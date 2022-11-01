Algoritmo sin_titulo
	definir sueldo_final,sueldo,categoria,horas como real
	definir nomina como real
	nomina <- 0
	Escribir "digite su sueldo"
	Repetir
		Escribir "digite su sueldo en numeros positivos"
		Leer sueldo 
	Hasta Que sueldo>0
	Escribir "digite sus horas extras en numeros positivos"
	Repetir
		Escribir "digite sus horas"
		Leer horas
	Hasta Que horas>0
	Escribir "digite su categoria en numeros positivos"
	Repetir
		Escribir "digite su categoria"
		Leer categoria
	Hasta Que categoria>0
	Segun categoria Hacer
		1:
			sueldo_final <- horas*30
		2:
			sueldo_final <- horas*35
		3:
			sueldo_final <- horas*50
		4:
			sueldo_final <- horas*70
		De Otro Modo:
			Escribir "no hay esta categoria"
	FinSegun
	Escribir "su sueldo es",sueldo_final+sueldo
	nomina <- nomina+sueldo_final+sueldo
FinAlgoritmo
