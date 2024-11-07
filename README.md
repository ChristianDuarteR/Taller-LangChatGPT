# LangChatGPT: Implementación del Tutorial LLM Chain con LangChain

En este repositorio **LangChatGPT**! se muestra cómo integrar la arquitectura de **LangChain** para crear una **LLM Chain** (Large Language Model Chain) en un entorno seguro

## 🚀 Descripción del Proyecto

Este proyecto implementa el tutorial [LLM Chain](https://python.langchain.com/docs/tutorials/llm_chain/), 

## 📂 Estructura del Repositorio

```plaintext
langchainbasicapp.ipynb
langchainclient.py
langchainserver.py
└── README.md
```

### Requisitos Previos

Para ejecutar este proyecto, necesitarás tener instalado:

- Python.
- Un IDE de Python de su preferencia.
- Un navegador web para interactuar con el servidor y la API.

### Instalación

1. Tener instalado Git en tu máquina local.
2. Elegir una carpeta en donde guardar el proyecto.
3. Abrir la terminal de GIT (ccho y seleccionar "Git bash here").
4. Clonar el repositorio en tu máquina local:lic dere
   ```bash
   git clone https://github.com/ChristianDuarteR/Taller-LangChatGPT

   
### Deployment

1. Abre el proyecto con tu IDE favorito o navega hasta el directorio del proyecto.
2. Desde la terminal, ejectuta los dos archivos de python
     ```bash
   python langchainserver.py
   python langchaincliente.py
3. El servidor iniciara
   ![image](https://github.com/user-attachments/assets/ddccecf0-e174-4988-9fc5-eecdd4068864)
     
4. Es posible interactuar con la aplicacion en el puerto (http:localhost:8000/chain/playground)
   ![image](https://github.com/user-attachments/assets/393536ed-8f98-40c2-9ad2-07c1094e62df)

   

  
### IMPORTANTE:

Es importante contar con un APIKEY, tanto en el servidor como en la API se deja uan variable vacia en donde deberia estar, sino se proporciona la aplicacion no servira

![image](https://github.com/user-attachments/assets/7081e72a-9570-4e4f-acfb-4ec8ff293408)

## Arquitectura

### Servidor

El Servidor Lang, adapta una implementacion sencilla para que realize una peticion a la API y asi brindar una respuesta al cliente segun la entrada que se proporciono

### Cliente

El cliente sencillamnete realiza una peticion POST de alguna frase y el lenguaje que quiere la traduccion y la envia al cliente

### Api 

Este componente hace un llamada al modelo de OpenIA para usaese, es necesario tener una llave a la API para que funcione de lo contrario el programa no iniciara

### Built with 
- [Python](https://www.python.org)

