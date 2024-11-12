Este es un proyecto de seguimiento de Eventos de Cliente de Shopify para eventos tanto de ecommerce como no-ecommerce.
Envía los datos de los eventos a la data layer, desde donde pueden ser recuperados mediante un sistema de gestión de etiquetas (por ejemplo, Google Tag Manager) y enviados a diferentes plataformas como Google Analytics, Google Ads, entre otras.

Con estos scripts, podrás rastrear los siguientes eventos:

page_view (vista de página)
view_item_list (vista de lista de productos)
view_item (vista de producto)
add_to_cart (añadir al carrito)
view_cart (ver carrito)
remove_from_cart (eliminar del carrito)
begin_checkout (inicio del checkout)
add_shipping_info (añadir información de envío)
add_payment_info (añadir información de pago)
purchase (compra)
view_search_results (ver resultados de búsqueda)
form_submit (envío de formulario)
clicks (en general)
Cómo usarlo:

El proyecto contiene tres scripts: gtm-customer-events-storefront, theme y custom-pixel.

gtm-customer-events-storefront

Navega a Online Store > Themes > Edit Code y encuentra la sección snippets.
Crea un nuevo snippet y nómbralo como gtm-customer-events-storefront.
Pega el contenido del script gtm-customer-events-storefront en el snippet recién creado.

theme

Con el editor de código aún abierto, localiza el archivo theme.liquid.
Pega el contenido del script theme lo más arriba posible en la sección <head>.

custom-pixel

Navega a Settings > Customer Events > Add custom pixel..
Nombra el píxel (por ejemplo, "GTM pixel") y ábrelo.
En la sección de Privacidad del Cliente, selecciona: No requerido (en la sección de Permisos). La recolección de datos no califica como venta de datos (en la sección de Venta de Datos).
Luego, desplázate hasta la sección de Código y reemplaza el código del placeholder de Shopify con el contenido del script custom-pixel.
Revisa y ajusta las configuraciones globales en la parte superior del script.
