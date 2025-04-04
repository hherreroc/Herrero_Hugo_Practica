# Práctica de Programación Orientada a Objetos – Curso 2024-2025

### Author: Hugo Herrero Cercadillo

### email: <hugo.herrero.hcg@gmail.com>

### tel: 646692566

### github: @hherreroc

---

## Análisis

Para el análisis de esta práctica comencé realizando este documento a modo de memoria para ir documentando todo el trabajo de inicio a fin de manera ordenada y constante.

Tras observar y pensar como realizar la práctica y su entrega me he decantado por usar **Markdown** como lenguaje de documentación ya que es el más cómodo para documentar código y el que he estado usando hasta la fecha. Por otro lado y para el control de versiones he decidido usar **GitHub** ya que me resulta muy cómodo y además para trabajar sobre el mismo código en diferentes sitios es muy útil. Crearé un repositorio en mi Github en el que cada vez que haya hecho avances significativos sobre el código y/o el diseño subiré los cambios.

Para el diseño de la práctica usaré **UML** para el diagrama de clases y si puedo para el de paquetes y el de componentes. He elegido este porque junto con Markdown hacen muy buena pareja para la documentación de proyectos y queda bastante estético a mi parecer.

+ Herramientas:
  + **Markdown**
  + **GitHub**
  + **UML**


---

Pasando al análisis de la práctica comencé realizando una lectura rápida de la misma, para ubicarme sobre el tema a tratar y familiarizarme con la solución que se quiere conseguir.

Una vez hecha esta lectura realicé una segunda lectura un poco más detallada subrayando las frases o palabras que me parecen más relevantes o que pueden dar lugar a clases, métodos o cualquier información de utilidad.

Por último se hizo una tercera lectura mucho más profunda y pausada en la que analicé poco a poco los requisitos de la aplicación subrayando de otro color las palabras claves del enunciado, esto me ayudará más adelante cuando quiera buscar las propiedades de algún requisito poder ubicarlo fácilmente y de manera visual.

## Diseño

```mermaid
classDiagram
    class Persona {
        + String nombre
        - metodoEjemplo()
    }
    class Usuario {
        +String raza
        - ladrar()
    }
    Persona <|-- Usuario

