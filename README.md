# Recoleccion-Basura
API para el servicio de Limpia Pública del Municipio de Xalapa, Veracruz.
---

Accesos para el API de camiones de basura en el municipio de Xalapa
	
	// --------------------------------------------------------------------------------------------------------------------------
	
	Obtener los grupos de vehículos
	GET Base URL/api/v1/gruposVehiculo
	
	Ejemplo de petición: recoleccionbasura.xalapa.gob.mx/api/v1/gruposVehiculo
	
	// --------------------------------------------------------------------------------------------------------------------------

	// --------------------------------------------------------------------------------------------------------------------------
	
	Obtener la última ubicación conocida de un grupo de vehículos
	GET Base URL/api/v1/gruposVehiculo/{gruposVehiculoId}/ultimasPosicionesVehiculos
	
	Donde: 
	{gruposVehiculoId} Representa el campo Id de un grupo de vehículos.
	
	Ejemplo de petición: recoleccionbasura.xalapa.gob.mx/api/v1/gruposVehiculo/1bca1382-b20f-442b-8c68-be29d51ff0f7/ultimasPosicionesVehiculos
	
	// --------------------------------------------------------------------------------------------------------------------------

---
