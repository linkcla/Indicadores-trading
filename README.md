# INDICADORES TRADING📈📉

En este repositorio encontramos tres indicadores de trading programados en **PineScript** el propio lenguaje de *TradingView*.

*La mayor parte de los codigos estan extraidos de otros indicadores de grandes contribuyentes en la plataforma de TradingView ([LuxAlgo](https://es.tradingview.com/u/LuxAlgo/) y [francrypto_](https://es.tradingview.com/u/francrypto_/))*

***
## Imbalance + EMAs
Indicador que mostrará encima de las barras las zonas de imbalance que se producen entre 3 velas consecutivas, este imbalance se marcara con un recuadro amarillo al lado de la vela generadora del imbalance.
Por otra parte, también he añadido 3 EMAS que se pueden personalizar (color y longitud) mediante el panel de ajustes.

## Imbalance + EMAs + Volume profile
Este indicador es el *Imbalance + EMAs* añadiendo el perfil de volumen📊. Este perfil de volumen está sacado de uno de los indicadores de [francrypto_](https://es.tradingview.com/u/francrypto_/).

## Imbalance + EMAs + Volume profile + Order block.
Este indicador es el *Imbalance + EMAs + Volume profile* añadiendo los order blocks. En este indicador tuve problemas para extraer únicamente el plot de los order blcks del indicador [Smart Money de LuxAlgo](https://es.tradingview.com/script/CnB3fSph-Smart-Money-Concepts-LuxAlgo/), por eso acabé añadiendo a todo este indicador las EMMAs y el perfil de volumen. 
Únicamente hice unos cuantos cambios en las funciones relacionadas en calcular los imbalances.

***

He creado estas mezclas porque *TradingView* se está volviendo cada vez más restrictivo y solo permite mostrar dos indicadores a la vez con la versión gratuita, de esta forma puedo tener muchos indicadores que cuentan como uno.
Tocar el código de estos indicadores me ha permitido entender como es **PineScript**.