# blog-de-laura

# En el stage 0
Creamos un requirements.txt con

<img width="506" height="77" alt="image" src="https://github.com/user-attachments/assets/6d7a0071-a8ab-4c39-a8f3-8a43da7ed0ff" />

Creamos el compose

<img width="755" height="175" alt="image" src="https://github.com/user-attachments/assets/244e266e-2bc8-46e1-8b34-8473801fe432" />

Y el dockerfile en cuestión

<img width="494" height="142" alt="image" src="https://github.com/user-attachments/assets/f3add18c-d34e-42ef-950a-7e4e96b45432" />

# En el stage 1 se han modificado lo siguiente

Editamos el urls.py para quitar django browser

<img width="1485" height="202" alt="image" src="https://github.com/user-attachments/assets/32e70eaa-197d-437f-9169-c65e193421f1" />


En settings.py cambiamos

<img width="667" height="201" alt="image" src="https://github.com/user-attachments/assets/222cf0ba-07e5-4789-a7ac-d89fb0d94d41" />
<img width="833" height="198" alt="image" src="https://github.com/user-attachments/assets/ec84b2f1-b7bc-432e-920c-e020a84c3858" />

En requeriments.txt quitamos django browser

<img width="403" height="111" alt="image" src="https://github.com/user-attachments/assets/d97cfe49-256e-48b1-9329-362d1a00dcba" />

En wsgi.py puede darse que esté instalado django browser, si es así se elimina

<img width="857" height="431" alt="image" src="https://github.com/user-attachments/assets/a98bfa04-3463-44e3-821d-89825a922742" />


# En el stage 2 han sido cambiadas ciertas partes del código:

Esto es lo cambiado del compose:

<img width="727" height="722" alt="image" src="https://github.com/user-attachments/assets/ff226235-a2b2-401a-83af-342a94d578ee" />

Esto lo cambiado del dockerfile:

<img width="614" height="97" alt="image" src="https://github.com/user-attachments/assets/22bea1a5-847d-4693-b67d-3423d7796ef2" />

Agregado nuevos archivos:

<img width="254" height="66" alt="image" src="https://github.com/user-attachments/assets/edce7603-e4ff-4f41-9d04-0356b6ced263" />

Modificado el settings.py del proyecto:

<img width="454" height="147" alt="image" src="https://github.com/user-attachments/assets/5ebec4d4-ceee-4198-b480-a9b616292a41" />

Y añadido una línea en el requirements.txt

<img width="480" height="122" alt="image" src="https://github.com/user-attachments/assets/777712fa-36df-4e05-8847-52a9838c8373" />

