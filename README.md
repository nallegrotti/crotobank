# crotobank
Un banco para crotos hecho por crotos

## Finalidad

- Mix entre banca centralizada y descentralizada

## Funcionalidades básicas

- Deposito de divisas
- Mantenimiento de divisas
- Extracción de divisas
- Transferencias de divisas entre cuentas
- Prestamos de divisas con dinero a cambio de un interes
- Pago de servicios
- Transferencias a CBU
- Inversion de activos en fondos de inversion
- Servicio de tokenizacion de cualquier activo

## Sobre los créditos: 

Se pueden otorgar a criterio de los administradores del banco a de los clientes con dinero depositado.

## Sobre el origen de los fondos del banco

Los fondos del banco se depositan en una cuenta que distribuye rentabilidad entre todos sus suscriptores en forma proporcional a sus aportes

## Normalización de dinero fiat
Creacion de token erc20 para opertoria normalizada en la plataforma

## Cuotapartes fondo de inversion 
Creacion de erc721 que representan cuotas partes de fondo de inversión

## Proxy de cuentas

Para no tener que implementar muchas de las integraciones se puede administrar un pool de cuentas de Mercadopago (y otros players del segmento) en forma completamente autonoma para evitar que ningun operador humano tenga acceso a la misma. 
Precondiciones: 
- Todas las transacciones de esa cuenta deben hacerse mediante operaciones registradas en un smartcontract
- Las credenciales deben rotarse en forma frecuente y sólo pueden ser almacenadas en forma segura y encriptada dentro de smartcontracts
- Ningún operador humano debe tener acceso a las cuentas proxeadas ni a sus medios para recupero de contraseña (dichos medios tambien deben ser automatizados)
- Loggeo con metamask 
