# PR-RA2_HTML_CSS

## 1A 
align-items centra el segundo eje y no el primero, no se centra nuestro H1

---
## 1B
Con flex :
.site-header {
  display: flex;
  justify-content: center;
  align-items: center;
} 
El primer eje se alinea con justify-content, lo ponemos en center tambien.

---
## 1D
.site-header {
  display: flex;
  justify-content: center;
  align-items: center;
  margin: 20px;
  padding: 20px;
  color: aquamarine;
  text-shadow: 4px 4px 4px coral;
  background-color: cadetblue;
}
Separamos con el resto del contenido con margin, de forma interna con padding. Aplicamos una sombra con text-shadow. Con background-color le damos un color de fondo distinto al del resto del HTML.
