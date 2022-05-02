# Examen-final
-Escriba una función llamada bitcoinToEuros con dos parámetros: bitcoin_amount , la cantidad de Bitcoin que posee, y bitcoin_value_euros , el valor de bitcoin en USD. La función debe devolver euros_value, que es su valor de bitcoin en Euros (para calcular esto, en la función, multiplica la variable bitcoin_amount por la variable bitcoin_value_usd y devuelve el valor).

-Una vez que haya escrito la función bitcoinToEuros, utilícela para calcular el valor de su Bitcoin en USD y luego cree una declaración if para determinar si el valor cae por debajo de 30,000€; si lo hace, envíe un mensaje para alertarlo (a través de una declaración de impresión).

-Ahora y con la experiencia de nuestro anterior programa vamos a diseñar un sistema de gestión de compra y venta de NFT´S. Los NFTs (Non-Fungible Tokens) son activos digitales que básicamente son una extensión de bienes tangibles que antes podíamos tocar y ver (oro, sellos, obras de arte), y ahora los tenemos en la red de redes como coleccionismo de arte y bienes digitales.

-Se supone la existencia de usuarios compradores y vendedores que se conectan a un servidor que gestiona las ofertas y las demandas. Se supone, además, una clasificación de criptomonadas por su nivel de riesgo (bajo, medio y alto), que se puede calcular mediante la función predefinida Nivel_Riesgo(nft).

-Cuando un vendedor desea utilizar este sistema para poder en venta una nfts, publica un anuncio ubicado en el servidor y a continuación queda esperando a que algún comprador le notifique el interés de adquirir el NFT. Tras realizarse la adquisición, se retirará el anuncio del tablón.

-Por otro lado, cuando un comprador adquiere el NFT, deberá comunicar al servidor el máximo nivel de riesgo que desea asumir. Al realizar esta petición, el comprador le indicara también al servidor que anuncios ha descartado ya, con el fin que el servidor no le proporcione un anuncio que ya haya sido consultado.

-Seguidamente, el comprador examinará el anuncio con la intención de averiguar si le interesa o no (función predefinida Interesa(Cliente, nft). Si no le interesa, lo descartará y vuelve a pedir un anuncio con idéntico riesgo al servidor. Si, por el contrario, el anuncio le interesa, el comprador notificará el interés al servidor y a este, a su vez, se lo hará saber al vendedor. Si la notificación llega tarde porque otro comprador notifica se ha adelantado, el comprador pedirá al servidor otro anuncio (de nuevo con el mismo interés de riesgo).

-Suponemos además que:

    -Los anuncios no caducan, están expuestos hasta que se realiza la venta del NFT.
    -El tablón tiene una capacidad limitada de K anuncios.
    -Hay un máximo de V vendedores y C compradores, siendo estos valoras relativamente pequeños (máximo 20)
    -La cuestión del pago no está contemplada.
