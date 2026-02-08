# 📌 TÍTULO DEL TEMA

> Apuntes personales — última actualización: YYYY-MM-DD

---

📌 Regla de oro:

1 solo # por archivo

El resto con ## y ###

## 🧠 Idea principal
Explica aquí, en **tus propias palabras**, de qué trata el tema.
Si lo puedes explicar simple, lo entiendes.

---

## 🧩 Conceptos clave
- Concepto 1: explicación corta
- Concepto 2: explicación corta
- Concepto 3: explicación corta

---

## ⚙️ Sintaxis / Comandos / Estructura
### 🔹 Bloque Bash
```bash
comando --opcion
ls -la
```

### 🔹 Bloque Python
```python
print("Hola")
```

!!! note "Nota Estática"
    Este bloque siempre es visible. Ideal para apuntes rápidos sobre "Cinema, mon amour".

??? abstract "Resumen de Película (Haz clic para abrir)"
    Aquí puedes poner la sinopsis de "Everything Everywhere All at Once" para no ocupar tanto espacio en la página.

!!! info "Certificación CompTIA A+"
    Información técnica importante sobre los módulos de estudio de hardware y redes.

???+ tip "Consejo para Inglés (Abierto por defecto)"
    Intenta ver las películas sin subtítulos para entrenar el oído; puedes cerrarlo si ya lo leíste.

!!! success "Progreso de Entrenamiento"
    ¡Rutina de anillas completada! Recuerda registrar las repeticiones de hoy.

??? question "Análisis Filosófico"
    ¿Qué representa el bagel en la película? Este bloque está cerrado para evitar spoilers.

!!! warning "Aviso de Edición"
    Cuidado con los niveles de audio en el video de YouTube para evitar saturación.

!!! failure "Error de Renderizado"
    Si el archivo no se exporta, verifica que el códec sea compatible con tu editor.

!!! danger "Seguridad en Anillas"
    No intentes ejercicios avanzados sin un calentamiento previo de articulaciones.

??? bug "Problema de Formato"
    Si los bloques no se ven, revisa la sangría de 4 espacios en tu archivo `.md`.

!!! example "Discrete Mathematics"
    Un ejemplo de lógica: si $P \rightarrow Q$ y $P$ es verdadero, entonces $Q$ es verdadero.

!!! quote "Cita Inspiradora"
    "The camera is an instrument that teaches people how to see without a camera." — Dorothea Lange

## Ejemplos de Matemáticas (LaTeX)
!!! example "Matemáticas Discretas"
    * **Lógica Proposicional:** La implicación se define como $P \rightarrow Q$.
    * **Teoría de Conjuntos:** La unión de dos conjuntos se expresa como:
        $$A \cup B = \{x \mid x \in A \lor x \in B\}$$
    * **Sumatorias:** $$\sum_{i=0}^{n} i = \frac{n(n+1)}{2}$$

## Ejemplos de Lenguajes de Programación
!!! example "Python: Automatización para 'Cinema, mon amour'"
    ```python
    # Script para organizar clips de video por fecha de creación
    import os
    import time

    def organize_cinema_clips(path):
        files = os.listdir(path)
        for file in files:
            creation_time = os.path.getctime(os.path.join(path, file))
            print(f"Clip: {file} | Fecha: {time.ctime(creation_time)}")

    organize_cinema_clips("./videos/raw_footage")
    ```

!!! info "Bash: Comandos de Red (CompTIA A+)"
    ```bash
    # Verificar la configuración de la interfaz de red
    ip addr show
    
    # Comprobar la conectividad con los servidores de Google
    ping -c 4 google.com
    
    # Ver la tabla de enrutamiento
    netstat -rn
    ```

!!! question "C++: Lógica de Matemáticas Discretas"
    ```cpp
    #include <iostream>
    #include <cmath>

    // Calcular el tamaño del conjunto potencia P(A) -> 2^n
    int main() {
        int n;
        std::cout << "Introduce el numero de elementos del conjunto A: ";
        std::cin >> n;
        std::cout << "La cardinalidad de P(A) es: " << pow(2, n) << std::endl;
        return 0;
    }
    ```

!!! abstract "SQL: Base de Datos de Películas"
    ```sql
    -- Consulta para encontrar análisis pendientes por género
    SELECT title, release_year, director
    FROM youtube_backlog
    WHERE analysis_status = 'pending'
    AND genre = 'Psychological Drama'
    ORDER BY priority DESC;
    ```

!!! tip "JavaScript: Configuración de MathJax"
    ```javascript
    window.MathJax = {
      tex: {
        inlineMath: [["\\(", "\\)"]],
        displayMath: [["\\[", "\\]"]],
        processEscapes: true,
        processEnvironments: true
      },
      options: {
        ignoreHtmlClass: ".*|",
        processHtmlClass: "arithmatex"
      }
    };
    ```


# 📚 Repaso General

!!! info "Lógica y Estructuras: Definiciones"
    La implicación lógica entre dos proposiciones $P$ y $Q$ se denota como $P \rightarrow Q$.
    
    En Teoría de Conjuntos, la unión se define formalmente como:
    $$A \cup B = \{x \mid x \in A \lor x \in B\}$$



???+ success "Linux CLI: Comandos Esenciales"
    Este bloque aparece abierto por defecto. Úsalo para comandos de red rápidos:
    ```bash
    # Ver direcciones IP configuradas
    ip addr show
    
    # Comprobar conectividad
    ping -c 4 8.8.8.8
    ```

??? tip "CompTIA: Verificación de Hardware"
    Si necesitas listar los dispositivos PCI en un sistema Linux:
    ```bash
    lspci -v
    ```

!!! example "Programación: Python y C++"
    **Python (Automatización):**
    ```python
    def check_system(status):
        if status == "OK":
            print("Sistema operativo listo.")
    ```
    
    **C++ (Lógica Matemática):**
    ```cpp
    #include <iostream>
    int main() {
        std::cout << "La cardinalidad de un conjunto potencia es 2^n" << std::endl;
        return 0;
    }
    ```

??? question "Fórmulas de Sumatorias (Math)"
    ¿Cuál es el resultado de la suma de los primeros $n$ números?
    $\sum_{i=1}^{n} i = \frac{n(n+1)}{2}$


# 📊 Tablas de Referencia

### Proyectos y Estudios Actuales
| Proyecto | Área | Estado |
| :--- | :--- | :---: |
| Cinema, mon amour | Análisis cinematográfico | YouTube |
| CompTIA A+ | Hardware y Redes | Certificación |
| Matemáticas Discretas | Lógica y Estructuras | UVEG |

---

### Rutina de Entrenamiento (Anillas)
| Ejercicio | Enfoque | Notas de Progreso |
| :--- | :--- | :--- |
| Dominadas en anillas | Fuerza (Tirón) | Foco en resistencia |
| Fondos (Dips) | Fuerza (Empuje) | Estabilidad de hombros |
| Remo invertido | Resistencia | Movimiento progresivo |

---

### Vocabulario de Inglés (Aprendizaje)
| Word / Phrase | Translation | Usage |
| :--- | :--- | :--- |
| *Insight* | Perspicacia / Percepción | "Deep insight into film theory" |
| *Standard* | Estándar / Norma | "Following CompTIA standards" |
| *Core* | Núcleo / Base | "Core strength for ring exercises" |

---

### Tabla con Fórmulas Matemáticas
| Concepto | Representación LaTeX | Definición |
| :--- | :---: | :--- |
| Conjunto Potencia | $$|P(A)| = 2^{|A|}$$ | Cardinalidad de subconjuntos |
| Unión | $A \cup B$ | Elementos en A o en B |
| Implicación | $P \rightarrow Q$ | Lógica proposicional |