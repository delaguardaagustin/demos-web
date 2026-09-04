# Demos para negocios — Santiago

Propuestas de sitio web, sistema de reservas y catálogo online para negocios que hoy
solo existen en Google Maps. Todo directo al WhatsApp del local, sin comisiones ni
mensualidad de plataforma.

**Ver todas las demos:** https://delaguardaagustin.github.io/demos-web/

## Estructura del repo

- **Sitios web** (`/`, carpetas sueltas en la raíz) — locales de Santiago sur, con menú y
  armador de pedido por WhatsApp. Ver tabla abajo.
- **Sistemas de reservas** (`reservas-<comuna>/`) — peluquerías, barberías, clínicas y
  gimnasios. Reserva de hora online con recordatorio automático.
  - [`reservas-nunoa/`](reservas-nunoa/) — Ñuñoa
  - [`reservas-providencia/`](reservas-providencia/) — Providencia
  - [`reservas-lascondes/`](reservas-lascondes/) — Las Condes
- **Catálogos online** (`catalogos-joyerias/`) — joyerías sin página web, catálogo de
  piezas reales con pedido por WhatsApp.

Cada carpeta de categoría tiene su propio `index.html` como mini-galería, y todo está
enlazado desde el `index.html` de la raíz.

## Sitios web — tabla completa

| Demo | Rubro | Zona |
|---|---|---|
| [`comic-lon/`](comic-lon/) | Hamburguesería | La Cisterna |
| [`donde-giulianos/`](donde-giulianos/) | Comida rápida | Macul |
| [`arabito-deluxe/`](arabito-deluxe/) | Comida árabe | Macul |
| [`kami-sushi/`](kami-sushi/) | Sushi, 6 locales | La Granja · Puente Alto · San Ramón |
| [`bajon-tio-coco/`](bajon-tio-coco/) | Comida rápida | La Florida |
| [`santo-sabor/`](santo-sabor/) | Comida rápida | La Florida |
| [`la-capital-restobar/`](la-capital-restobar/) | Restobar | Macul |
| [`big-george/`](big-george/) | Hamburguesas | Puente Alto |
| [`the-gustapoco/`](the-gustapoco/) | Comida rápida | San Joaquín |
| [`stc-gimnasio/`](stc-gimnasio/) | Gimnasio, con armador de plan | La Cisterna |
| [`los-negros-sangucheria/`](los-negros-sangucheria/) | Sanguchería, con armador de pedidos | Puente Alto |
| [`diez-pa-la-una/`](diez-pa-la-una/) | Hamburguesería, con armador de pedidos | Puente Alto |
| [`pasteleria-wafel/`](pasteleria-wafel/) | Pastelería, con armador de encargos | Puente Alto |
| [`sushi-rotonda-grecia/`](sushi-rotonda-grecia/) | Sushi, con armador de pedidos | Peñalolén |
| [`el-rinconcito-peruano/`](el-rinconcito-peruano/) | Comida peruana, con armador de pedidos | Estación Central |
| [`la-picada-de-piero/`](la-picada-de-piero/) | Comida peruana, con armador de pedidos | Estación Central |
| [`pizzeria-colon/`](pizzeria-colon/) | Pizzería, con armador de pedidos | San Bernardo |
| [`piu-pizzeria/`](piu-pizzeria/) | Pizzería napoletana, con armador de pedidos | Maipú |
| [`sansu-sushi/`](sansu-sushi/) | Sushi, con armador de pedidos | Maipú |
| [`oroshi-sushi/`](oroshi-sushi/) | Restaurante japonés, con armador de pedidos | Maipú |
| [`pasteleria-daca/`](pasteleria-daca/) | Pastelería, con armador de encargos | La Florida |
| [`importadora-anama/`](importadora-anama/) | Ropa por mayor, con armador de cotización | Estación Central |

## Aviso

Estas páginas son **demostraciones**. No son los sitios oficiales de los locales y no existe
relación comercial con ellos. Los menús, precios y horarios son inventados como ejemplo.
El nombre, la dirección y la calificación provienen de sus fichas públicas de Google Maps.
Todas llevan `noindex` y una franja visible que lo declara.

## Cómo están hechas

Un solo `index.html` por sitio. Sin build, sin dependencias, sin JavaScript de terceros.

- Mobile-first — casi todo el tráfico de estos negocios entra desde el celular
- Paleta propia por rubro, definida con variables CSS
- Botón de pedido que arma un mensaje de WhatsApp listo para enviar
- Peso: ~10 KB por página, carga instantánea incluso con señal mala

## Correr en local

```bash
python -m http.server 4321
```

Después abre `http://localhost:4321/`.

---

Agustín de la Guarda · Santiago, Chile
