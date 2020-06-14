<template>
    <AgroFooter :footerData=footerData />
</template>

<style>

</style>

<script>

import {AgroFooter} from 'agrofy-ui-components'

export default {
    components: {
        'AgroFooter': AgroFooter
    },
    data: function () {
        return {
            footerData : {
                "general": {
                    "copyright": "Todos los derechos reservados",
                    "afip": {
                    "show": true,
                    "href": "http://qr.afip.gob.ar/?qr=kl97ZzOrePSttu_XTrPgIg,,"
                    }
                },
                "about": {
                    "label": "Acerca de",
                    "items": [
                    {
                        "title": "Ayuda",
                        "href": "http://ayuda.agrofy.com.ar/",
                        "label": "Ayuda",
                        "show": true
                    },
                    {
                        "title": "Quiénes Somos",
                        "href": "https://www.agrofy.com.ar/quienes-somos",
                        "label": "Quiénes Somos",
                        "show": true
                    },
                    {
                        "title": "Contacto",
                        "href": "https://www.agrofy.com.ar/contacts",
                        "label": "Contacto",
                        "show": true
                    },
                    {
                        "title": "Sumate a Nuestro Equipo",
                        "href": "https://www.agrofy.com.ar/profesionales",
                        "label": "Sumate a Nuestro Equipo",
                        "show": true
                    },
                    {
                        "title": "Tené tu Sucursal Online",
                        "href": "https://www.agrofy.com.ar/sucursal-online",
                        "label": "Tené tu Sucursal Online",
                        "show": true
                    },
                    {
                        "title": "Programa Market Makers",
                        "href": "http://marketmakers.agrofy.com.ar/",
                        "label": "Programa Market Makers",
                        "show": true
                    },
                    {
                        "title": "AgrofyNews - El medio de negocios del agro",
                        "label": "Agrofy News",
                        "href": "https://news.agrofy.com.ar",
                        "show": true
                    }
                    ]
                },
                "account": {
                    "label": "Mi cuenta",
                    "items": [
                    {
                        "title": "Mi Cuenta",
                        "label": "Mi Cuenta",
                        "href": "https://www.agrofy.com.ar/customer/account/index/",
                        "show": true
                    },
                    {
                        "title": "Mis avisos",
                        "label": "Mis avisos",
                        "href": "https://www.agrofy.com.ar/idscustomer/account-misventas-misavisos/activos/",
                        "show": true
                    },
                    {
                        "title": "Mis favoritos",
                        "label": "Mis favoritos",
                        "href": "https://www.agrofy.com.ar/wishlist/index/index/",
                        "show": true
                    },
                    {
                        "title": "Ayuda",
                        "label": "Ayuda",
                        "href": "http://ayuda.agrofy.com/",
                        "show": true
                    }
                    ]
                },
                "categories": {
                    "label": "Categorias",
                    "items": [
                    {
                        "title": "Herramientas para el Agro en Agrofy",
                        "href": "https://www.agrofy.com.ar/herramientas",
                        "label": "Herramientas"
                    },
                    {
                        "title": "Infraestructura para el Agro en Agrofy",
                        "href": "https://www.agrofy.com.ar/infraestructura",
                        "label": "Infraestructura"
                    },
                    {
                        "title": "Maquinaria Agrícola en Agrofy",
                        "href": "https://www.agrofy.com.ar/maquinaria-agricola",
                        "label": "Maquinaria Agrícola"
                    },
                    {
                        "title": "Campos en Agrofy",
                        "href": "https://www.agrofy.com.ar/campos",
                        "label": "Campos"
                    },
                    {
                        "title": "Insumos Agropecuarios en Agrofy",
                        "href": "https://www.agrofy.com.ar/insumos-agricolas",
                        "label": "Insumos Agropecuarios"
                    },
                    {
                        "title": "Vehículos en Agrofy",
                        "href": "https://www.agrofy.com.ar/vehiculos",
                        "label": "Vehículos"
                    },
                    {
                        "title": "Sucursales Online en Agrofy",
                        "href": "https://www.agrofy.com.ar/sucursales-online?tab=todas",
                        "label": "Sucursales Online"
                    }
                    ]
                },
                "social": {
                    "label": "Seguinos en",
                    "items": [
                    {
                        "href": "https://www.facebook.com/Agrofy.AR",
                        "title": "Seguinos en Facebook",
                        "show": true,
                        "label": "facebook"
                    },
                    {
                        "href": "https://www.instagram.com/agrofy.ar",
                        "title": "Seguinos En Instagram",
                        "show": true,
                        "label": "instagram"
                    },
                    {
                        "href": "https://www.linkedin.com/company/agrofy",
                        "title": "Seguinos En Linkedin",
                        "show": true,
                        "label": "linkedin"
                    }
                    ]
                },
                "legals": {
                    "items": [
                    {
                        "title": "Términos y Condiciones",
                        "href": "https://www.agrofy.com.ar/terminos-y-condiciones/",
                        "label": "Términos y Condiciones",
                        "show": true
                    },
                    {
                        "title": "Políticas de Privacidad",
                        "href": "https://www.agrofy.com.ar/politicas-de-privacidad/",
                        "label": "Políticas de Privacidad",
                        "show": true
                    },
                    {
                        "title": "Políticas de Publicación",
                        "href": "https://www.agrofy.com.ar/politicas-de-publicacion/",
                        "label": "Políticas de Publicación",
                        "show": true
                    }
                    ]
                }
                }
        }
    }
}
</script>