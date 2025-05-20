# 206-lab-02

# 📱 Breakpoints Implementados

## Media Queries con Flexbox

### 1. **Pantallas Grandes (Desktop)**
   - **Rango**: > 1024px
   - **Estilos base**: 
     ```css
     body {
       background-color: #e6f2ff;
     }
     nav {
       flex-direction: row;
     }
     ```

### 2. **Tablets (Horizontal/Vertical)**
   - **Breakpoint**: 1024px
   - **Cambios clave**:
     ```css
     @media screen and (max-width: 1024px) {
       hero {
         width: 90%;
       }
       .contenedor-galeria img {
         width: 200px; /* 4 columnas */
       }
     }
     ```

### 3. **Móviles (Modo Oscuro Activado)**
   - **Breakpoint**: 767px
   - **Cambios clave**:
     ```css
     @media screen and (max-width: 767px) {
       body {
         background-color: #121212; /* Modo oscuro */
       }
       nav {
         flex-direction: column;
       }
       .contenedor-galeria img {
         width: 45%; /* 2 columnas */
       }
     }
     ```
