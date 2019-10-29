# Análisis de dataset robo y hurtos de autos 

link https://datos.gob.ar/dataset/justicia-robos-recuperos-autos

### ÚLTIMO COMMIT
	- Todos los datasets para laburar ya están en la carpeta de curados. Hay diferentes notebooks que describo en el inciso (notebook) (agus)
	- Ya mergee todos los dfs mensuales en uno solo, desdoblé los recuperados y guardé todo como csvs separados. Ahora laburar directamente esos en otro notebook (*EDA*) (agus)


## Datasets para cruzar
	- Patentamientos por modelo
	- Patentamientos por año
	- Parque automotor


## TODO
- [x] Conseguir o averiguar si existe dataset patentes
- [x] Concatenar todos los files
- [x] Desdoblar dataset recuperos
	- aquellos que fueron recuperados agregar columna con tiempo de recuperación
- [x] Curar datasets para averiguar si tenemos robados y recuperados en este periodo
- [ ] EDA (IN PROGRESS)
	- Conteos, distribuciones et al
		- Hecho: Año, mes, día de la semana
		- To do: año de patentamiento
	- Mapas (falta relativizar el n de robos a algo)
		- provincia abs, provincia/patentados 
		- (opc: /pobl, robados que se patentaron en 18/19)
	- robos por año de patentamiento?
- [ ] RegEx de tipo (agus) , marca y modelo de auto (buscar x modelos más vendidos)
- [ ] Clasificador para predecir recuperados
	- Mejorar el tema del desbalanceo en el train test split
	- Feature selection?
	- ver qué modelo / probar modelos.
- [ ] Regresor para predecir tiempo hasta recuperado
	- Hacer stratify en traintest split
- [ ] Conseguir dataset parque automotor por marca

## NOTEBOOKS
	- EDA
	- SETUP Y LIMPIEZA DEL DS
	- CLASIFICADOR
	- REGRESOR
	
