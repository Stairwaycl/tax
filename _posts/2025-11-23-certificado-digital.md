---
title: "Firma Electrónica Simple (FES)"
layout: post
---

El Certificado Digital (o Firma Electrónica Simple, FES) es tu identidad digital ante el Servicio de Impuestos Internos (SII). Funciona como tu cédula de identidad, pero en formato digital, y es obligatorio para emitir la mayoría de los Documentos Tributarios Electrónicos (DTE), como facturas y, en ciertos casos, boletas.

## 🔑 Certificado Digital: Instalado vs. Centralizado


Existen dos formas de trabajar con el FES: siendo instalado en el pc o usado directamente en el sii (centralizado). La diferencia entre ambas radica en dónde se almacena y cómo se utiliza ese archivo de identidad.🔑

<table class="table table-bordered">
  <thead>
    <tr>
      <th>Característica</th>
      <th>Instalado (local)</th>
      <th>Centralizado (en el SII)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Ubicacion</td>
      <td>Guardado directamente en tu computador (como un archivo .pfx o .p12).</td>
      <td>Almacenado de forma segura en los servidores del SII o del proveedor.</td>
    </tr>
    <tr>
      <td>Uso</td>
      <td>Solo puedes usarlo desde el computador específico donde está instalado (o donde lo importes).</td>
      <td>Solo puedes usarlo desde el computador específico donde está instalado (o donde lo importes).</td>
    </tr>
    <tr>
      <td>Proceso</td>
      <td>Requiere que lo instales en el navegador (en tu caso, un proceso que puede ser más complejo dependiendo del navegador y sistema operativo.</td>
      <td>Requiere que subas el archivo de tu certificado al portal del SII. El SII lo almacena y lo usa por ti cuando firmas un DTE.</td>
    </tr>
        <tr>
      <td>Ventaja Principal</td>
      <td>Mayor control si usas un software de facturación propio.</td>
      <td>Comodidad y movilidad (ideal si trabajas desde diferentes lugares, como con proyectos digitales).</td>
    </tr>
        <tr>
      <td>Desventaja</td>
      <td>Si el equipo falla, debes tener un respaldo o reinstalarlo.</td>
      <td>Solo se puede usar con el sistema de facturación gratuito del SII o sistemas que admitan esta modalidad.</td>
    </tr>
  </tbody>
</table>

La centralización en el SII puede ser la opción más práctica si te quieres evitar problemas de configuración o compatibilidad del certificado instalado.

Tambien puedes emitir facturas o boletas afectas a clientes para tus servicios desde cualquier lugar, sin depender de un único equipo.

## Pasos para la Centralización (Resumen)

Si ya compraste tu certificado digital (en formato ```.pfx``` o .```p12```), el proceso en el SII es generalmente:
1. Ingreso: Entra al portal del SII (sii.cl) con tu RUT y Clave Tributaria.
2. Navegación: Ve a Servicios Online $$\rightarrow$$ Factura Electrónica $$\rightarrow$$ Sistema de facturación gratuito del SII $$\rightarrow$$ Centralizar su certificado digital.
3. Carga: Sube el archivo de tu certificado ```(.pfx)``` e ingresa la contraseña que le asignaste al crearlo.Una vez centralizado, el SII lo utilizará para "firmar" electrónicamente cada documento tributario que generes a través de su plataforma gratuita.
