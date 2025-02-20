# Trazado de una vulnerabilidad

Indice de contenidos:

1. [Información sobre la vulnerabilidad](#información-sobre-la-vulnerabilidad)
2. [Información sobre las debilidades explotadas](#información-sobre-el-riesgo-o-criticidad-de-una-vulnerabilidad)
3. [Información sobre las debilidades explotadas](#información-sobre-las-debilidades-explotadas)
4. [Información sobre patrones de ataque](#información-sobre-patrones-de-ataque)
5. [Descarga del Registro CVE de la vulnerabilidad](#descarga-del-registro-cve-de-la-vulnerabilidad)

- - -

Vulnerabilidad a trazar [GoAnywhere MFT de Fortra](https://www.incibe.es/empresas/avisos/vulnerabilidad-critica-de-omision-de-autenticacion-en-goanywhere-mft-de-fortra).


## Información sobre la vulnerabilidad

En la web de incibe donde alerta sobre la vulnerabilidad al final del artículo podemos enoctr el cve de la vulnerabilidad.

![Incibe vulnerabilitie note](images/incibe-vulnerabilitie-note.png)

Y un poco más abajo podemos encontar el enlace al comunicado propio de la empresa [FI-2024-001 - Authentication Bypass in GoAnywhere MFT](https://www.fortra.com/security/advisories/product-security/fi-2024-001).

![Incibe refence](images/incibe-refence.png)

En el comunicado de la empresa nos detalla tambien el cve al que hace referencia, información de la criticidad, etc.

![Fortra comunication 1](images/fortra-comunication_1.png)

![Fortra comunication 2](images/fortra-comunication_2.png)

## Información sobre el riesgo o criticidad de una vulnerabilidad

Encontramos información más detallada tanto en la web [CVE referente a la vulnerabilidad CVE-2024-0204](https://www.cve.org/CVERecord?id=CVE-2024-0204) como en la gubernamental [NIST refente a la vulneabilidad CVE-2024-0204](https://nvd.nist.gov/vuln/detail/CVE-2024-0204). Podemos observar que nos da una descripción de la vulnerabilidad seguido de la puntuación que define su gravedad para la versión 3 del estandard métrico.

![NIST Metrics](images/nist-metrics.png)

Si ponemos el cursor sobre el Vector nos aparecerán los valores correspondientes a las diferentes métricas que se han usado para el calculo de la puntuación.

![NIST Vector](images/nist-vector.png)


## Información sobre las debilidades explotadas
Otra información adicional que nos ofrece el NIST es el enlace a la debilidad.
![NIST weakness](images/nist-weakness.png)

El [enlace de Common Weaknes Enumeration](https://cwe.mitre.org/data/definitions/425.html) nos ofrece informatión detallada de la debilidad **CWE-425**, informandonos que consiste en que hay ciertas rutas que no están correctamente securizadas, debido a que asume que solo son accesibles desde otras que si están securizadas, permitiendo la explotación de CSRF o XSS.

![CWE description](images/cwe-description.png)

## Información sobre patrones de ataque

## Descarga del Registro CVE de la vulnerabilidad


