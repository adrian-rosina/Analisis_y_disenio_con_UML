# 📚 Sistema de Gestión de Biblioteca – Análisis y Diseño UML


### 1️⃣ Diagrama de casos de uso
![Diagrama de casos de uso](Diagrama%20de%20casos%20de%20uso%20(PlantUML).png)

Representa las acciones que pueden realizar los distintos usuarios del sistema:  
- Los **socios** pueden consultar el catálogo, realizar reservas y ver su historial.  
- Los **bibliotecarios** gestionan usuarios, préstamos y el catálogo.  
- El **administrador** supervisa el sistema y genera informes.

**Casos de uso principales:**
- Consultar catálogo  
- Realizar reserva  
- Gestionar usuarios  
- Gestionar catálogo  
- Gestionar préstamos  
- Generar informes  
- Consultar historial de préstamos  

---

### 2️⃣ Diagrama de clases
![Diagrama de clases](Diagrama%20de%20clases%20(PlantUML).png)

Muestra la estructura interna del sistema, con las clases principales y sus relaciones.  
Entre las más importantes se encuentran:

- **Usuario**, clase base de la que heredan **Socio**, **Bibliotecario** y **Administrador**.  
- **Libro** y **Ejemplar**, donde cada libro puede tener varios ejemplares físicos.  
- **Autor** y **Autoría**, que representan la relación muchos a muchos entre libros y autores.  
- **Préstamo**, **Reserva** y **Penalización**, que reflejan las acciones que se realizan sobre los ejemplares.  
- **Incidencia**, usada para registrar pérdidas o daños.
