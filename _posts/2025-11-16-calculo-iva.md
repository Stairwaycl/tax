---
layout: post
title: "Guía Completa del IVA: Conceptos, Cálculo y Declaración en Chile"
date: 2025-11-16 14:09:00 -0300
tags: [iva, sii, debito fiscal, credito fiscal, calculo]
last_modified_at: 2025-11-18

---

El **Impuesto al Valor Agregado (IVA)** es el impuesto más importante en Chile, fijado en el **19%**. Es crucial para cualquier emprendedor entender qué es, cómo se calcula y cómo se administra.

---

## 1. 🔍 Conceptos Fundamentales del IVA

El IVA es un impuesto al consumo. Las empresas actúan como **recaudadoras** para el fisco, compensando lo que pagan y lo que cobran en cada transacción.

### Roles del IVA en una Empresa

* **Débito Fiscal:** Es 19% del precio neto que **cobraste** extra a tus clientes en tus ventas (boletas y facturas emitidas). Este monto es una deuda con el fisco.
* **Crédito Fiscal:** Es el IVA que **pagaste** a tus proveedores en tus compras (facturas recibidas). Este monto es un "crédito" que puedes usar para reducir tu deuda.

La obligación mensual de una empresa (F29) se determina por la diferencia:

$$\text{Monto a pagar al fisco} = \text{Débito Fiscal} - \text{Crédito Fiscal}$$

Lo cuál se calcula automático si se usó el RCV del SII. Si no hubo movimiento, se puede declarar sin movimiento.

Es importante recalcar que el SII exige asignar las facturas de compra en clasificaciones, y es importante, ya que sin esto, tu derecho a utilizar el iva pagado como crédito fiscal es nulo.

Si tienes dudas al respecto, lee nuestro artículo sobre la [Clasificación del Crédito Fiscal.]({% post_url 2025-11-12-credito-debito %})

---

## 2. 🧮 Escenarios de Cálculo del IVA (19%)

Es fundamental dominar el desglose de este impuesto al momento de cotizar o emitir documentos.

Para llegar al **Precio Bruto** (el valor total que pagará el cliente), aplicas el 19% de IVA al Precio Neto.

$$\text{Precio Bruto} = \text{Precio Neto} \times 1.19$$

* **Fórmula del IVA:**
    $$\text{IVA} = \text{Precio Neto} \times 0.19$$

* **Ejemplo (Precio Neto: \$100.000):**
    * **IVA(en pesos):**

    $$\text{100.000} \times 0.19 = \boldsymbol{\19.000}$$

    * **Precio Bruto (Total a Pagar(en pesos)**:

    $$\text{100.000} + 19.000 = \boldsymbol{119.000}$$

Por supuesto, si se necesita obtener el Precio Neto y se tiene el Precio Bruto, basta aplicar matemáticas.

---

## 3. 📄 Emisión de Boleta Afecta o Factura en el SII

Estas emisiones servirán para el inicio del mes siguiente, tener el [registro de compras y ventas](#4--registro-de-compras-y-ventas-rcv-y-declaración) y poder declarar efectivamente el F29.

La emisión se realiza a través del **Sistema de Facturación Gratuito** o el **sistema de Boleta Electrónica del SII**.

### Pasos Generales para la Emisión de Boleta Afecta

1.  **Habilitación Previa:** Debes tener un **Inicio de Actividades** y un **giro** habilitado, y _**estar inscrito**_ en el Sistema de Emisión de Boleta Electrónica del SII.
2.  **Emisión:** Ingresa al sitio web del SII con tu **RUT y Clave Tributaria**. Navega a **Boleta de Ventas y Servicios Electrónica** y selecciona **Afecta** al ingresar el monto bruto.

### Emisión de Factura Electrónica

Si tu cliente es otra empresa que necesita usar el IVA como **Crédito Fiscal**, debes emitir una Factura Electrónica (código 33), lo que generalmente requiere un _**Certificado Digital**_.

* **Proceso:** Accede a **Servicios Online** $$\rightarrow$$ **Factura Electrónica** $$\rightarrow$$ **Sistema de Facturación Gratuito del SII**. Ingresa los datos del cliente (**RUT, Razón Social**) y el detalle del servicio.

---

## 4. 💾 Registro de Compras y Ventas (RCV) y Declaración

Una vez que emites tus documentos, el paso final es el registro en el **RCV**, el cual es clave para tu declaración mensual (**Formulario 29**).

### Pasos para Verificar y Usar el RCV

Si utilizas los sistemas de emisión electrónica del SII, el proceso es mayormente **automático**:

1.  **Ingreso:** Ve a `www.sii.cl` $$\rightarrow$$ **Servicios Online** $$\rightarrow$$ **Factura Electrónica** $$\rightarrow$$ **Registro de Compras y Ventas (RCV)**.
2.  **Verificación de Débito:** Revisa la pestaña de **Ventas**. Aquí se suman tus documentos  del  [punto 3](#3--emisión-de-boleta-afecta-o-factura-en-el-sii) de forma automática, lo que constituye tu **Débito Fiscal**.
3.  **Verificación de Crédito:** Revisa la pestaña de **Compras**. Aquí se suman las facturas que recibiste, lo que constituye tu **Crédito Fiscal**.

El SII utiliza la información de este RCV para proponerte automáticamente el borrador de tu declaración de IVA (**Formulario 29**) a fin de mes.

_**Para más detalle sobre cómo usar el RCV [lee nuestro post sobre F29]({% post_url 2025-11-03-f29 %})**_
