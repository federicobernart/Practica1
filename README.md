# Practica1
Practica 1 Para primera semana en Iquall Networks
Practica 1:
Instalar las siguientes aplicaciones utilizando ansible
Influx v1.8 (docker)
Desplegar influx en un contenedor de Docker utilizando Ansible para su despliegue. Una vez realizado, almacenar las métricas de recursos en influx.
Telegraf (sin docker): 
Instalar telegraf como servicio utilizando Ansible, configurarlo para que extraiga datos de disco,mem,cpu (investigar qué otras cosas de interés pueden ser monitoreables del localhost) y los guarde en influx
Kapacitor ( docker):
Desplegar kapacitor en un contenedor de Docker utilizando Ansible para su despliegue. 
Configurar alarmas e insertar en una DB o measurement de influx si se triggereo o no la alarma y que pueda ser graficado el resultado en un dashboard de grafana.
Chronograf (docker):
Desplegar chronograf en un contenedor de Docker utilizando Ansible para su despliegue
Grafana (docker): 
Desplegar la aplicación de grafana en un contenedor de Docker utilizando Ansible. 
Configurar y armar un  dashboard que permita visualizar los parámetros extraídos

Para que investigues durante la práctica: si tuvieras que guardar estas métricas durante 1 año, qué herramientas brinda influx para ello? 
TIPS: Retention policies y granularidad de los puntos insertados.

