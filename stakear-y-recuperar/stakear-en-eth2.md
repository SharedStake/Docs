---
description: 'Tienes tu vEth2, pero… ¿qué pasa con tu Ethereum?'
---

# 🔩 Stakear en Eth2

El proceso de staking va relacionado con un contrato de acuñación \([Minter](https://etherscan.io/address/0xbca3b7b87dcb15f0efa66136bc0e4684a3e5da4d)\) del token [vEth2](https://etherscan.io/token/0x898bad2774eb97cf6b94605677f43b41871410b1). Este contrato es desplegado en la red principal \(mainnet\). 

Tras stakear Eth en el protocolo de SharedStake, los usuarios pueden recuperar su Eth a cambio de su [vEth2](https://etherscan.io/token/0x898bad2774eb97cf6b94605677f43b41871410b1). Esta funcionalidad reduce los riesgos y los costes e incrementa la usabilidad del protocolo.

{% page-ref page="../fundamentos/caracteristicas-destacadas/recuperar-tu-eth-stakeado-en-sharedstake.md" %}

El proceso de recuperación se activa tras un periodo predeterminado o una vez se alcanza el límite del balance del contrato. 

En ese momento el contrato de acuñación es pausado para prevenir cualquier pérdida mientras se crean los validadores. Desplegamos múltiples validadores al [Contrato de Depósito de Eth2.0](https://etherscan.io/address/0x00000000219ab540356cBB839Cbe05303d7705Fa). Tras este proceso, el contrato se reanuda y vuelve a aceptar Eth y acuñar vEth2 de nuevo.

**El** [**contrato de acuñación**](https://etherscan.io/address/0xbca3b7b87dcb15f0efa66136bc0e4684a3e5da4d) **puede ser actualizado mediante los diferentes SIPs y votado por los miembros de la DAO con SGT.**

