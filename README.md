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
## 1C
<img width="1919" height="958" alt="imagen" src="https://github.com/user-attachments/assets/3590235f-cb6b-4cd4-8c39-bf3bba0df760" />
.site-header {
  display: grid;
    grid-template-rows: 100px auto 200px;
    justify-content: center;
    align-items: center;
    gap: 30px;
}
Creamos con grid dos filas distintas para despues alinear los dos ejes al centro, la separacion la conseguimos con "gap"

---
## 1D
<img width="1915" height="956" alt="imagen" src="https://github.com/user-attachments/assets/9c41e303-fc2d-44ce-b46c-2e8fe6a4c59e" />

.site-header {
    display: grid;
    grid-template-rows: 100px auto 200px;
    justify-content: center;
    align-items: center;
    gap: 30px;
  margin: 20px;
  padding: 20px;
  color: aquamarine;
  text-shadow: 4px 4px 4px coral;
  background-color: cadetblue;
  border-radius:10px ;
}
Separamos con el resto del contenido con margin, de forma interna con padding. Aplicamos una sombra con text-shadow. Con background-color le damos un color de fondo distinto al del resto del HTML. Border-radius nos servirá para darle ese aspecto redondeado.
