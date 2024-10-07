

# Estructura de Clasificación de Mensajes

## 1. Mensajes Importantes `{}`

- **Descripción**: Mensajes críticos que requieren atención inmediata. Pueden indicar errores o eventos significativos.
- **Símbolos**:
  - `!`: Indica un error o una advertencia.
  - `*`: Indica una acción que debe tomarse.
- **Ejemplo**: 

  { ! Error al conectar a la base de datos }
  { * Actualización exitosa }
  

## 2. Mensajes Moderados `[]`

- **Descripción**: Mensajes que son útiles, pero no críticos. Incluyen información general y actualizaciones.
- **Símbolos**:
  - `+`: Indica información adicional o progreso.
  - `-`: Indica una reducción o un cambio negativo.
- **Ejemplo**:
  
  [ + Nueva característica añadida ]
  [ - Reducción del límite de uso ]
  

## 3. Avisos `()`

- **Descripción**: Mensajes que son meramente informativos o recordatorios. Pueden no requerir acción.
- **Símbolos**:
  - `?`: Indica una pregunta o un recordatorio.
  - `~`: Indica un aviso de cambio próximo o de planificación.
- **Ejemplo**:
  
  ( ? ¿Deseas continuar con la operación? )
  ( ~ Mantenimiento programado para el fin de semana )
  

## Ejemplo de Uso

Aquí tienes un ejemplo de cómo podrías utilizar esta estructura en un programa:

```d
import std.stdio;

void main() {
    writeln("{ ! Error: No se pudo cargar el archivo }");
    writeln("[ + Carga de usuario completada ]");
    writeln("( ~ Revisa los cambios realizados )");
    writeln("{ * Reiniciando el servicio }");
    writeln("[ - Uso de memoria alto ]");
    writeln("( ? ¿Quieres ver más detalles? )");
}
```

## Resumen

Con esta estructura, puedes clasificar tus mensajes de manera clara y concisa. Los símbolos adicionales te permiten transmitir matices en la información que estás compartiendo, mejorando así la legibilidad y comprensión de los mensajes en tu consola. ¡Espero que te sea útil!


