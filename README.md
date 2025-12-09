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

---
## 3a, 3B y 3C
Cuando pasamos por encima de la imagen esta se hace más grande, y genera un sombreado azul, gracias a colocarlo en CSS con :hover
<img width="1918" height="893" alt="imagen" src="https://github.com/user-attachments/assets/c612043f-cec5-40a1-a90a-2eaa64fc83db" />
Cuando clicamos encima de ella nos manda a otra pestaña con el tamaño original de la misma:
<img width="1916" height="998" alt="imagen" src="https://github.com/user-attachments/assets/6e2d2c81-2ccd-44d9-bd66-3d1de64815c0" />
### Aqui están mi CSS y HTML :  
<img width="545" height="486" alt="imagen" src="https://github.com/user-attachments/assets/473e89a6-0819-4097-9f50-4470aa306513" />
<img width="1019" height="278" alt="imagen" src="https://github.com/user-attachments/assets/f1731f10-fb7b-49d9-afbb-6f46eca41fa4" />

---


