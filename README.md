# Taller
  **Integrantes**  
- Valentina Orjuela
- Ana Sofia Llorente
- Sofia Gomez

---

 **Información del curso**  
- **Curso:** Pensamiento algorítmico – Universidad Sergio Arboleda  
- **Fecha de entrega:** 01/09/2025


 **Guías de compilación**  

 Requisitos
- Compilador C++ compatible con C++17 o superior (`g++`, `clang`, o Visual Studio).
- Sistema operativo: Windows, Linux o macOS.
- Crear carpeta `bin/` (si no existe) para guardar ejecutables.

---

 Compilación en Linux / macOS
```bash
g++ -std=c++17 src/calculadora.cpp -o bin/calculadora
g++ -std=c++17 src/validacion_fecha.cpp -o bin/validacion_fecha
g++ -std=c++17 src/sistema_descuentos.cpp -o bin/sistema_descuentos
g++ -std=c++17 src/cajero_automatico.cpp -o bin/cajero_automatico
g++ -std=c++17 src/horoscopo.cpp -o bin/horoscopo
g++ -std=c++17 src/validacion_hora.cpp -o bin/validacion_hora
````

Ejecutar un programa:

```bash
./bin/calculadora
```

---

Compilación en Windows (MinGW)

```cmd
g++ -std=c++17 src\calculadora.cpp -o bin\calculadora.exe
g++ -std=c++17 src\validacion_fecha.cpp -o bin\validacion_fecha.exe
g++ -std=c++17 src\sistema_descuentos.cpp -o bin\sistema_descuentos.exe
g++ -std=c++17 src\cajero_automatico.cpp -o bin\cajero_automatico.exe
g++ -std=c++17 src\horoscopo.cpp -o bin\horoscopo.exe
g++ -std=c++17 src\validacion_hora.cpp -o bin\validacion_hora.exe
```

Ejecutar un programa:

```cmd
bin\calculadora.exe
```

---

 Compilación en Visual Studio (Windows)

1. Crear un proyecto tipo **Console App** en Visual Studio.
2. Agregar cada archivo `.cpp` al proyecto.
3. Compilar y ejecutar desde el IDE.


