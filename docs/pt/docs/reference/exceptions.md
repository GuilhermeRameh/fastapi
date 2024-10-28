# Exceções - `HTTPException` e `WebSocketException`

Estas são as exceções que você pode lançar para mostrar erros ao cliente.

Quando você lança uma exceção, como aconteceria com o Python normal, a execução é abortada. Dessa forma, você pode lançar essas exceções de qualquer lugar no código para abortar uma solicitação e exibir o erro para o cliente.

Você pode usar:

* `HTTPException`
* `WebSocketException`

Essas exceções podem ser importadas diretamente de `fastapi`:

```python
from fastapi import HTTPException, WebSocketException
```

::: fastapi.HTTPException

::: fastapi.WebSocketException
