# 🏥 Sistema de Ficha Médica

## Descripción                                         

La aplicación consiste en un sistema web para el ingreso y búsqueda de fichas médicas, desarrollado utilizando **HTML, CSS, JavaScript y LocalStorage**, permitiendo almacenar la información directamente en el navegador sin necesidad de utilizar una base de datos.

---

## Tecnologías utilizadas

- HTML5
- CSS3
- JavaScript
- Bulma CSS
- LocalStorage
- GitHub Pages

---

## Funcionalidades

El sistema permite:

- Registrar pacientes mediante una ficha médica.
- Validar los datos ingresados.
- Guardar la información en LocalStorage.
- Buscar pacientes por apellido.
- Evitar registros duplicados mediante validación por RUT.
- Sobrescribir un registro existente previa confirmación del usuario.

---

## Estructura del proyecto

```
Proyecto/
│
├── index.html
├── Formulario.html
├── buscar.html
├── estilos.css
└── README.md
```

---

## Validaciones implementadas

- RUT obligatorio.
- Nombre y apellido solo permiten letras.
- Ciudad solo permite letras.
- Teléfono de 9 dígitos.
- Correo electrónico válido.
- Estado civil obligatorio.
- Confirmación para sobrescribir registros existentes.

---

## Almacenamiento

La información es almacenada utilizando **LocalStorage**, lo que permite mantener los registros aun cuando se cierre el navegador.

---

Taller de Testing y Calidad de Software

2026
