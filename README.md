# Sistema Kawsay

Prototipo en Python para registrar pacientes, médicos, citas y atenciones de un establecimiento de salud.
Trabajo del curso Lenguajes de Programación (UAIN1288P), UPN.

**Todos los datos son ficticios.** El sistema muestra solo la inicial del nombre del paciente.

## Cómo ejecutarlo

Requiere Python 3. Desde la carpeta del proyecto:

```
python main.py          # menú interactivo
python main.py demo     # recorrido automático
```

En Windows, si `python` no funciona, usar `py main.py`.

## Archivos

| Archivo | Contenido |
|---|---|
| `paciente.py` | Clase `Paciente` (valida la edad entre 0 y 120 y guarda el historial) |
| `medico.py` | Clase `Medico` |
| `cita.py` | Clase `Cita` (valida la fecha DD/MM/AAAA y registra la atención) |
| `main.py` | Funciones, menú y recorrido de demostración |

## Paradigmas

- **Estructurado:** funciones, listas y validaciones en `main.py`.
- **Orientado a objetos:** clases con atributos protegidos, getters y setters.
- **Funcional:** `filter()` con `lambda` para buscar médicos por especialidad.
