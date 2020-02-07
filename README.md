

# Pasos para utilizar Bootstrap con React

Reactstrap te permite utilizar Bootstrap (CSS y JS) en tu aplicación de React.


Los pasos para poder utilizarlo son:


Instalar Bootstrap a través de npm:

```npm install --save bootstrap```



2. Instalar Reactstrap a través de npm:

```npm install --save reactstrap react react-dom```



3. Importar en index.js la siguiente línea:

```import 'bootstrap/dist/css/bootstrap.min.css';```



4. Importar los componentes que necesitas (Modal, Button, Card…) desde el componente donde los vayas a utilizar:

```import { Button, Modal, ModalHeader, ModalBody, ModalFooter } from 'reactstrap';```
