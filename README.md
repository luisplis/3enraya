
# Juego 3 en Raya

__Demo en React con useState__

Instalar Node y sus dependencias para React:
`pnpm install`

Lanzar simulación del proyecto al navegador:
`pnpm start`

![vista previa del juego](/public/capture.png)

```javascript
--
import { useState } from 'react';
--
const [values, setValues] = useState(Array(10).fill(''));
const [status, setStatus] = useState('');
const [log, setLog]       = useState([]);
···
```