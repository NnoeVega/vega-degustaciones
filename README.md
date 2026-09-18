# Vega Degustaciones

Propuestas y sitios web del proyecto **Vega Degustaciones** — degustaciones con proyección de patrimonio fotográfico de San Rafael, Mendoza.

## Estructura del repositorio

Cada carpeta contiene un `index.html` autocontenido, listo para deployar como sitio independiente en Vercel:

| Carpeta | Propuesta | Público objetivo |
|---|---|---|
| [`publico/`](publico/) | Sitio principal de la experiencia | Clientes finales |
| [`anfitriones/`](anfitriones/) | Programa para dueños de espacios | Cabañas, hoteles, chacras |
| [`invitados/`](invitados/) | Programa para invitados especiales y partnership | Enólogos, historiadores, sommeliers |
| [`captadores/`](captadores/) | Programa mayorista para revendedores | Agencias, guías, hoteleros |
| [`bodegas/`](bodegas/) | Servicio "La Cata Ilustrada" | Bodegas locales |
| [`tienda/`](tienda/) | Degustando en Casa — tienda con carrito | Clientes finales |

## Deploy a Vercel

Cada carpeta se conecta a su propio proyecto Vercel usando **Root Directory** apuntando a la carpeta correspondiente. Cambios en un `index.html` disparan el redeploy automático del proyecto vinculado.

## Analítica

Todos los sitios tienen instalado el **Meta Pixel** (`ID: 1096077809477649`) con evento `PageView` en carga y evento `Contact` disparado en cada interacción con WhatsApp (links directos, botón de reservas del formulario y checkout de la tienda).

## Contacto

- WhatsApp: +54 9 260 463-0599
- Instagram: [@degustandosanrafael](https://www.instagram.com/degustandosanrafael/)
- Facebook: [Perfil](https://www.facebook.com/profile.php?id=61588817952370)
