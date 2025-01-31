# Customize Your Smoothie App
**Badge 3: Data Application Builders Workshop - Snowflake**

Este proyecto forma parte del **Badge 3: Data Application Builders Workshop** de Snowflake. A través de este curso, se aprende a crear aplicaciones de datos interactivas utilizando herramientas como **Streamlit** y Snowflake. Este repositorio contiene el código para una aplicación interactiva de personalización de batidos, que utiliza datos almacenados en Snowflake y consulta información nutricional a través de una API externa.

## Objetivo

El propósito de este proyecto es demostrar cómo se puede integrar **Streamlit** con **Snowflake** para crear aplicaciones interactivas. Los usuarios pueden personalizar su batido seleccionando frutas y obtener información nutricional a través de una API.

## Características

- **Selección de Frutas:** Los usuarios pueden elegir hasta 5 frutas para crear su batido.
- **Visualización de Datos Nutricionales:** Se obtiene información nutricional de cada fruta seleccionada utilizando una API externa.
- **Conexión con Snowflake:** La aplicación se conecta a Snowflake para obtener los ingredientes disponibles y guardar los pedidos.
- **Interactividad:** Los usuarios pueden personalizar su batido y hacer un pedido directamente desde la interfaz.

## Requisitos

Antes de ejecutar el proyecto, asegúrate de tener instalados los siguientes paquetes:

- `streamlit` - para la interfaz web interactiva.
- `snowflake-snowpark-python` - para interactuar con la base de datos Snowflake.
- `requests` - para realizar solicitudes HTTP y obtener la información nutricional de las frutas.
