# Que es?
Este repo contiene el script de configuracion del modelo

# Como usar?
- Abrir el script `config.py`
- Modificar el parametro que se quiere cambiar
- Guardar cambios

## Parámetros
temperature: define que tanto puede divagar el modelo y que tan poco determinista son sus respuestas , por regla de negocio se ajusta a 0.2 para que tenga una libertad baja de creatividad. El rango valido del parametro es [0-1]
max_tokens: controla la cantidad de tokens maximos que se le mandan al modelo, por regla de negocio se coloca como 2048
