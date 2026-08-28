# Demos de sitios web — Santiago sur

Propuestas de diseño para locales de barrio que hoy solo existen en Google Maps:
sin página web propia, dependiendo de apps de delivery que se llevan entre 25% y 30% de cada venta.

**Ver las demos:** https://delaguardaagustin.github.io/demos-web/

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
