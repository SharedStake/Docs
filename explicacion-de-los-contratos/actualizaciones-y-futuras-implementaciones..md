# 🔮 Actualizaciones y futuras implementaciones

### **Futuras implementaciones**

* Distribución: Acumulación de airdrops con la actualización de la raíz merkle \(merkle root\). Este contrato será implementado desde el actual contrato de Airdrop y será utilizado para distribuir los beneficios de Eth2 a los usuarios de SharedStake.
* El staking en los geysers seguirá siendo mejorado \(actualizaciones, eliminación de requisitos de migración cada tres meses, etc.\)

### **Guía de Lanzamiento**

* Lanzamiento del token vEthToken.sol con la dirección del dueño y del acuñador.
* Lanzamiento de Minter.sol usando la dirección del token vEth2.
* Configuración del acuñador de vEth2 y transferencia de la propiedad a la dirección del contrato de Minter.
* En caso de mejoras de contrato, Minter tiene la función setMinter para transferir los tokens al nuevo contrato.

### Notas

* El contrato acuñador no transferirá Eth que no esté stakeado al nuevo contrato.

