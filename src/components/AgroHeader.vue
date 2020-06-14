<template>
    <AgroHeader :generalData=generalData :menuData=menuData :userInfo=userData  />
</template>

<style>

</style>

<script>

import {AgroHeader} from 'agrofy-ui-components'

export default {
    components: {
        'AgroHeader': AgroHeader
    },
    data: function() {
        return {
            generalData : {
                footer: {
                about: {
                    items: [
                    {
                        href: 'http://ayuda.agrofy.com.ar/',
                        label: 'Ayuda',
                        show: true,
                        title: 'Ayuda'
                    },
                    {
                        href: 'https://www.agrofy.com.ar/quienes-somos',
                        label: 'Quiénes Somos',
                        show: true,
                        title: 'Quiénes Somos'
                    },
                    {
                        href: 'https://www.agrofy.com.ar/contacts',
                        label: 'Contacto',
                        show: true,
                        title: 'Contacto'
                    },
                    {
                        href: 'https://www.agrofy.com.ar/profesionales',
                        label: 'Sumate a Nuestro Equipo',
                        show: true,
                        title: 'Sumate a Nuestro Equipo'
                    },
                    {
                        href: 'https://www.agrofy.com.ar/sucursal-online',
                        label: 'Tené tu Sucursal Online',
                        show: true,
                        title: 'Tené tu Sucursal Online'
                    },
                    {
                        href: 'http://marketmakers.agrofy.com.ar/',
                        label: 'Programa Market Makers',
                        show: true,
                        title: 'Programa Market Makers'
                    },
                    {
                        href: 'https://news.agrofy.com.ar',
                        label: 'Agrofy News',
                        show: true,
                        title: 'AgrofyNews - El medio de negocios del agro'
                    }
                    ],
                    label: 'Acerca de'
                },
                account: {
                    items: [
                    {
                        href: 'https://www.agrofy.com.ar/customer/account/index/',
                        label: 'Mi Cuenta',
                        show: true,
                        title: 'Mi Cuenta'
                    },
                    {
                        href: 'https://www.agrofy.com.ar/idscustomer/account-misventas-misavisos/activos/',
                        label: 'Mis avisos',
                        show: true,
                        title: 'Mis avisos'
                    },
                    {
                        href: 'https://www.agrofy.com.ar/wishlist/index/index/',
                        label: 'Mis favoritos',
                        show: true,
                        title: 'Mis favoritos'
                    },
                    {
                        href: 'http://ayuda.agrofy.com/',
                        label: 'Ayuda',
                        show: true,
                        title: 'Ayuda'
                    }
                    ],
                    label: 'Mi cuenta'
                },
                categories: {
                    items: [
                    {
                        href: 'https://www.agrofy.com.ar/herramientas',
                        label: 'Herramientas',
                        title: 'Herramientas para el Agro en Agrofy'
                    },
                    {
                        href: 'https://www.agrofy.com.ar/infraestructura',
                        label: 'Infraestructura',
                        title: 'Infraestructura para el Agro en Agrofy'
                    },
                    {
                        href: 'https://www.agrofy.com.ar/maquinaria-agricola',
                        label: 'Maquinaria Agrícola',
                        title: 'Maquinaria Agrícola en Agrofy'
                    },
                    {
                        href: 'https://www.agrofy.com.ar/campos',
                        label: 'Campos',
                        title: 'Campos en Agrofy'
                    },
                    {
                        href: 'https://www.agrofy.com.ar/insumos-agricolas',
                        label: 'Insumos Agropecuarios',
                        title: 'Insumos Agropecuarios en Agrofy'
                    },
                    {
                        href: 'https://www.agrofy.com.ar/vehiculos',
                        label: 'Vehículos',
                        title: 'Vehículos en Agrofy'
                    },
                    {
                        href: 'https://www.agrofy.com.ar/sucursales-online?tab=todas',
                        label: 'Sucursales Online',
                        title: 'Sucursales Online en Agrofy'
                    }
                    ],
                    label: 'Categorias'
                },
                general: {
                    afip: {
                    href: 'http://qr.afip.gob.ar/?qr=kl97ZzOrePSttu_XTrPgIg,,',
                    show: true
                    },
                    copyright: 'Todos los derechos reservados'
                },
                legals: {
                    items: [
                    {
                        href: 'https://www.agrofy.com.ar/terminos-y-condiciones/',
                        label: 'Términos y Condiciones',
                        show: true,
                        title: 'Términos y Condiciones'
                    },
                    {
                        href: 'https://www.agrofy.com.ar/politicas-de-privacidad/',
                        label: 'Políticas de Privacidad',
                        show: true,
                        title: 'Políticas de Privacidad'
                    },
                    {
                        href: 'https://www.agrofy.com.ar/politicas-de-publicacion/',
                        label: 'Políticas de Publicación',
                        show: true,
                        title: 'Políticas de Publicación'
                    }
                    ]
                },
                social: {
                    items: [
                    {
                        href: 'https://www.facebook.com/Agrofy.AR',
                        label: 'facebook',
                        show: true,
                        title: 'Seguinos en Facebook'
                    },
                    {
                        href: 'https://www.instagram.com/agrofy.ar',
                        label: 'instagram',
                        show: true,
                        title: 'Seguinos En Instagram'
                    },
                    {
                        href: 'https://www.linkedin.com/company/agrofy',
                        label: 'linkedin',
                        show: true,
                        title: 'Seguinos En Linkedin'
                    }
                    ],
                    label: 'Seguinos en'
                }
                },
                header: {
                loginLabel: 'INGRESAR',
                loginUrl: 'https://www.agrofy.com.ar/customer/account/login/index?redirectURL=https%3A%2F%2Fwww.agrofy.com.ar%2F',
                newsLinks: [
                    {
                    iconClass: 'noticias',
                    name: 'Noticias',
                    url: 'https://news.agrofy.com.ar/'
                    },
                    {
                    iconClass: 'clima',
                    name: 'Clima',
                    url: 'https://news.agrofy.com.ar/pronostico-clima-tiempo'
                    },
                    {
                    iconClass: 'cotizaciones',
                    name: 'Cotizaciones',
                    url: 'https://news.agrofy.com.ar/granos'
                    },
                    {
                    iconClass: 'foro',
                    name: 'Foro',
                    url: 'https://news.agrofy.com.ar/foro'
                    }
                ],
                onlineStore: 'Ver Sucursal Online',
                postLabel: 'Publicar',
                postUrl: 'https://www.agrofy.com.ar/customer/account/login?redirectURL=https%3A%2F%2Fwww.agrofy.com.ar%2Faviso%2Fonepage%2Findex%2F'
                },
                notifications: {
                acceptedQuotations: ' ha aceptado tu cotización del producto ',
                account: 'Mi cuenta',
                answerQuotations: ' te ha respondido tu pedido de cotización del producto ',
                followAgroshop: 'Notificaciones de mi red',
                last: 'ÚLTIMAS CONSULTAS',
                lastAcceptedQuotations: 'ÚLTIMAS COTIZACIONES ACEPTADAS',
                lastQuotations: 'ÚLTIMAS COTIZACIONES',
                logout: 'Salir',
                more: 'Ver más',
                newQuotations: ' ha solicitado una cotización de tu producto ',
                noNotif: 'No tenés notificaciones nuevas.',
                received: 'Recibidas',
                sent: 'Enviadas'
                },
                text: {
                categories: 'Categorías',
                onlineStores: 'Sucursales Online',
                placeholder: 'Buscar...',
                searchAgrofy: 'Buscar en Agrofy...'
                }
            },
            menuData : {
                desktop: [
                {
                    Children: [
                    {
                        Children: [
                        {
                            HasLink: '0',
                            ID: '114',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Trigo',
                            SecondIcon: '',
                            URL: '/semillas-de-trigo',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '140',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Soja',
                            SecondIcon: '',
                            URL: '/semillas-de-soja',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '165',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Maíz',
                            SecondIcon: '',
                            URL: '/semillas-de-maiz',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '277',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Sorgo',
                            SecondIcon: '',
                            URL: '/semillas-de-sorgo',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '278',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Girasol',
                            SecondIcon: '',
                            URL: '/semillas-de-girasol',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        }
                        ],
                        HasLink: '0',
                        ID: '113',
                        Icon: '',
                        IsNavigable: '1',
                        LinkText: null,
                        Name: 'Semillas e Híbridos',
                        SecondIcon: '',
                        URL: '/semillas',
                        WhenLogged: '1',
                        WhenNotLogged: '1'
                    },
                    {
                        Children: [
                        {
                            HasLink: '0',
                            ID: '107',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Fungicidas',
                            SecondIcon: '',
                            URL: '/fungicidas',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '108',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Herbicidas',
                            SecondIcon: '',
                            URL: '/herbicidas',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '109',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Insecticidas',
                            SecondIcon: '',
                            URL: '/insecticidas',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '141',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Coadyuvantes',
                            SecondIcon: '',
                            URL: '/coadyuvantes',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        }
                        ],
                        HasLink: '0',
                        ID: '106',
                        Icon: '',
                        IsNavigable: '1',
                        LinkText: null,
                        Name: 'Protección de Cultivos',
                        SecondIcon: '',
                        URL: '/proteccion-de-cultivos',
                        WhenLogged: '1',
                        WhenNotLogged: '1'
                    },
                    {
                        Children: [
                        {
                            HasLink: '0',
                            ID: '116',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Nitrogenados',
                            SecondIcon: '',
                            URL: '/fertilizantes/elemento-nitrogeno',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '117',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Fosfatados',
                            SecondIcon: '',
                            URL: '/fertilizantes/elemento-fosforo',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '118',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Potásicos',
                            SecondIcon: '',
                            URL: '/fertilizantes/elemento-potasio',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '166',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Azufrados',
                            SecondIcon: '',
                            URL: '/fertilizantes/elemento-azufre',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        }
                        ],
                        HasLink: '0',
                        ID: '115',
                        Icon: '',
                        IsNavigable: '1',
                        LinkText: null,
                        Name: 'Fertilizantes',
                        SecondIcon: '',
                        URL: '/fertilizantes',
                        WhenLogged: '1',
                        WhenNotLogged: '1'
                    },
                    {
                        Children: [
                        {
                            HasLink: '0',
                            ID: '143',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Inoculantes',
                            SecondIcon: '',
                            URL: '/inoculantes',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '145',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Silo Bolsas',
                            SecondIcon: '',
                            URL: '/silo-bolsas',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        }
                        ],
                        HasLink: '0',
                        ID: '142',
                        Icon: '',
                        IsNavigable: '0',
                        LinkText: null,
                        Name: 'Otros Insumos Agrícolas',
                        SecondIcon: '',
                        URL: null,
                        WhenLogged: '1',
                        WhenNotLogged: '1'
                    }
                    ],
                    HasLink: '1',
                    ID: '105',
                    Icon: '',
                    IsNavigable: '1',
                    LinkText: 'Todo Insumos Agrícolas',
                    Name: 'Insumos Agrícolas',
                    SecondIcon: '',
                    URL: '/insumos-agricolas',
                    WhenLogged: '1',
                    WhenNotLogged: '1'
                },
                {
                    Children: [
                    {
                        Children: [
                        {
                            HasLink: '1',
                            ID: '297',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Antibióticos',
                            SecondIcon: '',
                            URL: '/insumos-veterinarios/antibioticos',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '1',
                            ID: '298',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Antiparasitarios',
                            SecondIcon: '',
                            URL: '/insumos-veterinarios/antiparasitarios',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '1',
                            ID: '299',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Antiinflamatorios',
                            SecondIcon: '',
                            URL: '/insumos-veterinarios/antiinflamatorios',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '1',
                            ID: '300',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Hormonales',
                            SecondIcon: '',
                            URL: '/insumos-veterinarios/hormonales',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '1',
                            ID: '301',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Vitaminas y Minerales',
                            SecondIcon: '',
                            URL: '/insumos-veterinarios/vitaminas-y-minerales',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        }
                        ],
                        HasLink: '0',
                        ID: '296',
                        Icon: '',
                        IsNavigable: '1',
                        LinkText: null,
                        Name: 'Insumos Veterinarios',
                        SecondIcon: '',
                        URL: '/insumos-veterinarios',
                        WhenLogged: '1',
                        WhenNotLogged: '1'
                    },
                    {
                        Children: [
                        {
                            HasLink: '0',
                            ID: '305',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Alimentos Balanceados',
                            SecondIcon: '',
                            URL: '/alimentos-balanceados',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '306',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Alimentos Concentrados',
                            SecondIcon: '',
                            URL: '/alimentos_concentrados',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '307',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Subproductos Industriales',
                            SecondIcon: '',
                            URL: '/subproductos-industriales',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '343',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Forrajes Conservados',
                            SecondIcon: '',
                            URL: '/forrajes-conservados',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '344',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Núcleos, Correctores y Suplementos',
                            SecondIcon: '',
                            URL: '/correctores',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        }
                        ],
                        HasLink: '0',
                        ID: '304',
                        Icon: '',
                        IsNavigable: '1',
                        LinkText: null,
                        Name: 'Nutrición Animal',
                        SecondIcon: '',
                        URL: '/nutricion-animal',
                        WhenLogged: '1',
                        WhenNotLogged: '1'
                    },
                    {
                        Children: [
                        {
                            HasLink: '0',
                            ID: '320',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Bovinos de Carne',
                            SecondIcon: '',
                            URL: '/bovinos-de-carne',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        }
                        ],
                        HasLink: '0',
                        ID: '319',
                        Icon: '',
                        IsNavigable: '1',
                        LinkText: null,
                        Name: 'Reproducción y Genética',
                        SecondIcon: '',
                        URL: '/reproduccion-y-genetica',
                        WhenLogged: '1',
                        WhenNotLogged: '1'
                    }
                    ],
                    HasLink: '1',
                    ID: '318',
                    Icon: '',
                    IsNavigable: '1',
                    LinkText: 'Todo Insumos para Ganadería',
                    Name: 'Insumos para Ganadería',
                    SecondIcon: '',
                    URL: '/insumos-para-ganaderia',
                    WhenLogged: '1',
                    WhenNotLogged: '1'
                },
                {
                    Children: [
                    {
                        Children: [
                        {
                            HasLink: '0',
                            ID: '7',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Tractores',
                            SecondIcon: '',
                            URL: '/tractores',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '8',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Pulverizadoras',
                            SecondIcon: '',
                            URL: '/pulverizadoras',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '68',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Sembradoras',
                            SecondIcon: '',
                            URL: '/sembradoras',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '9',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Cosechadoras',
                            SecondIcon: '',
                            URL: '/cosechadoras',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '119',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Fertilizadoras',
                            SecondIcon: '',
                            URL: '/fertilizadoras',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '69',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Plataformas y Cabezales',
                            SecondIcon: '',
                            URL: '/plataformas-y-cabezales',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        }
                        ],
                        HasLink: '0',
                        ID: '6',
                        Icon: '',
                        IsNavigable: '0',
                        LinkText: null,
                        Name: 'Implementos Agrícolas',
                        SecondIcon: '',
                        URL: null,
                        WhenLogged: '1',
                        WhenNotLogged: '1'
                    },
                    {
                        Children: [
                        {
                            HasLink: '0',
                            ID: '13',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Rastras',
                            SecondIcon: '',
                            URL: '/rastras',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '14',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Paratill',
                            SecondIcon: '',
                            URL: '/paratill',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '15',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Palas y Niveladoras',
                            SecondIcon: '',
                            URL: '/palas-y-niveladoras',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '17',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Rolos',
                            SecondIcon: '',
                            URL: '/rolos',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        }
                        ],
                        HasLink: '0',
                        ID: '12',
                        Icon: '',
                        IsNavigable: '0',
                        LinkText: null,
                        Name: 'Herramientas de Labranza',
                        SecondIcon: '',
                        URL: null,
                        WhenLogged: '1',
                        WhenNotLogged: '1'
                    },
                    {
                        Children: [
                        {
                            HasLink: '0',
                            ID: '19',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Enfardadoras',
                            SecondIcon: '',
                            URL: '/enfardadoras',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '20',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Segadoras',
                            SecondIcon: '',
                            URL: '/segadoras',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '21',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Rotoenfardadoras',
                            SecondIcon: '',
                            URL: '/rotoenfardadoras',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '22',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Picadoras',
                            SecondIcon: '',
                            URL: '/picadoras',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '16',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Rastrillos',
                            SecondIcon: '',
                            URL: '/rastrillos',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '23',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Desmalezadoras',
                            SecondIcon: '',
                            URL: '/desmalezadoras',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '186',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Mixers',
                            SecondIcon: '',
                            URL: '/mixers',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        }
                        ],
                        HasLink: '0',
                        ID: '18',
                        Icon: '',
                        IsNavigable: '0',
                        LinkText: null,
                        Name: 'Equipamiento Forrajero',
                        SecondIcon: '',
                        URL: null,
                        WhenLogged: '1',
                        WhenNotLogged: '1'
                    },
                    {
                        Children: [
                        {
                            HasLink: '0',
                            ID: '101',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Casillas Rurales',
                            SecondIcon: '',
                            URL: '/casillas-rurales',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '26',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Embolsadoras',
                            SecondIcon: '',
                            URL: '/embolsadoras',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '27',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Chimangos',
                            SecondIcon: '',
                            URL: '/chimangos',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '28',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Extractoras',
                            SecondIcon: '',
                            URL: '/extractoras',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '29',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Norias',
                            SecondIcon: '',
                            URL: '/norias',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        }
                        ],
                        HasLink: '0',
                        ID: '24',
                        Icon: '',
                        IsNavigable: '0',
                        LinkText: null,
                        Name: 'Otro Equipamiento',
                        SecondIcon: '',
                        URL: null,
                        WhenLogged: '1',
                        WhenNotLogged: '1'
                    },
                    {
                        Children: [
                        {
                            HasLink: '0',
                            ID: '40',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Tolvas',
                            SecondIcon: '',
                            URL: '/acoplados-tolvas',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '41',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Carros Forrajeros',
                            SecondIcon: '',
                            URL: '/carros-forrajeros-y-compactadores',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '42',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Cargadores de Rollos',
                            SecondIcon: '',
                            URL: '/cargadores-y-transportadores-de-rollos',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        }
                        ],
                        HasLink: '0',
                        ID: '38',
                        Icon: '',
                        IsNavigable: '0',
                        LinkText: null,
                        Name: 'Transporte de Productos',
                        SecondIcon: '',
                        URL: null,
                        WhenLogged: '1',
                        WhenNotLogged: '1'
                    }
                    ],
                    HasLink: '1',
                    ID: '3',
                    Icon: '',
                    IsNavigable: '1',
                    LinkText: 'Todas las Maquinarias Agrícolas',
                    Name: 'Maquinarias Agrícolas',
                    SecondIcon: '',
                    URL: '/maquinaria-agricola',
                    WhenLogged: '1',
                    WhenNotLogged: '1'
                },
                {
                    Children: [
                    {
                        Children: [
                        {
                            HasLink: '0',
                            ID: '31',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Generadores',
                            SecondIcon: '',
                            URL: '/generadores-grupos-electrogenos',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '44',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Moto Soldadoras',
                            SecondIcon: '',
                            URL: '/motosoldadoras',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '45',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Motosierras',
                            SecondIcon: '',
                            URL: '/motosierras',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '46',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Compresores',
                            SecondIcon: '',
                            URL: '/compresores',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '47',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Motoguadañas',
                            SecondIcon: '',
                            URL: '/motoguadanas',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '147',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Hidrolavadoras',
                            SecondIcon: '',
                            URL: '/hidrolavadoras',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '187',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Hoyadoras',
                            SecondIcon: '',
                            URL: '/hoyadoras',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '250',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Cortadoras de Césped',
                            SecondIcon: '',
                            URL: '/cortadoras-de-cesped',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        }
                        ],
                        HasLink: '0',
                        ID: '30',
                        Icon: '',
                        IsNavigable: '1',
                        LinkText: null,
                        Name: 'Herramientas a Motor',
                        SecondIcon: '',
                        URL: '/herramientas-a-motor',
                        WhenLogged: '1',
                        WhenNotLogged: '1'
                    },
                    {
                        Children: [
                        {
                            HasLink: '0',
                            ID: '49',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Banderilleros satelitales',
                            SecondIcon: '',
                            URL: '/banderilleros-satelitales',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '50',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Pilotos automáticos',
                            SecondIcon: '',
                            URL: '/pilotos-automaticos',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '51',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Monitores de siembra',
                            SecondIcon: '',
                            URL: '/monitores-de-siembra',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '52',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Humedímetros',
                            SecondIcon: '',
                            URL: '/humedimetros',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        }
                        ],
                        HasLink: '0',
                        ID: '48',
                        Icon: '',
                        IsNavigable: '1',
                        LinkText: null,
                        Name: 'Agricultura de Precisión',
                        SecondIcon: '',
                        URL: '/agricultura-de-precision',
                        WhenLogged: '1',
                        WhenNotLogged: '1'
                    },
                    {
                        Children: [
                        {
                            HasLink: '0',
                            ID: '54',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Herramientas Manuales',
                            SecondIcon: '',
                            URL: '/herramientas-manuales',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '55',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Otras Herramientas',
                            SecondIcon: '',
                            URL: '/otras-herramientas',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        }
                        ],
                        HasLink: '0',
                        ID: '53',
                        Icon: '',
                        IsNavigable: '0',
                        LinkText: null,
                        Name: 'Más Herramientas',
                        SecondIcon: '',
                        URL: null,
                        WhenLogged: '1',
                        WhenNotLogged: '1'
                    }
                    ],
                    HasLink: '1',
                    ID: '4',
                    Icon: '',
                    IsNavigable: '1',
                    LinkText: 'Todo Herramientas',
                    Name: 'Herramientas',
                    SecondIcon: '',
                    URL: '/herramientas',
                    WhenLogged: '1',
                    WhenNotLogged: '1'
                },
                {
                    Children: [
                    {
                        Children: [
                        {
                            HasLink: '0',
                            ID: '57',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Tanques',
                            SecondIcon: '',
                            URL: '/infraestructura-tanques',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '58',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Silos',
                            SecondIcon: '',
                            URL: '/silos',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '59',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Alambrados',
                            SecondIcon: '',
                            URL: '/alambrados',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '189',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Tranqueras',
                            SecondIcon: '',
                            URL: '/tranqueras',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '60',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Riego y bebida',
                            SecondIcon: '',
                            URL: '/instalaciones-para-riego-y-bebida',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '61',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Balanzas y básculas',
                            SecondIcon: '',
                            URL: '/balanzas-y-basculas',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '161',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Bombas Agrícolas e Industriales',
                            SecondIcon: '',
                            URL: '/bombas',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '164',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Tanques Australianos',
                            SecondIcon: '',
                            URL: '/tanques-australianos',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '188',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Molinos de viento',
                            SecondIcon: '',
                            URL: '/molinos',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        }
                        ],
                        HasLink: '0',
                        ID: '56',
                        Icon: '',
                        IsNavigable: '0',
                        LinkText: null,
                        Name: 'Instalaciones Agroganaderas',
                        SecondIcon: '',
                        URL: null,
                        WhenLogged: '1',
                        WhenNotLogged: '1'
                    },
                    {
                        Children: [
                        {
                            HasLink: '0',
                            ID: '63',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Instalaciones para Ganadería',
                            SecondIcon: '',
                            URL: '/instalaciones-para-ganaderia',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '64',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Instalaciones para Tambos',
                            SecondIcon: '',
                            URL: '/instalaciones-para-tambos',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '65',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Instalaciones para Cerdos',
                            SecondIcon: '',
                            URL: '/instalaciones-para-cerdos',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '66',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Instalaciones para Avicultura',
                            SecondIcon: '',
                            URL: '/instalaciones-para-avicultura',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        }
                        ],
                        HasLink: '0',
                        ID: '62',
                        Icon: '',
                        IsNavigable: '0',
                        LinkText: null,
                        Name: 'Instalaciones por Rubro',
                        SecondIcon: '',
                        URL: null,
                        WhenLogged: '1',
                        WhenNotLogged: '1'
                    },
                    {
                        Children: [
                        {
                            HasLink: '0',
                            ID: '163',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Grupos Electrógenos',
                            SecondIcon: '',
                            URL: '/grupos-electrogenos',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '345',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Paneles Solares',
                            SecondIcon: '',
                            URL: '/paneles-solares',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '346',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Generadores Eólicos',
                            SecondIcon: '',
                            URL: '/generadores-eolicos',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '347',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Otros Generadores de Energía',
                            SecondIcon: '',
                            URL: '/otros-generadores-de-energia',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        }
                        ],
                        HasLink: '0',
                        ID: '162',
                        Icon: '',
                        IsNavigable: '1',
                        LinkText: null,
                        Name: 'Generadores de energía',
                        SecondIcon: '',
                        URL: '/generadores-de-energia',
                        WhenLogged: '1',
                        WhenNotLogged: '1'
                    }
                    ],
                    HasLink: '1',
                    ID: '5',
                    Icon: '',
                    IsNavigable: '1',
                    LinkText: 'Todo Infraestructura',
                    Name: 'Infraestructura',
                    SecondIcon: '',
                    URL: '/infraestructura',
                    WhenLogged: '1',
                    WhenNotLogged: '1'
                },
                {
                    Children: [
                    {
                        Children: [
                        {
                            HasLink: '0',
                            ID: '149',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Palas Cargadoras',
                            SecondIcon: '',
                            URL: '/palas-cargadoras',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '150',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Excavadoras',
                            SecondIcon: '',
                            URL: '/excavadoras',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '151',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Retroexcavadoras',
                            SecondIcon: '',
                            URL: '/retroexcavadora',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '152',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Minicargadoras',
                            SecondIcon: '',
                            URL: '/minicargadoras',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '153',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Palas con Retroexcavadora',
                            SecondIcon: '',
                            URL: '/palas-con-retro',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        }
                        ],
                        HasLink: '0',
                        ID: '148',
                        Icon: '',
                        IsNavigable: '0',
                        LinkText: null,
                        Name: 'Movimiento de Tierra',
                        SecondIcon: '',
                        URL: null,
                        WhenLogged: '1',
                        WhenNotLogged: '1'
                    },
                    {
                        Children: [
                        {
                            HasLink: '0',
                            ID: '155',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Motoniveladoras',
                            SecondIcon: '',
                            URL: '/motoniveladoras',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '156',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Topadoras',
                            SecondIcon: '',
                            URL: '/topadoras',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '157',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Compactadores',
                            SecondIcon: '',
                            URL: '/compactadores',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        }
                        ],
                        HasLink: '0',
                        ID: '154',
                        Icon: '',
                        IsNavigable: '0',
                        LinkText: null,
                        Name: 'Acondicionamiento de suelo',
                        SecondIcon: '',
                        URL: null,
                        WhenLogged: '1',
                        WhenNotLogged: '1'
                    },
                    {
                        Children: [
                        {
                            HasLink: '0',
                            ID: '159',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Autoelevadores',
                            SecondIcon: '',
                            URL: '/autoelevadores',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '160',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Plataformas de elevación',
                            SecondIcon: '',
                            URL: '/plataformas-de-elevacion',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        }
                        ],
                        HasLink: '0',
                        ID: '158',
                        Icon: '',
                        IsNavigable: '0',
                        LinkText: null,
                        Name: 'Otra Maquinaria Pesada',
                        SecondIcon: '',
                        URL: null,
                        WhenLogged: '1',
                        WhenNotLogged: '1'
                    }
                    ],
                    HasLink: '1',
                    ID: '146',
                    Icon: '',
                    IsNavigable: '1',
                    LinkText: 'Toda la Maquinaria Vial',
                    Name: 'Maquinarias Viales',
                    SecondIcon: '',
                    URL: '/maquinaria-vial',
                    WhenLogged: '1',
                    WhenNotLogged: '1'
                },
                {
                    Children: [
                    {
                        Children: [
                        {
                            HasLink: '0',
                            ID: '173',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Daño',
                            SecondIcon: '',
                            URL: '/seguros-integrales-y-todo-riesgo/dano',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '174',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Destrucciones',
                            SecondIcon: '',
                            URL: '/seguros-integrales-y-todo-riesgo/destrucciones',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '175',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Incendio Total',
                            SecondIcon: '',
                            URL: '/seguros-integrales-y-todo-riesgo/incendio-total',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        }
                        ],
                        HasLink: '0',
                        ID: '168',
                        Icon: '',
                        IsNavigable: '1',
                        LinkText: null,
                        Name: 'Integrales y todo riesgo',
                        SecondIcon: '',
                        URL: '/seguros-integrales-y-todo-riesgo',
                        WhenLogged: '1',
                        WhenNotLogged: '1'
                    },
                    {
                        Children: [
                        {
                            HasLink: '0',
                            ID: '276',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Integral',
                            SecondIcon: '',
                            URL: '/seguros-para-empleados-y-personal',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        }
                        ],
                        HasLink: '0',
                        ID: '275',
                        Icon: '',
                        IsNavigable: '0',
                        LinkText: null,
                        Name: 'Empleados y Personal',
                        SecondIcon: '',
                        URL: '/seguros-para-empleados-y-personal',
                        WhenLogged: '1',
                        WhenNotLogged: '1'
                    },
                    {
                        Children: [
                        {
                            HasLink: '0',
                            ID: '176',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Granizo',
                            SecondIcon: '',
                            URL: '/seguros-para-cultivos/granizo',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '177',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Heladas',
                            SecondIcon: '',
                            URL: 'seguros-para-cultivos/heladas',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '178',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Incendio',
                            SecondIcon: '',
                            URL: '/seguros-para-cultivos/incendio',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        }
                        ],
                        HasLink: '0',
                        ID: '169',
                        Icon: '',
                        IsNavigable: '1',
                        LinkText: null,
                        Name: 'Cultivos',
                        SecondIcon: '',
                        URL: '/seguros-para-cultivos',
                        WhenLogged: '1',
                        WhenNotLogged: '1'
                    },
                    {
                        Children: [
                        {
                            HasLink: '0',
                            ID: '180',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Bovinos',
                            SecondIcon: '',
                            URL: '/seguros-para-hacienda/bovinos',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '181',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Equinos',
                            SecondIcon: '',
                            URL: '/seguros-para-hacienda/equinos',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        }
                        ],
                        HasLink: '0',
                        ID: '171',
                        Icon: '',
                        IsNavigable: '1',
                        LinkText: null,
                        Name: 'Hacienda',
                        SecondIcon: '',
                        URL: '/seguros-para-hacienda',
                        WhenLogged: '1',
                        WhenNotLogged: '1'
                    },
                    {
                        Children: [
                        {
                            HasLink: '0',
                            ID: '183',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Maquinaria',
                            SecondIcon: '',
                            URL: '/seguros-para-maquinaria',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '184',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Rodados',
                            SecondIcon: '',
                            URL: '/seguros-para-rodados',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '185',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Silo Bolsas',
                            SecondIcon: '',
                            URL: '/seguros-para-silo-bolsas',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        }
                        ],
                        HasLink: '0',
                        ID: '172',
                        Icon: '',
                        IsNavigable: '1',
                        LinkText: null,
                        Name: 'Patrimonio',
                        SecondIcon: '',
                        URL: '/seguros-para-patrimonio',
                        WhenLogged: '1',
                        WhenNotLogged: '1'
                    }
                    ],
                    HasLink: '0',
                    ID: '167',
                    Icon: '',
                    IsNavigable: '1',
                    LinkText: null,
                    Name: 'Seguros',
                    SecondIcon: '',
                    URL: '/seguros',
                    WhenLogged: '1',
                    WhenNotLogged: '1'
                },
                {
                    Children: [
                    {
                        Children: [
                        {
                            HasLink: '0',
                            ID: '95',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Toyota Hilux',
                            SecondIcon: '',
                            URL: '/camionetas/hilux',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '102',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Volkswagen Amarok',
                            SecondIcon: '',
                            URL: '/camionetas/amarok/volkswagen',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '103',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Ford Ranger',
                            SecondIcon: '',
                            URL: 'camionetas/ford/ranger',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '190',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Campers y Motorhome',
                            SecondIcon: '',
                            URL: '/motorhomes',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        }
                        ],
                        HasLink: '0',
                        ID: '81',
                        Icon: '',
                        IsNavigable: '1',
                        LinkText: null,
                        Name: 'Camionetas',
                        SecondIcon: '',
                        URL: '/camionetas',
                        WhenLogged: '1',
                        WhenNotLogged: '1'
                    },
                    {
                        Children: [
                        {
                            HasLink: '0',
                            ID: '93',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Camiones Nuevos',
                            SecondIcon: '',
                            URL: 'camiones-nuevos',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '94',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Camiones Usados',
                            SecondIcon: '',
                            URL: 'camiones-usados',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        }
                        ],
                        HasLink: '0',
                        ID: '82',
                        Icon: '',
                        IsNavigable: '1',
                        LinkText: null,
                        Name: 'Camiones',
                        SecondIcon: '',
                        URL: '/camiones',
                        WhenLogged: '1',
                        WhenNotLogged: '1'
                    },
                    {
                        Children: [
                        {
                            HasLink: '0',
                            ID: '79',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Autos Nuevos',
                            SecondIcon: '',
                            URL: 'autos-nuevos',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '80',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Autos Usados',
                            SecondIcon: '',
                            URL: 'autos-usados',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        }
                        ],
                        HasLink: '0',
                        ID: '78',
                        Icon: '',
                        IsNavigable: '1',
                        LinkText: null,
                        Name: 'Autos',
                        SecondIcon: '',
                        URL: '/autos',
                        WhenLogged: '1',
                        WhenNotLogged: '1'
                    },
                    {
                        Children: [
                        {
                            HasLink: '0',
                            ID: '85',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Carretones',
                            SecondIcon: '',
                            URL: '/semirremolques-carretones',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '86',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Tolvas',
                            SecondIcon: '',
                            URL: '/semirremolques-tolvas',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '87',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Volcadores',
                            SecondIcon: '',
                            URL: '/semirremolques-volcadores',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '88',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Todos los Semirremolques',
                            SecondIcon: '',
                            URL: '/semiremolques',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        }
                        ],
                        HasLink: '0',
                        ID: '83',
                        Icon: '',
                        IsNavigable: '1',
                        LinkText: null,
                        Name: 'Semirremolques',
                        SecondIcon: '',
                        URL: '/semiremolques',
                        WhenLogged: '1',
                        WhenNotLogged: '1'
                    },
                    {
                        Children: [
                        {
                            HasLink: '0',
                            ID: '89',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Cerealera',
                            SecondIcon: '',
                            URL: '/carroceria-cerealera',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '90',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Volcadora',
                            SecondIcon: '',
                            URL: '/carrocerias-volcadoras',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '91',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Baranda Volcable',
                            SecondIcon: '',
                            URL: '/carrocerias-baranda-volcable',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '92',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Todas las Carrocerías',
                            SecondIcon: '',
                            URL: '/rodados-carrocerias',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        }
                        ],
                        HasLink: '0',
                        ID: '84',
                        Icon: '',
                        IsNavigable: '1',
                        LinkText: null,
                        Name: 'Carrocerías',
                        SecondIcon: '',
                        URL: '/rodados-carrocerias',
                        WhenLogged: '1',
                        WhenNotLogged: '1'
                    },
                    {
                        Children: [
                        {
                            HasLink: '0',
                            ID: '98',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Neumáticos Agrícolas',
                            SecondIcon: '',
                            URL: '/neumaticos-agricolas-y-viales',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '99',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Neumáticos para Autos y Camionetas',
                            SecondIcon: '',
                            URL: '/neumaticos-autos-y-camionetas',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '100',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Todos los Neumáticos',
                            SecondIcon: '',
                            URL: '/neumaticos',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        }
                        ],
                        HasLink: '0',
                        ID: '97',
                        Icon: '',
                        IsNavigable: '1',
                        LinkText: null,
                        Name: 'Neumáticos',
                        SecondIcon: '',
                        URL: '/neumaticos',
                        WhenLogged: '1',
                        WhenNotLogged: '1'
                    },
                    {
                        Children: [
                        {
                            HasLink: '0',
                            ID: '192',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Trailers',
                            SecondIcon: '',
                            URL: '/acoplados-trailer',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '193',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Acoplados Jaula',
                            SecondIcon: '',
                            URL: '/acoplados-jaulas',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '194',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Baranda Volcable',
                            SecondIcon: '',
                            URL: '/acoplados-baranda-volcable',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        }
                        ],
                        HasLink: '0',
                        ID: '191',
                        Icon: '',
                        IsNavigable: '1',
                        LinkText: null,
                        Name: 'Acoplados',
                        SecondIcon: '',
                        URL: '/acoplados',
                        WhenLogged: '1',
                        WhenNotLogged: '1'
                    }
                    ],
                    HasLink: '1',
                    ID: '77',
                    Icon: '',
                    IsNavigable: '1',
                    LinkText: 'Todo Vehículos',
                    Name: 'Vehículos',
                    SecondIcon: '',
                    URL: '/vehiculos',
                    WhenLogged: '1',
                    WhenNotLogged: '1'
                },
                {
                    Children: [
                    {
                        Children: [
                        {
                            HasLink: '0',
                            ID: '326',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'En venta',
                            SecondIcon: '',
                            URL: '/departamentos/venta',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '327',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'En Alquiler',
                            SecondIcon: '',
                            URL: '/departamentos/alquiler',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        }
                        ],
                        HasLink: '0',
                        ID: '313',
                        Icon: '',
                        IsNavigable: '1',
                        LinkText: null,
                        Name: 'Departamentos',
                        SecondIcon: '',
                        URL: '/departamentos',
                        WhenLogged: '1',
                        WhenNotLogged: '1'
                    },
                    {
                        Children: [
                        {
                            HasLink: '0',
                            ID: '329',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: '1 Dormitorio',
                            SecondIcon: '',
                            URL: '/casas/1-dormitorio',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '330',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: '2 Dormitorios',
                            SecondIcon: '',
                            URL: '/casas/2-dormitorios',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '331',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: '3 Dormitorios',
                            SecondIcon: '',
                            URL: '/casas/3-dormitorios',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '332',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: '4 Dormitorios',
                            SecondIcon: '',
                            URL: '/casas/4-dormitorios',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '333',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: '5 Dormitorios o más',
                            SecondIcon: '',
                            URL: '/casas/5-dormitorios-o-mas',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        }
                        ],
                        HasLink: '0',
                        ID: '328',
                        Icon: '',
                        IsNavigable: '1',
                        LinkText: null,
                        Name: 'Casas',
                        SecondIcon: '',
                        URL: '/casas',
                        WhenLogged: '1',
                        WhenNotLogged: '1'
                    },
                    {
                        Children: [
                        {
                            HasLink: '0',
                            ID: '335',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Por inmobiliaria',
                            SecondIcon: '',
                            URL: '/terrenos/inmobiliaria',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '336',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Por particular',
                            SecondIcon: '',
                            URL: '/terrenos/particular',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        }
                        ],
                        HasLink: '0',
                        ID: '334',
                        Icon: '',
                        IsNavigable: '1',
                        LinkText: null,
                        Name: 'Terrenos',
                        SecondIcon: '',
                        URL: '/terrenos',
                        WhenLogged: '1',
                        WhenNotLogged: '1'
                    },
                    {
                        Children: [
                        {
                            HasLink: '0',
                            ID: '338',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'En Buenos Aires',
                            SecondIcon: '',
                            URL: '/casas-de-campo/buenos-aires',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '339',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'En Córdoba',
                            SecondIcon: '',
                            URL: '/casas-de-campo/cordoba',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '340',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'En Entre Ríos',
                            SecondIcon: '',
                            URL: '/casas-de-campo/entre-rios',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        }
                        ],
                        HasLink: '0',
                        ID: '337',
                        Icon: '',
                        IsNavigable: '1',
                        LinkText: null,
                        Name: 'Casas de campo',
                        SecondIcon: '',
                        URL: '/casas-de-campo',
                        WhenLogged: '1',
                        WhenNotLogged: '1'
                    }
                    ],
                    HasLink: '1',
                    ID: '308',
                    Icon: '',
                    IsNavigable: '1',
                    LinkText: 'Todos los Inmuebles',
                    Name: 'Inmuebles',
                    SecondIcon: '',
                    URL: '/inmuebles',
                    WhenLogged: '1',
                    WhenNotLogged: '1'
                },
                {
                    Children: [
                    {
                        Children: [
                        {
                            HasLink: '0',
                            ID: '131',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Menos de 100 Ha',
                            SecondIcon: '',
                            URL: '/campos/superficie_total-0-100',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '121',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Entre 100 y 500 Ha',
                            SecondIcon: '',
                            URL: '/campos/superficie_total-100-500',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '132',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Entre 500 y 1000 Ha',
                            SecondIcon: '',
                            URL: '/campos/superficie_total-500-1000',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '133',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Entre 1000 y 5000 Ha',
                            SecondIcon: '',
                            URL: '/campos/superficie_total-1000-5000',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '122',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Más de 5000 Ha',
                            SecondIcon: '',
                            URL: '/campos/superficie_total-5000-',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        }
                        ],
                        HasLink: '0',
                        ID: '120',
                        Icon: '',
                        IsNavigable: '0',
                        LinkText: null,
                        Name: 'Por Superficie',
                        SecondIcon: '',
                        URL: null,
                        WhenLogged: '1',
                        WhenNotLogged: '1'
                    },
                    {
                        Children: [
                        {
                            HasLink: '0',
                            ID: '124',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Aptitud Agrícola',
                            SecondIcon: '',
                            URL: '/campos-agricolas',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '125',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Aptitud Ganadera',
                            SecondIcon: '',
                            URL: '/campos-ganaderos',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '126',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Aptitud Mixta',
                            SecondIcon: '',
                            URL: '/campos-mixtos',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '130',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Otra Aptitud',
                            SecondIcon: '',
                            URL: '/campos/otra-aptitud',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        }
                        ],
                        HasLink: '0',
                        ID: '123',
                        Icon: '',
                        IsNavigable: '0',
                        LinkText: null,
                        Name: 'Por Aptitud',
                        SecondIcon: '',
                        URL: null,
                        WhenLogged: '1',
                        WhenNotLogged: '1'
                    },
                    {
                        Children: [
                        {
                            HasLink: '0',
                            ID: '135',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Campos en Buenos Aires',
                            SecondIcon: '',
                            URL: '/campos/buenos-aires',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '136',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Campos en Córdoba',
                            SecondIcon: '',
                            URL: '/campos/cordoba',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '139',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Campos en Entre Ríos',
                            SecondIcon: '',
                            URL: '/campos/entre-rios',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '137',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Campos en La Pampa',
                            SecondIcon: '',
                            URL: '/campos/la-pampa',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '138',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Campos en Santa Fe',
                            SecondIcon: '',
                            URL: '/campos/santa-fe',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        }
                        ],
                        HasLink: '0',
                        ID: '134',
                        Icon: '',
                        IsNavigable: '0',
                        LinkText: null,
                        Name: 'Por Ubicación',
                        SecondIcon: '',
                        URL: null,
                        WhenLogged: '1',
                        WhenNotLogged: '1'
                    },
                    {
                        Children: [
                        {
                            HasLink: '0',
                            ID: '128',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Campos en venta',
                            SecondIcon: '',
                            URL: '/campos-en-venta',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '129',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Campos en alquiler',
                            SecondIcon: '',
                            URL: '/campos/alquiler',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        }
                        ],
                        HasLink: '0',
                        ID: '127',
                        Icon: '',
                        IsNavigable: '0',
                        LinkText: null,
                        Name: 'Por Tipo de Operación',
                        SecondIcon: '',
                        URL: null,
                        WhenLogged: '1',
                        WhenNotLogged: '1'
                    }
                    ],
                    HasLink: '1',
                    ID: '104',
                    Icon: '',
                    IsNavigable: '1',
                    LinkText: 'Todos Campos',
                    Name: 'Campos',
                    SecondIcon: '',
                    URL: '/campos',
                    WhenLogged: '1',
                    WhenNotLogged: '1'
                },
                {
                    Children: [
                    {
                        Children: [
                        {
                            HasLink: '0',
                            ID: '202',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Repuestos para Tractores',
                            SecondIcon: '',
                            URL: '/repuestos-para-tractores',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '203',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Repuestos para Cosechadoras',
                            SecondIcon: '',
                            URL: '/repuestos-para-cosechadoras',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '204',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Repuestos para Sembradoras',
                            SecondIcon: '',
                            URL: '/repuestos-para-sembradoras',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '205',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Repuestos para Pulverizadoras',
                            SecondIcon: '',
                            URL: '/repuestos-para-pulverizadoras',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '207',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Repuestos para Maquinaria Vial',
                            SecondIcon: '',
                            URL: '/repuestos-para-maquinaria-vial',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        }
                        ],
                        HasLink: '0',
                        ID: '198',
                        Icon: '',
                        IsNavigable: '0',
                        LinkText: null,
                        Name: 'Repuestos para Maquinaria',
                        SecondIcon: '',
                        URL: null,
                        WhenLogged: '1',
                        WhenNotLogged: '1'
                    },
                    {
                        Children: [
                        {
                            HasLink: '0',
                            ID: '209',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Repuestos para Implementos',
                            SecondIcon: '',
                            URL: '/repuestos-para-implementos',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '210',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Repuestos para Rodados',
                            SecondIcon: '',
                            URL: '/repuestos-para-rodados',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        }
                        ],
                        HasLink: '0',
                        ID: '206',
                        Icon: '',
                        IsNavigable: '1',
                        LinkText: null,
                        Name: 'Otros Repuestos',
                        SecondIcon: '',
                        URL: '/otros-repuestos',
                        WhenLogged: '1',
                        WhenNotLogged: '1'
                    }
                    ],
                    HasLink: '1',
                    ID: '195',
                    Icon: '',
                    IsNavigable: '1',
                    LinkText: 'Todos los Repuestos',
                    Name: 'Repuestos',
                    SecondIcon: '',
                    URL: '/repuestos',
                    WhenLogged: '1',
                    WhenNotLogged: '1'
                },
                {
                    Children: [
                    {
                        Children: [
                        {
                            HasLink: '1',
                            ID: '281',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Créditos para Campos',
                            SecondIcon: '',
                            URL: '/creditos-para-campos',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '1',
                            ID: '282',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Créditos para Insumos',
                            SecondIcon: '',
                            URL: '/creditos-para-insumos',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '1',
                            ID: '283',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Créditos para Maquinaria',
                            SecondIcon: '',
                            URL: '/creditos-para-maquinaria',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '1',
                            ID: '284',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Créditos para Rodados',
                            SecondIcon: '',
                            URL: '/creditos-para-rodados',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '1',
                            ID: '285',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Créditos para Inmuebles',
                            SecondIcon: '',
                            URL: '/creditos-para-inmuebles',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        }
                        ],
                        HasLink: '1',
                        ID: '280',
                        Icon: '',
                        IsNavigable: '1',
                        LinkText: null,
                        Name: 'Créditos',
                        SecondIcon: '',
                        URL: '/creditos',
                        WhenLogged: '1',
                        WhenNotLogged: '1'
                    },
                    {
                        Children: [
                        {
                            HasLink: '1',
                            ID: '287',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Leasing 48 meses',
                            SecondIcon: '',
                            URL: '/leasing-de-maquinaria/48-meses',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '1',
                            ID: '288',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Leasing 60 meses',
                            SecondIcon: '',
                            URL: '/leasing-de-maquinaria/60-meses',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '1',
                            ID: '289',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Leasing 61 meses',
                            SecondIcon: '',
                            URL: '/leasing-de-maquinaria/61-meses',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        }
                        ],
                        HasLink: '1',
                        ID: '286',
                        Icon: '',
                        IsNavigable: '1',
                        LinkText: null,
                        Name: 'Leasing de Maquinaria',
                        SecondIcon: '',
                        URL: '/leasing-de-maquinaria',
                        WhenLogged: '1',
                        WhenNotLogged: '1'
                    },
                    {
                        Children: [
                        {
                            HasLink: '1',
                            ID: '291',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Convenios para Insumos',
                            SecondIcon: '',
                            URL: '/convenios-para-insumos',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '1',
                            ID: '292',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Convenios para Maquinaria',
                            SecondIcon: '',
                            URL: '/convenios-para-maquinaria',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        }
                        ],
                        HasLink: '1',
                        ID: '290',
                        Icon: '',
                        IsNavigable: '1',
                        LinkText: null,
                        Name: 'Tarjetas',
                        SecondIcon: '',
                        URL: '/tarjetas',
                        WhenLogged: '1',
                        WhenNotLogged: '1'
                    }
                    ],
                    HasLink: '1',
                    ID: '279',
                    Icon: '',
                    IsNavigable: '1',
                    LinkText: 'Todo Créditos y Financiación',
                    Name: 'Créditos y Financiación',
                    SecondIcon: '',
                    URL: '/home-creditos-y-financiacion',
                    WhenLogged: '1',
                    WhenNotLogged: '1'
                },
                {
                    HasLink: '1',
                    ID: '342',
                    Icon: '',
                    IsNavigable: '1',
                    LinkText: null,
                    Name: 'Servicios',
                    SecondIcon: '',
                    URL: '/servicios',
                    WhenLogged: '1',
                    WhenNotLogged: '1'
                },
                {
                    HasLink: '1',
                    ID: '341',
                    Icon: '',
                    IsNavigable: '1',
                    LinkText: null,
                    Name: 'Formación',
                    SecondIcon: '',
                    URL: '/formacion',
                    WhenLogged: '1',
                    WhenNotLogged: '1'
                },
                {
                    HasLink: '0',
                    ID: '2',
                    Icon: 'https://argentina.agrofystatic.com/media/item/image/s/p/sprite-sucursales.png',
                    IsNavigable: '1',
                    LinkText: null,
                    Name: 'Sucursales Online',
                    SecondIcon: '',
                    URL: '/sucursales-online',
                    WhenLogged: '1',
                    WhenNotLogged: '1'
                }
                ],
                mobile: [
                {
                    HasLink: '0',
                    ID: '248',
                    Icon: 'https://argentina.agrofystatic.com/media/item/image/m/i/mi_cuenta_ingresar.svg',
                    IsNavigable: '1',
                    LinkText: null,
                    Name: 'Ingresar',
                    SecondIcon: '',
                    URL: '/customer/account/login/index',
                    WhenLogged: '0',
                    WhenNotLogged: '1'
                },
                {
                    Children: [
                    {
                        HasLink: '0',
                        ID: '273',
                        Icon: '',
                        IsNavigable: '1',
                        LinkText: null,
                        Name: 'Resumen',
                        SecondIcon: '',
                        URL: '/myaccount/#/dashboard',
                        WhenLogged: '1',
                        WhenNotLogged: '0'
                    },
                    {
                        HasLink: '0',
                        ID: '256',
                        Icon: '',
                        IsNavigable: '0',
                        LinkText: null,
                        Name: 'VENTAS',
                        SecondIcon: '',
                        URL: null,
                        WhenLogged: '1',
                        WhenNotLogged: '0'
                    },
                    {
                        HasLink: '0',
                        ID: '302',
                        Icon: 'https://argentina.agrofystatic.com/media/item/image/m/i/mi_cuenta_ventas.svg',
                        IsNavigable: '1',
                        LinkText: null,
                        Name: 'Mis Ventas',
                        SecondIcon: '',
                        URL: '/myaccount/#/sales',
                        WhenLogged: '1',
                        WhenNotLogged: '0'
                    },
                    {
                        HasLink: '0',
                        ID: '261',
                        Icon: 'https://argentina.agrofystatic.com/media/item/image/m/i/mi_cuenta_consultas.svg',
                        IsNavigable: '1',
                        LinkText: null,
                        Name: 'Consultas Recibidas',
                        SecondIcon: '',
                        URL: '/myaccount/#/received',
                        WhenLogged: '1',
                        WhenNotLogged: '0'
                    },
                    {
                        HasLink: '0',
                        ID: '294',
                        Icon: 'https://argentina.agrofystatic.com/media/item/image/m/i/mi_cuenta_cotizaciones.svg',
                        IsNavigable: '1',
                        LinkText: null,
                        Name: 'Cotizaciones Recibidas',
                        SecondIcon: '',
                        URL: '/myaccount/#/quotations/received',
                        WhenLogged: '1',
                        WhenNotLogged: '0'
                    },
                    {
                        HasLink: '0',
                        ID: '257',
                        Icon: '',
                        IsNavigable: '0',
                        LinkText: null,
                        Name: 'MIS PUBLICACIONES',
                        SecondIcon: '',
                        URL: null,
                        WhenLogged: '1',
                        WhenNotLogged: '0'
                    },
                    {
                        HasLink: '0',
                        ID: '262',
                        Icon: '',
                        IsNavigable: '1',
                        LinkText: null,
                        Name: 'Activas',
                        SecondIcon: '',
                        URL: '/idscustomer/account_misventas_misavisos/activos',
                        WhenLogged: '1',
                        WhenNotLogged: '0'
                    },
                    {
                        HasLink: '0',
                        ID: '263',
                        Icon: '',
                        IsNavigable: '1',
                        LinkText: null,
                        Name: 'Pendientes',
                        SecondIcon: '',
                        URL: '/idscustomer/account_misventas_misavisos/pendientes/',
                        WhenLogged: '1',
                        WhenNotLogged: '0'
                    },
                    {
                        HasLink: '0',
                        ID: '264',
                        Icon: '',
                        IsNavigable: '1',
                        LinkText: null,
                        Name: 'Inactivas',
                        SecondIcon: '',
                        URL: '/idscustomer/account_misventas_misavisos/inactivos/',
                        WhenLogged: '1',
                        WhenNotLogged: '0'
                    },
                    {
                        HasLink: '0',
                        ID: '258',
                        Icon: '',
                        IsNavigable: '0',
                        LinkText: null,
                        Name: 'COMPRAS',
                        SecondIcon: '',
                        URL: null,
                        WhenLogged: '1',
                        WhenNotLogged: '0'
                    },
                    {
                        HasLink: '0',
                        ID: '303',
                        Icon: 'https://argentina.agrofystatic.com/media/item/image/m/i/mi_cuenta_compras.svg',
                        IsNavigable: '1',
                        LinkText: null,
                        Name: 'Mis Compras',
                        SecondIcon: '',
                        URL: '/myaccount/#/purchases',
                        WhenLogged: '1',
                        WhenNotLogged: '0'
                    },
                    {
                        HasLink: '0',
                        ID: '265',
                        Icon: 'https://argentina.agrofystatic.com/media/item/image/m/i/mi_cuenta_consultas.svg',
                        IsNavigable: '1',
                        LinkText: null,
                        Name: 'Consultas Enviadas',
                        SecondIcon: '',
                        URL: '/myaccount/#/sent',
                        WhenLogged: '1',
                        WhenNotLogged: '0'
                    },
                    {
                        HasLink: '0',
                        ID: '295',
                        Icon: 'https://argentina.agrofystatic.com/media/item/image/m/i/mi_cuenta_cotizaciones.svg',
                        IsNavigable: '1',
                        LinkText: null,
                        Name: 'Cotizaciones Enviadas',
                        SecondIcon: '',
                        URL: '/myaccount/#/quotations/sent',
                        WhenLogged: '1',
                        WhenNotLogged: '0'
                    },
                    {
                        HasLink: '0',
                        ID: '266',
                        Icon: 'https://argentina.agrofystatic.com/media/item/image/m/i/mi_cuenta_mis_favoritos.svg',
                        IsNavigable: '1',
                        LinkText: null,
                        Name: 'Mis Favoritos',
                        SecondIcon: '',
                        URL: '/wishlist',
                        WhenLogged: '1',
                        WhenNotLogged: '0'
                    },
                    {
                        HasLink: '0',
                        ID: '259',
                        Icon: '',
                        IsNavigable: '0',
                        LinkText: null,
                        Name: 'MIS DATOS',
                        SecondIcon: '',
                        URL: null,
                        WhenLogged: '1',
                        WhenNotLogged: '0'
                    },
                    {
                        HasLink: '0',
                        ID: '272',
                        Icon: '',
                        IsNavigable: '1',
                        LinkText: null,
                        Name: 'Datos de la Empresa',
                        SecondIcon: '',
                        URL: '/myaccount/#/edit-company',
                        WhenLogged: '1',
                        WhenNotLogged: '0'
                    },
                    {
                        HasLink: '0',
                        ID: '268',
                        Icon: '',
                        IsNavigable: '1',
                        LinkText: null,
                        Name: 'Datos del Contacto',
                        SecondIcon: '',
                        URL: '/myaccount/#/edit-contact',
                        WhenLogged: '1',
                        WhenNotLogged: '0'
                    },
                    {
                        HasLink: '0',
                        ID: '260',
                        Icon: '',
                        IsNavigable: '0',
                        LinkText: null,
                        Name: 'CONFIGURACIÓN',
                        SecondIcon: '',
                        URL: null,
                        WhenLogged: '1',
                        WhenNotLogged: '0'
                    },
                    {
                        HasLink: '0',
                        ID: '270',
                        Icon: 'https://argentina.agrofystatic.com/media/item/image/m/i/mi_cuenta_suscripciones.svg',
                        IsNavigable: '1',
                        LinkText: null,
                        Name: 'Suscripciones',
                        SecondIcon: '',
                        URL: '/seguiragroshop/seguiragroshop/misnotificaciones',
                        WhenLogged: '1',
                        WhenNotLogged: '0'
                    },
                    {
                        HasLink: '0',
                        ID: '274',
                        Icon: '',
                        IsNavigable: '1',
                        LinkText: null,
                        Name: 'Cerrar Sesión',
                        SecondIcon: '',
                        URL: '/customer/account/logout/',
                        WhenLogged: '1',
                        WhenNotLogged: '0'
                    }
                    ],
                    HasLink: '0',
                    ID: '255',
                    Icon: 'https://argentina.agrofystatic.com/media/item/image/m/i/mi_cuenta_ingresar.svg',
                    IsNavigable: '0',
                    LinkText: null,
                    Name: 'Mi Cuenta',
                    SecondIcon: '',
                    URL: null,
                    WhenLogged: '1',
                    WhenNotLogged: '0'
                },
                {
                    Children: [
                    {
                        Children: [
                        {
                            Children: [],
                            HasLink: '0',
                            ID: '113',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Semillas e Híbridos',
                            SecondIcon: '',
                            URL: '/semillas',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            Children: [],
                            HasLink: '0',
                            ID: '106',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Protección de Cultivos',
                            SecondIcon: '',
                            URL: '/proteccion-de-cultivos',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            Children: [],
                            HasLink: '0',
                            ID: '115',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Fertilizantes',
                            SecondIcon: '',
                            URL: '/fertilizantes',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '143',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Inoculantes',
                            SecondIcon: '',
                            URL: '/inoculantes',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '145',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Silo Bolsas',
                            SecondIcon: '',
                            URL: '/silo-bolsas',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        }
                        ],
                        HasLink: '1',
                        ID: '105',
                        Icon: '',
                        IsNavigable: '1',
                        LinkText: 'Todo Insumos Agrícolas',
                        Name: 'Insumos Agrícolas',
                        SecondIcon: 'https://project-e.agrofy.com/media/item/image/n/u/nueva_17.png',
                        URL: '/insumos-agricolas',
                        WhenLogged: '1',
                        WhenNotLogged: '1'
                    },
                    {
                        Children: [
                        {
                            Children: [
                            {
                                HasLink: '1',
                                ID: '297',
                                Icon: '',
                                IsNavigable: '1',
                                LinkText: null,
                                Name: 'Antibióticos',
                                SecondIcon: '',
                                URL: '/insumos-veterinarios/antibioticos',
                                WhenLogged: '1',
                                WhenNotLogged: '1'
                            },
                            {
                                HasLink: '1',
                                ID: '298',
                                Icon: '',
                                IsNavigable: '1',
                                LinkText: null,
                                Name: 'Antiparasitarios',
                                SecondIcon: '',
                                URL: '/insumos-veterinarios/antiparasitarios',
                                WhenLogged: '1',
                                WhenNotLogged: '1'
                            },
                            {
                                HasLink: '1',
                                ID: '299',
                                Icon: '',
                                IsNavigable: '1',
                                LinkText: null,
                                Name: 'Antiinflamatorios',
                                SecondIcon: '',
                                URL: '/insumos-veterinarios/antiinflamatorios',
                                WhenLogged: '1',
                                WhenNotLogged: '1'
                            },
                            {
                                HasLink: '1',
                                ID: '300',
                                Icon: '',
                                IsNavigable: '1',
                                LinkText: null,
                                Name: 'Hormonales',
                                SecondIcon: '',
                                URL: '/insumos-veterinarios/hormonales',
                                WhenLogged: '1',
                                WhenNotLogged: '1'
                            },
                            {
                                HasLink: '1',
                                ID: '301',
                                Icon: '',
                                IsNavigable: '1',
                                LinkText: null,
                                Name: 'Vitaminas y Minerales',
                                SecondIcon: '',
                                URL: '/insumos-veterinarios/vitaminas-y-minerales',
                                WhenLogged: '1',
                                WhenNotLogged: '1'
                            }
                            ],
                            HasLink: '0',
                            ID: '296',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Insumos Veterinarios',
                            SecondIcon: '',
                            URL: '/insumos-veterinarios',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            Children: [
                            {
                                HasLink: '0',
                                ID: '305',
                                Icon: '',
                                IsNavigable: '1',
                                LinkText: null,
                                Name: 'Alimentos Balanceados',
                                SecondIcon: '',
                                URL: '/alimentos-balanceados',
                                WhenLogged: '1',
                                WhenNotLogged: '1'
                            },
                            {
                                HasLink: '0',
                                ID: '306',
                                Icon: '',
                                IsNavigable: '1',
                                LinkText: null,
                                Name: 'Alimentos Concentrados',
                                SecondIcon: '',
                                URL: '/alimentos_concentrados',
                                WhenLogged: '1',
                                WhenNotLogged: '1'
                            },
                            {
                                HasLink: '0',
                                ID: '307',
                                Icon: '',
                                IsNavigable: '1',
                                LinkText: null,
                                Name: 'Subproductos Industriales',
                                SecondIcon: '',
                                URL: '/subproductos-industriales',
                                WhenLogged: '1',
                                WhenNotLogged: '1'
                            },
                            {
                                HasLink: '0',
                                ID: '343',
                                Icon: '',
                                IsNavigable: '1',
                                LinkText: null,
                                Name: 'Forrajes Conservados',
                                SecondIcon: '',
                                URL: '/forrajes-conservados',
                                WhenLogged: '1',
                                WhenNotLogged: '1'
                            },
                            {
                                HasLink: '0',
                                ID: '344',
                                Icon: '',
                                IsNavigable: '1',
                                LinkText: null,
                                Name: 'Núcleos, Correctores y Suplementos',
                                SecondIcon: '',
                                URL: '/correctores',
                                WhenLogged: '1',
                                WhenNotLogged: '1'
                            }
                            ],
                            HasLink: '0',
                            ID: '304',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Nutrición Animal',
                            SecondIcon: '',
                            URL: '/nutricion-animal',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            Children: [
                            {
                                HasLink: '0',
                                ID: '320',
                                Icon: '',
                                IsNavigable: '1',
                                LinkText: null,
                                Name: 'Bovinos de Carne',
                                SecondIcon: '',
                                URL: '/bovinos-de-carne',
                                WhenLogged: '1',
                                WhenNotLogged: '1'
                            }
                            ],
                            HasLink: '0',
                            ID: '319',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Reproducción y Genética',
                            SecondIcon: '',
                            URL: '/reproduccion-y-genetica',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        }
                        ],
                        HasLink: '1',
                        ID: '318',
                        Icon: '',
                        IsNavigable: '1',
                        LinkText: 'Todo Insumos para Ganadería',
                        Name: 'Insumos para Ganadería',
                        SecondIcon: '',
                        URL: '/insumos-para-ganaderia',
                        WhenLogged: '1',
                        WhenNotLogged: '1'
                    },
                    {
                        Children: [
                        {
                            HasLink: '0',
                            ID: '7',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Tractores',
                            SecondIcon: '',
                            URL: '/tractores',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '8',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Pulverizadoras',
                            SecondIcon: '',
                            URL: '/pulverizadoras',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '68',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Sembradoras',
                            SecondIcon: '',
                            URL: '/sembradoras',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '9',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Cosechadoras',
                            SecondIcon: '',
                            URL: '/cosechadoras',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '119',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Fertilizadoras',
                            SecondIcon: '',
                            URL: '/fertilizadoras',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '69',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Plataformas y Cabezales',
                            SecondIcon: '',
                            URL: '/plataformas-y-cabezales',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '101',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Casillas Rurales',
                            SecondIcon: '',
                            URL: '/casillas-rurales',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '40',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Tolvas',
                            SecondIcon: '',
                            URL: '/acoplados-tolvas',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        }
                        ],
                        HasLink: '1',
                        ID: '3',
                        Icon: '',
                        IsNavigable: '1',
                        LinkText: 'Todas las Maquinarias Agrícolas',
                        Name: 'Maquinarias Agrícolas',
                        SecondIcon: 'https://project-e.agrofy.com/media/item/image/n/u/nueva_17.png',
                        URL: '/maquinaria-agricola',
                        WhenLogged: '1',
                        WhenNotLogged: '1'
                    },
                    {
                        Children: [
                        {
                            Children: [],
                            HasLink: '0',
                            ID: '30',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Herramientas a Motor',
                            SecondIcon: '',
                            URL: '/herramientas-a-motor',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            Children: [],
                            HasLink: '0',
                            ID: '48',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Agricultura de Precisión',
                            SecondIcon: '',
                            URL: '/agricultura-de-precision',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '54',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Herramientas Manuales',
                            SecondIcon: '',
                            URL: '/herramientas-manuales',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '55',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Otras Herramientas',
                            SecondIcon: '',
                            URL: '/otras-herramientas',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        }
                        ],
                        HasLink: '1',
                        ID: '4',
                        Icon: '',
                        IsNavigable: '0',
                        LinkText: 'Todo Herramientas',
                        Name: 'Herramientas',
                        SecondIcon: '',
                        URL: '/herramientas',
                        WhenLogged: '1',
                        WhenNotLogged: '1'
                    },
                    {
                        Children: [
                        {
                            HasLink: '0',
                            ID: '57',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Tanques',
                            SecondIcon: '',
                            URL: '/infraestructura-tanques',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '58',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Silos',
                            SecondIcon: '',
                            URL: '/silos',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '59',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Alambrados',
                            SecondIcon: '',
                            URL: '/alambrados',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '189',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Tranqueras',
                            SecondIcon: '',
                            URL: '/tranqueras',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '60',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Riego y bebida',
                            SecondIcon: '',
                            URL: '/instalaciones-para-riego-y-bebida',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '61',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Balanzas y básculas',
                            SecondIcon: '',
                            URL: '/balanzas-y-basculas',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '63',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Instalaciones para Ganadería',
                            SecondIcon: '',
                            URL: '/instalaciones-para-ganaderia',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        }
                        ],
                        HasLink: '1',
                        ID: '5',
                        Icon: '',
                        IsNavigable: '0',
                        LinkText: 'Todo Infraestructura',
                        Name: 'Infraestructura',
                        SecondIcon: '',
                        URL: '/infraestructura',
                        WhenLogged: '1',
                        WhenNotLogged: '1'
                    },
                    {
                        Children: [
                        {
                            HasLink: '0',
                            ID: '149',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Palas Cargadoras',
                            SecondIcon: '',
                            URL: '/palas-cargadoras',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '150',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Excavadoras',
                            SecondIcon: '',
                            URL: '/excavadoras',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '151',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Retroexcavadoras',
                            SecondIcon: '',
                            URL: '/retroexcavadora',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '152',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Minicargadoras',
                            SecondIcon: '',
                            URL: '/minicargadoras',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '153',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Palas con Retroexcavadora',
                            SecondIcon: '',
                            URL: '/palas-con-retro',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '155',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Motoniveladoras',
                            SecondIcon: '',
                            URL: '/motoniveladoras',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '156',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Topadoras',
                            SecondIcon: '',
                            URL: '/topadoras',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '157',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Compactadores',
                            SecondIcon: '',
                            URL: '/compactadores',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '159',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Autoelevadores',
                            SecondIcon: '',
                            URL: '/autoelevadores',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '160',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Plataformas de elevación',
                            SecondIcon: '',
                            URL: '/plataformas-de-elevacion',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        }
                        ],
                        HasLink: '1',
                        ID: '146',
                        Icon: '',
                        IsNavigable: '0',
                        LinkText: 'Toda la Maquinaria Vial',
                        Name: 'Maquinarias Viales',
                        SecondIcon: '',
                        URL: '/maquinaria-vial',
                        WhenLogged: '1',
                        WhenNotLogged: '1'
                    },
                    {
                        Children: [
                        {
                            Children: [],
                            HasLink: '0',
                            ID: '275',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Empleados y Personal',
                            SecondIcon: '',
                            URL: '/seguros-para-empleados-y-personal',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            Children: [],
                            HasLink: '0',
                            ID: '169',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Cultivos',
                            SecondIcon: '',
                            URL: '/seguros-para-cultivos',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            Children: [],
                            HasLink: '0',
                            ID: '171',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Hacienda',
                            SecondIcon: '',
                            URL: '/seguros-para-hacienda',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            Children: [],
                            HasLink: '0',
                            ID: '172',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Patrimonio',
                            SecondIcon: '',
                            URL: '/seguros-para-patrimonio',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        }
                        ],
                        HasLink: '0',
                        ID: '167',
                        Icon: '',
                        IsNavigable: '0',
                        LinkText: null,
                        Name: 'Seguros',
                        SecondIcon: '',
                        URL: '/seguros',
                        WhenLogged: '1',
                        WhenNotLogged: '1'
                    },
                    {
                        Children: [
                        {
                            Children: [],
                            HasLink: '0',
                            ID: '81',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Camionetas',
                            SecondIcon: '',
                            URL: '/camionetas',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            Children: [],
                            HasLink: '0',
                            ID: '82',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Camiones',
                            SecondIcon: '',
                            URL: '/camiones',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            Children: [],
                            HasLink: '0',
                            ID: '78',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Autos',
                            SecondIcon: '',
                            URL: '/autos',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            Children: [],
                            HasLink: '0',
                            ID: '83',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Semirremolques',
                            SecondIcon: '',
                            URL: '/semiremolques',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            Children: [],
                            HasLink: '0',
                            ID: '84',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Carrocerías',
                            SecondIcon: '',
                            URL: '/rodados-carrocerias',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            Children: [],
                            HasLink: '0',
                            ID: '97',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Neumáticos',
                            SecondIcon: '',
                            URL: '/neumaticos',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        }
                        ],
                        HasLink: '1',
                        ID: '77',
                        Icon: '',
                        IsNavigable: '0',
                        LinkText: 'Todo Vehículos',
                        Name: 'Vehículos',
                        SecondIcon: '',
                        URL: '/vehiculos',
                        WhenLogged: '1',
                        WhenNotLogged: '1'
                    },
                    {
                        Children: [
                        {
                            Children: [
                            {
                                HasLink: '0',
                                ID: '326',
                                Icon: '',
                                IsNavigable: '1',
                                LinkText: null,
                                Name: 'En venta',
                                SecondIcon: '',
                                URL: '/departamentos/venta',
                                WhenLogged: '1',
                                WhenNotLogged: '1'
                            },
                            {
                                HasLink: '0',
                                ID: '327',
                                Icon: '',
                                IsNavigable: '1',
                                LinkText: null,
                                Name: 'En Alquiler',
                                SecondIcon: '',
                                URL: '/departamentos/alquiler',
                                WhenLogged: '1',
                                WhenNotLogged: '1'
                            }
                            ],
                            HasLink: '0',
                            ID: '313',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Departamentos',
                            SecondIcon: '',
                            URL: '/departamentos',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            Children: [
                            {
                                HasLink: '0',
                                ID: '329',
                                Icon: '',
                                IsNavigable: '1',
                                LinkText: null,
                                Name: '1 Dormitorio',
                                SecondIcon: '',
                                URL: '/casas/1-dormitorio',
                                WhenLogged: '1',
                                WhenNotLogged: '1'
                            },
                            {
                                HasLink: '0',
                                ID: '330',
                                Icon: '',
                                IsNavigable: '1',
                                LinkText: null,
                                Name: '2 Dormitorios',
                                SecondIcon: '',
                                URL: '/casas/2-dormitorios',
                                WhenLogged: '1',
                                WhenNotLogged: '1'
                            },
                            {
                                HasLink: '0',
                                ID: '331',
                                Icon: '',
                                IsNavigable: '1',
                                LinkText: null,
                                Name: '3 Dormitorios',
                                SecondIcon: '',
                                URL: '/casas/3-dormitorios',
                                WhenLogged: '1',
                                WhenNotLogged: '1'
                            },
                            {
                                HasLink: '0',
                                ID: '332',
                                Icon: '',
                                IsNavigable: '1',
                                LinkText: null,
                                Name: '4 Dormitorios',
                                SecondIcon: '',
                                URL: '/casas/4-dormitorios',
                                WhenLogged: '1',
                                WhenNotLogged: '1'
                            },
                            {
                                HasLink: '0',
                                ID: '333',
                                Icon: '',
                                IsNavigable: '1',
                                LinkText: null,
                                Name: '5 Dormitorios o más',
                                SecondIcon: '',
                                URL: '/casas/5-dormitorios-o-mas',
                                WhenLogged: '1',
                                WhenNotLogged: '1'
                            }
                            ],
                            HasLink: '0',
                            ID: '328',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Casas',
                            SecondIcon: '',
                            URL: '/casas',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            Children: [
                            {
                                HasLink: '0',
                                ID: '335',
                                Icon: '',
                                IsNavigable: '1',
                                LinkText: null,
                                Name: 'Por inmobiliaria',
                                SecondIcon: '',
                                URL: '/terrenos/inmobiliaria',
                                WhenLogged: '1',
                                WhenNotLogged: '1'
                            },
                            {
                                HasLink: '0',
                                ID: '336',
                                Icon: '',
                                IsNavigable: '1',
                                LinkText: null,
                                Name: 'Por particular',
                                SecondIcon: '',
                                URL: '/terrenos/particular',
                                WhenLogged: '1',
                                WhenNotLogged: '1'
                            }
                            ],
                            HasLink: '0',
                            ID: '334',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Terrenos',
                            SecondIcon: '',
                            URL: '/terrenos',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            Children: [
                            {
                                HasLink: '0',
                                ID: '338',
                                Icon: '',
                                IsNavigable: '1',
                                LinkText: null,
                                Name: 'En Buenos Aires',
                                SecondIcon: '',
                                URL: '/casas-de-campo/buenos-aires',
                                WhenLogged: '1',
                                WhenNotLogged: '1'
                            },
                            {
                                HasLink: '0',
                                ID: '339',
                                Icon: '',
                                IsNavigable: '1',
                                LinkText: null,
                                Name: 'En Córdoba',
                                SecondIcon: '',
                                URL: '/casas-de-campo/cordoba',
                                WhenLogged: '1',
                                WhenNotLogged: '1'
                            },
                            {
                                HasLink: '0',
                                ID: '340',
                                Icon: '',
                                IsNavigable: '1',
                                LinkText: null,
                                Name: 'En Entre Ríos',
                                SecondIcon: '',
                                URL: '/casas-de-campo/entre-rios',
                                WhenLogged: '1',
                                WhenNotLogged: '1'
                            }
                            ],
                            HasLink: '0',
                            ID: '337',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Casas de campo',
                            SecondIcon: '',
                            URL: '/casas-de-campo',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        }
                        ],
                        HasLink: '1',
                        ID: '308',
                        Icon: '',
                        IsNavigable: '1',
                        LinkText: 'Todos los Inmuebles',
                        Name: 'Inmuebles',
                        SecondIcon: '',
                        URL: '/inmuebles',
                        WhenLogged: '1',
                        WhenNotLogged: '1'
                    },
                    {
                        Children: [
                        {
                            HasLink: '0',
                            ID: '131',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Menos de 100 Ha',
                            SecondIcon: '',
                            URL: '/campos/superficie_total-0-100',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '121',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Entre 100 y 500 Ha',
                            SecondIcon: '',
                            URL: '/campos/superficie_total-100-500',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '132',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Entre 500 y 1000 Ha',
                            SecondIcon: '',
                            URL: '/campos/superficie_total-500-1000',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '133',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Entre 1000 y 5000 Ha',
                            SecondIcon: '',
                            URL: '/campos/superficie_total-1000-5000',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '122',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Más de 5000 Ha',
                            SecondIcon: '',
                            URL: '/campos/superficie_total-5000-',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '124',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Aptitud Agrícola',
                            SecondIcon: '',
                            URL: '/campos-agricolas',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '125',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Aptitud Ganadera',
                            SecondIcon: '',
                            URL: '/campos-ganaderos',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '126',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Aptitud Mixta',
                            SecondIcon: '',
                            URL: '/campos-mixtos',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '130',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Otra Aptitud',
                            SecondIcon: '',
                            URL: '/campos/otra-aptitud',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '135',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Campos en Buenos Aires',
                            SecondIcon: '',
                            URL: '/campos/buenos-aires',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '136',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Campos en Córdoba',
                            SecondIcon: '',
                            URL: '/campos/cordoba',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '139',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Campos en Entre Ríos',
                            SecondIcon: '',
                            URL: '/campos/entre-rios',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '137',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Campos en La Pampa',
                            SecondIcon: '',
                            URL: '/campos/la-pampa',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '138',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Campos en Santa Fe',
                            SecondIcon: '',
                            URL: '/campos/santa-fe',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '128',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Campos en venta',
                            SecondIcon: '',
                            URL: '/campos-en-venta',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '129',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Campos en alquiler',
                            SecondIcon: '',
                            URL: '/campos/alquiler',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        }
                        ],
                        HasLink: '1',
                        ID: '104',
                        Icon: '',
                        IsNavigable: '0',
                        LinkText: 'Todos Campos',
                        Name: 'Campos',
                        SecondIcon: '',
                        URL: '/campos',
                        WhenLogged: '1',
                        WhenNotLogged: '1'
                    },
                    {
                        Children: [
                        {
                            HasLink: '0',
                            ID: '202',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Repuestos para Tractores',
                            SecondIcon: '',
                            URL: '/repuestos-para-tractores',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '203',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Repuestos para Cosechadoras',
                            SecondIcon: '',
                            URL: '/repuestos-para-cosechadoras',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '204',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Repuestos para Sembradoras',
                            SecondIcon: '',
                            URL: '/repuestos-para-sembradoras',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '205',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Repuestos para Pulverizadoras',
                            SecondIcon: '',
                            URL: '/repuestos-para-pulverizadoras',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            HasLink: '0',
                            ID: '207',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Repuestos para Maquinaria Vial',
                            SecondIcon: '',
                            URL: '/repuestos-para-maquinaria-vial',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            Children: [
                            {
                                HasLink: '0',
                                ID: '209',
                                Icon: '',
                                IsNavigable: '1',
                                LinkText: null,
                                Name: 'Repuestos para Implementos',
                                SecondIcon: '',
                                URL: '/repuestos-para-implementos',
                                WhenLogged: '1',
                                WhenNotLogged: '1'
                            },
                            {
                                HasLink: '0',
                                ID: '210',
                                Icon: '',
                                IsNavigable: '1',
                                LinkText: null,
                                Name: 'Repuestos para Rodados',
                                SecondIcon: '',
                                URL: '/repuestos-para-rodados',
                                WhenLogged: '1',
                                WhenNotLogged: '1'
                            }
                            ],
                            HasLink: '0',
                            ID: '206',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Otros Repuestos',
                            SecondIcon: '',
                            URL: '/otros-repuestos',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        }
                        ],
                        HasLink: '1',
                        ID: '195',
                        Icon: '',
                        IsNavigable: '0',
                        LinkText: 'Todos los Repuestos',
                        Name: 'Repuestos',
                        SecondIcon: '',
                        URL: '/repuestos',
                        WhenLogged: '1',
                        WhenNotLogged: '1'
                    },
                    {
                        Children: [
                        {
                            Children: [
                            {
                                HasLink: '1',
                                ID: '281',
                                Icon: '',
                                IsNavigable: '1',
                                LinkText: null,
                                Name: 'Créditos para Campos',
                                SecondIcon: '',
                                URL: '/creditos-para-campos',
                                WhenLogged: '1',
                                WhenNotLogged: '1'
                            },
                            {
                                HasLink: '1',
                                ID: '282',
                                Icon: '',
                                IsNavigable: '1',
                                LinkText: null,
                                Name: 'Créditos para Insumos',
                                SecondIcon: '',
                                URL: '/creditos-para-insumos',
                                WhenLogged: '1',
                                WhenNotLogged: '1'
                            },
                            {
                                HasLink: '1',
                                ID: '283',
                                Icon: '',
                                IsNavigable: '1',
                                LinkText: null,
                                Name: 'Créditos para Maquinaria',
                                SecondIcon: '',
                                URL: '/creditos-para-maquinaria',
                                WhenLogged: '1',
                                WhenNotLogged: '1'
                            },
                            {
                                HasLink: '1',
                                ID: '284',
                                Icon: '',
                                IsNavigable: '1',
                                LinkText: null,
                                Name: 'Créditos para Rodados',
                                SecondIcon: '',
                                URL: '/creditos-para-rodados',
                                WhenLogged: '1',
                                WhenNotLogged: '1'
                            },
                            {
                                HasLink: '1',
                                ID: '285',
                                Icon: '',
                                IsNavigable: '1',
                                LinkText: null,
                                Name: 'Créditos para Inmuebles',
                                SecondIcon: '',
                                URL: '/creditos-para-inmuebles',
                                WhenLogged: '1',
                                WhenNotLogged: '1'
                            }
                            ],
                            HasLink: '1',
                            ID: '280',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Créditos',
                            SecondIcon: '',
                            URL: '/creditos',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            Children: [
                            {
                                HasLink: '1',
                                ID: '287',
                                Icon: '',
                                IsNavigable: '1',
                                LinkText: null,
                                Name: 'Leasing 48 meses',
                                SecondIcon: '',
                                URL: '/leasing-de-maquinaria/48-meses',
                                WhenLogged: '1',
                                WhenNotLogged: '1'
                            },
                            {
                                HasLink: '1',
                                ID: '288',
                                Icon: '',
                                IsNavigable: '1',
                                LinkText: null,
                                Name: 'Leasing 60 meses',
                                SecondIcon: '',
                                URL: '/leasing-de-maquinaria/60-meses',
                                WhenLogged: '1',
                                WhenNotLogged: '1'
                            },
                            {
                                HasLink: '1',
                                ID: '289',
                                Icon: '',
                                IsNavigable: '1',
                                LinkText: null,
                                Name: 'Leasing 61 meses',
                                SecondIcon: '',
                                URL: '/leasing-de-maquinaria/61-meses',
                                WhenLogged: '1',
                                WhenNotLogged: '1'
                            }
                            ],
                            HasLink: '1',
                            ID: '286',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Leasing de Maquinaria',
                            SecondIcon: '',
                            URL: '/leasing-de-maquinaria',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        },
                        {
                            Children: [
                            {
                                HasLink: '1',
                                ID: '291',
                                Icon: '',
                                IsNavigable: '1',
                                LinkText: null,
                                Name: 'Convenios para Insumos',
                                SecondIcon: '',
                                URL: '/convenios-para-insumos',
                                WhenLogged: '1',
                                WhenNotLogged: '1'
                            },
                            {
                                HasLink: '1',
                                ID: '292',
                                Icon: '',
                                IsNavigable: '1',
                                LinkText: null,
                                Name: 'Convenios para Maquinaria',
                                SecondIcon: '',
                                URL: '/convenios-para-maquinaria',
                                WhenLogged: '1',
                                WhenNotLogged: '1'
                            }
                            ],
                            HasLink: '1',
                            ID: '290',
                            Icon: '',
                            IsNavigable: '1',
                            LinkText: null,
                            Name: 'Tarjetas',
                            SecondIcon: '',
                            URL: '/tarjetas',
                            WhenLogged: '1',
                            WhenNotLogged: '1'
                        }
                        ],
                        HasLink: '1',
                        ID: '279',
                        Icon: '',
                        IsNavigable: '1',
                        LinkText: 'Todo Créditos y Financiación',
                        Name: 'Créditos y Financiación',
                        SecondIcon: '',
                        URL: '/home-creditos-y-financiacion',
                        WhenLogged: '1',
                        WhenNotLogged: '1'
                    },
                    {
                        HasLink: '1',
                        ID: '342',
                        Icon: '',
                        IsNavigable: '1',
                        LinkText: null,
                        Name: 'Servicios',
                        SecondIcon: '',
                        URL: '/servicios',
                        WhenLogged: '1',
                        WhenNotLogged: '1'
                    },
                    {
                        HasLink: '1',
                        ID: '341',
                        Icon: '',
                        IsNavigable: '1',
                        LinkText: null,
                        Name: 'Formación',
                        SecondIcon: '',
                        URL: '/formacion',
                        WhenLogged: '1',
                        WhenNotLogged: '1'
                    }
                    ],
                    HasLink: '0',
                    ID: '249',
                    Icon: 'https://argentina.agrofystatic.com/media/item/image/m/i/mi_cuenta_categorias.svg',
                    IsNavigable: '0',
                    LinkText: null,
                    Name: 'Categorías',
                    SecondIcon: '',
                    URL: null,
                    WhenLogged: '1',
                    WhenNotLogged: '1'
                },
                {
                    HasLink: '0',
                    ID: '251',
                    Icon: 'https://argentina.agrofystatic.com/media/item/image/m/i/mi_cuenta_sucursales_onlines.svg',
                    IsNavigable: '1',
                    LinkText: null,
                    Name: 'Sucursales Online',
                    SecondIcon: '',
                    URL: '/sucursales-online',
                    WhenLogged: '1',
                    WhenNotLogged: '1'
                },
                {
                    HasLink: '0',
                    ID: '252',
                    Icon: 'https://argentina.agrofystatic.com/media/item/image/m/i/mi_cuenta_ofertas_destacadas.svg',
                    IsNavigable: '1',
                    LinkText: null,
                    Name: 'Ofertas Destacadas',
                    SecondIcon: '',
                    URL: '/ofertas-destacadas',
                    WhenLogged: '1',
                    WhenNotLogged: '1'
                },
                {
                    HasLink: '0',
                    ID: '253',
                    Icon: 'https://argentina.agrofystatic.com/media/item/image/m/i/mi_cuenta_noticias_agro.svg',
                    IsNavigable: '1',
                    LinkText: null,
                    Name: 'Noticias del Agro',
                    SecondIcon: '',
                    URL: 'https://news.agrofy.com.ar/',
                    WhenLogged: '1',
                    WhenNotLogged: '1'
                },
                {
                    HasLink: '0',
                    ID: '254',
                    Icon: 'https://argentina.agrofystatic.com/media/item/image/m/i/mi_cuenta_vender_agrofy.svg',
                    IsNavigable: '1',
                    LinkText: null,
                    Name: 'Vender en Agrofy',
                    SecondIcon: '',
                    URL: '/aviso/onepage/index/',
                    WhenLogged: '1',
                    WhenNotLogged: '1'
                },
                {
                    HasLink: '0',
                    ID: '271',
                    Icon: '',
                    IsNavigable: '1',
                    LinkText: null,
                    Name: 'Cerrar Sesión',
                    SecondIcon: '',
                    URL: '/customer/account/logout/',
                    WhenLogged: '1',
                    WhenNotLogged: '0'
                }
                ]
            },        
            userData: {
                    agroshop: {
                    logo: 'https://s3.amazonaws.com/static.project-e.agrofy.com/media/catalog/agroshop/amauta-agrofy-logo.png',
                    name: 'Amauta',
                    url: '/amauta'
                    },
                    cuit: '30710639392',
                    email: 'relisei+4095@agrofy.com',
                    fullName: 'Fernando Manfredi',
                    id: '63155',
                    isLogged: true,
                    name: 'Fernando'
                }
            }
    }
}
</script>