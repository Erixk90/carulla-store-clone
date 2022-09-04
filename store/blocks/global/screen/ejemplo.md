/*{

    "store.home": {
        "blocks": [
            "rich-text#welcome",
            /*"rich-text#subtitle",
            "rich-text#paragrahp",
            "rich-text#linked",*/
            "info-card",
            "info-card#secondary",
            "flex-layout.row",
            "slider-layout#home",
            "image#dudalo",
            "slider-layout#homefinal"

        ]
    },

    /*Ejemplo info card*/
    "info-card#2ejemplo": {
        "props": {
            "imageUrl": "https://images.unsplash.com/photo-1524185962737-ea7c028a12cd?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80",
            "isFullModeStyle": false,
            "headline": "Black Friday",
            "callToActionText": "Subscribe",
            "textPosition": "center",
            "height": "100%"
        }
    },
    /* Rich Text  ejemplo de titulo*/
    "rich-text#welcome": {
        "props": {
            "text": "Mi propio titulo",
            "textAlignment": "CENTER",
            "textPosition": "CENTER",
            "font": "t-heading-1"
        }
    },

    /* Rich Text  ejemplo de subtitulo*/
    "rich-text#subtitle": {
        "props": {
            "text": "Este es el subtitulo del parrafo",
            "textAlignment": "RIGTH",
            "font": "t-heading-1"
        }
    },

    /* Rich Text  ejemplo de parrafo*/
    "rich-text#paragrahp": {
        "props": {
            "text": "**este parrafo se encaraga de hacer una simulación de los diferentes parrafos que tiene un articulo**, este parrafo se encaraga de hacer una simulación de los diferentes parrafos que tiene un articulo , este parrafo se encaraga de hacer una simulación de los diferentes parrafos que tiene un articulo, este parrafo se encaraga de hacer una simulación de los diferentes parrafos que tiene un articulo, este parrafo se encaraga de hacer una simulación de los diferentes parrafos que tiene un articulo, este parrafo se encaraga de hacer una simulación de los diferentes parrafos que tiene un articulo",
            "blockClass": "paragrap"
        }
    },

    /* Imagen ejemplo */
    "image#welcome": {
        "props": {
            "src": "assets/img/header.jpg",
            "max-width": 600,
            "title": "Banner principal"
        }
    },

    /* Rich Text  ejemplo de link*/
    "rich-text#linked": {
        "props": {
            "textAlignment": "CENTER",
            "textPosition": "CENTER",
            "text": "Visit our [help](https://developers.vtex.com/vtex-developer-docs/docs/welcome) section.\n**Be Bold!**\n*This is italic*",
            "textColor": "c-on-emphasis",
            "font": "t-heading-5",
            "blockClass": "help-message"
        }
    },

    /* info-card ejemplo imagen ilustrativa*/
    "info-card": {
        "props": {
            "id": "info-card-example",
            "isFullModeStyle": false,
            "textPosition": "left",
            "imageUrl": "https://storecomponents.vteximg.com.br/arquivos/banner-infocard2.png",
            "headline": "Clearance Sale",
            "callToActionText": "DISCOVER",
            "callToActionUrl": "/sale/d",
            "blockClass": "info-card-example",
            "textAlignment": "center"
        }
    },
    /* info-card ejemplo imagen ilustrativa*/
    "info-card#secondary": {
        "props": {
            "isFullModeStyle": false,
            "textPosition": "right",
            "imageUrl": "assets/img/header.jpg",
            "headline": "Vintage Pink",
            "subhead": "Give your kitchen a boho style adding vintage apparels.<br>Available until January 2020.",
            "callToActionMode": "button",
            "callToActionText": "Explore",
            "callToActionUrl": "#",
            "textAlignment": "center"
        }
    },

    /* flex-layout row ejemplo de imagenes como vitrinas*/
    "flex-layout.row": {
        "children": [
            "info-card#rethink",
            "flex-layout.col"
        ]
    },

    "info-card#rethink": {
        "props": {
            "imageUrl": "https://appliancetheme.vteximg.com.br/arquivos/utensilios-cozinha-min.png",
            "isFullModeStyle": true,
            "headline": "Time to rethink your kitchen",
            "callToActionText": "Discover",
            "textPosition": "center"
        }
    },

    "flex-layout.col": {
        "children": [
            "image#electronics",
            "image#major-appliance"
        ]
    },


    "image#electronics": {
        "props": {
            "src": "https://appliancetheme.vteximg.com.br/assets/vtex.file-manager-graphql/images/electronics_banner___25d69b49f8224b369375e68513b4d593.png",
            "maxWidth": "100%"
        }
    },
    "image#major-appliance": {
        "props": {
            "src": "https://appliancetheme.vteximg.com.br/assets/vtex.file-manager-graphql/images/major_appliance_banner___bb10093866a127345ddfbcca3efa5022.png",
            "maxWidth": "100%"
        }
    },

    "slider-layout#home": {
        "children": ["info-card#1", "info-card#2"],
        "props": {
            "autoplay": {
                "timeout": 2000,
                "stopOnHover": true
            }
        }
    },

    "info-card#1": {
        "props": {
            "imageUrl": "https://images.unsplash.com/photo-1524185962737-ea7c028a12cd?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80",
            "isFullModeStyle": true,
            "headline": "Black Friday",
            "callToActionText": "Subscribe",
            "textPosition": "center"
        }
    },

    "info-card#2": {
        "props": {
            "imageUrl": "https://images.unsplash.com/photo-1524185962737-ea7c028a12cd?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80",
            "isFullModeStyle": true,
            "headline": "Black Friday",
            "callToActionText": "Subscribe",
            "textPosition": "center"
        }
    },

    "image#dudalo": {
        "props": {
            "src": "https://storecomponents.vteximg.com.br/arquivos/box.png",
            "maxHeight": 240
        }
    },

    "slider-layout#homefinal": {
        "children": ["image#brand1", "image#brand2", "image#brand3", "image#brand4", "image#brand5", "image#brand6"],
        "props": {
            "autoplay": {
                "timeout": 1000,
                "stopOnHover": false
            },
            "itemsPerPage": {
                "desktop": 3,
                "tablet": 1,
                "phone": 1
            },
            "infinite": true,
            "showNavigationArrows": "always",
            "blockClass": "carousel",
            "centerMode": "center"


        }
    },

    "image#brand1": {
        "props": {
            "src": "https://appliancetheme.vteximg.com.br/arquivos/flatflat-brand-logo-square1.png",
            "maxHeight": 240
        }
    },

    "image#brand2": {
        "props": {
            "src": "https://appliancetheme.vteximg.com.br/arquivos/flatflat-brand-logo-square2.png",
            "maxHeight": 240
        }
    },
    "image#brand3": {
        "props": {
            "src": "https://appliancetheme.vteximg.com.br/arquivos/flatflat-brand-logo-square3.png",
            "maxHeight": 240
        }
    },
    "image#brand4": {
        "props": {
            "src": "https://appliancetheme.vteximg.com.br/arquivos/flatflat-brand-logo-square4.png",
            "maxHeight": 240
        }
    },
    "image#brand5": {
        "props": {
            "src": "https://appliancetheme.vteximg.com.br/arquivos/flatflat-brand-logo-square5.png",
            "maxHeight": 240
        }
    },
    "image#brand6": {
        "props": {
            "src": "https://appliancetheme.vteximg.com.br/arquivos/flatflat-brand-logo-square6.png",
            "maxHeight": 240
        }
    },

    /* header */

    {
    "header": {
    "title": "Header",
    "blocks": ["header-layout.desktop",
      "header-layout.mobile"
    ]
  },
  "header.full": {
    "title": "Header",
    "blocks": ["header-layout.desktop",
      "header-layout.mobile"
    ]},

  "header-layout.desktop": {
    "children": [
      "header-row"
      /*,
           "header-row#2-desktop",
           "header-row#3-desktop",
           "header-row#4-desktop"*/
  /*
    ]
  },
  "rich-text#header":{
    "props": {
      "text": "Mi propio titulo"
  }},

  "header-layout.mobile": {
    "children": [
      "rich-text#header2"]},

      "rich-text#header2":{
        "props": {
          "text": "Mi propio titulo mobile"
      }},

  "header-row#1-desktop": {
    "children": [
      "rich-text",
      "image#header__top-logo"
    ]
  },

  "image#header__top-logo": {
    "title": "sucio",
    "props": {
      "src": "assets/img/logo.png",
      "width": 150
    }
  }

   "header.full": {
     "blocks": ["header-layout.desktop", "header-layout.mobile"]
   },
   "header-layout.desktop": {
     "children": [
       "sticky-layout#desktop"
     ]
   },
   "sticky-layout#desktop": {
     "props": {
       "blockClass": "sticky-header"
     },
     "children": ["flex-layout.row#desktop"]
   },
   "flex-layout.row#desktop": {
     "props": {
       "horizontalAlign": "center",
       "verticalAlign": "center",
       "preventHorizontalStretch": true,
       "preventVerticalStretch": true,
       "fullWidth": true
     },
     "children": [
       "flex-layout.col#logo-desktop",
       "flex-layout.col#spacer",
       "search-bar",
       "locale-switcher",
       "login",
       "minicart.v2"
     ]
   },
   "flex-layout.col#spacer": {
     "props": {
       "width": "grow"
     }
   },
   "flex-layout.col#logo-desktop": {
     "props": {
       "verticalAlign": "middle"
     },
     "children": ["logo"]
   },
   "logo": {
     "props": {
       "title": "Logo",
       "src": "assets/img/logo.jpg",
       "width": "80"
     }
   },
   "header-layout.mobile": {
     "children": ["sticky-layout#mobile"]
   },
   "sticky-layout#mobile": {
     "children": ["flex-layout.row#mobile"]
   },
   "flex-layout.row#mobile": {
     "children": [
       "drawer",
       "logo",
       "flex-layout.col#spacer",
       "login",
       "minicart.v2"
     ],
     "props": {
       "blockClass": "main-header-mobile",
       "preventHorizontalStretch": true,
       "preserveLayoutOnMobile": true,
       "fullWidth": true
     }
   },
   "drawer": {
     "children": []
   } */


   /-------------------------footer------------------------/

   

  "flex-layout.col#footer__container-group-two":{
    "children": [
      "menu#help"
    ]
  },

  "flex-layout.col#footer__container-group-three":{
    "children": [
      "menu#help"
    ]
  },

  "footer-layout.mobile": {
    "children": [
      "disclosure-layout-group#footer__menu-group"
    ]
  },

  "disclosure-layout-group#footer__menu-group": {

    "children": [
      "flex-layout.row#footer"
      /*,
      "disclosure-layout#policies"*/
    ]
  },

  "flex-layout.row#footer": {
    "children": ["disclosure-layout#help",
      "disclosure-layout#interestinfo"
    ]
  },

  "disclosure-layout#help": {
    "children": [
      "disclosure-trigger#help",
      "disclosure-content#help"
    ]
  },

  "disclosure-trigger#help": {
    "children": [
      "rich-text#help"
    ]
  },

  "rich-text#help": {
    "props": {
      "text": "Centro de Ayuda"
    }
  },


  "disclosure-content#help": {
    "children": [
      "menu#help"
    ]
  },

  "menu#help": {
    "children": [
      "menu-item#help-one",
      "menu-item#help-two"
    ],
    "props": {
      "orientation": "vertical"
    }
  },

  "menu-item#help-one": {
    "props": {
      "id": "menu-help-one",
      "type": "custom",
      "itemProps": {
        "type": "internal",
        "href": "#",
        "tagTitle": "Términos y condiciones",
        "text": "Términos y condiciones"
      }
    }
  },

  "menu-item#help-two": {
    "props": {
      "id": "menu-help-two",
      "type": "custom",
      "itemProps": {
        "type": "internal",
        "href": "#",
        "tagTitle": "Centro de ayuda",
        "text": "Centro de ayuda"
      }
    }
  },

  /*Next disclosure*/
  "disclosure-layout#interestinfo": {
    "children": [
      "disclosure-trigger#interestinfo",
      "disclosure-content#interestinfo"
    ]
  },

  "disclosure-trigger#interestinfo": {
    "children": [
      "rich-text#interestinfo"
    ]
  },

  "rich-text#interestinfo": {
    "props": {
      "text": "Información de Interes"
    }
  },

  "disclosure-content#interestinfo": {
    "children": [
      "menu#interestinfo"
    ]
  },

  "menu#interestinfo": {
    "children": [
      "menu-item#interestinfo-one",
      "menu-item#interestinfo-two"
    ],
    "props": {
      "orientation": "vertical"
    }
  },

  "menu-item#interestinfo-one": {
    "props": {
      "id": "menu-interestinfo-one",
      "type": "custom",
      "itemProps": {
        "type": "internal",
        "href": "#",
        "tagTitle": "Términos y condiciones",
        "text": "Términos y condiciones"
      }
    }
  },

  "menu-item#interestinfo-two": {
    "props": {
      "id": "menu-interestinfo-two",
      "type": "custom",
      "itemProps": {
        "type": "internal",
        "href": "#",
        "tagTitle": "Centro de ayuda",
        "text": "Centro de ayuda"
      }
    }
  },

  "social-networks": {
    "props": {
      "socialNetworks": [
        { "url": "https://facebook.com/foo", "name": "Facebook" },
        { "url": "https://twitter.com/foo", "name": "Twitter" }
      ]
    }
  },
  "accepted-payment-methods": {
    "props": {
      "paymentMethods": ["mastercard", "visa", "diners club"]
    }
  }
  /*
  "flex-layout.row#footer": { 
    "children": [
      "image"
    ]
  },
  "image": {
    "props": {
      "width": 100,
      "src": "https://brand.vtex.com/static/media/VTEX_pink_RGB.751a9fb5.svg"
    }
  } */




  
    /*Search Results etse TOCA COLOCARLO OBLIGATORIO
    traemos contexto para poder agregar a una pagina que no lo tiene como es el home*/ 

  },
  "search-result-layout.customQuery#home-search": {
    "blocks": [
      "search-result-layout.desktop#home__search-desktop",
      "search-result-layout.mobile#home__search-mobile",
      "search-not-found-layout"
    ],
    "props": {
      "querySchema": {
        "skusFilter": "ALL",
        "simulationBehavior": "skip"
      }
    }
  },

  "search-result-layout.desktop#home__search-desktop": {
    "children": [
      
      
      "flex-layout.row#home__results"/*,
      "flex-layout.row#searchtitle",
      "flex-layout.row#result"
    */
    ],
    "props": {
      "preventRouteChange": true
    }
  },

  "flex-layout.row#home__results":{
    "children": [
      "flex-layout.col#home__results-search"
    
    ]
  },
  "flex-layout.col#home__results-filter":{
    "props":{
      "width": "100%"
    }},

    "flex-layout.col#home__results-search":{
      "props":{
        "width": "70%"
    },
    "children": [
      "search-content#home__results-search"
    ]},

    "search-content#home__results-search":{
      "blocks":[
        "gallery", "not-found"]
      },

      "gallery":{
        "blocks":[
          "product-summary.shelf"
        ]
      },

  "search-result-layout.mobile#home__search-mobile":{
     
  }
}


/* Footer de  viernes en la noche  */ 

{
  "footer": {
    "title": "Footer",
    "blocks": [
      "footer-layout.desktop",
      "footer-layout.mobile"
    ]
  },
  "footer-layout.desktop#nada": {
    "children": [
      "disclosure-layout-group#footer__menu-group" 
    ]
  },

  "disclosure-layout-group#footer__menu-group":{
    "children": [
      "disclosure-layout-group#footer__menu-group",


      "flex-layout.col#footer__container",
      "social-networks",
      "accepted-payment-methods"
    ]
  },

  "flex-layout.col#footer__container":{
    "children": [
    "flex-layout.row#footer__container-top-footer"/*,
    "flex-layout.row#footer__container-middle-footer",
    "flex-layout.row#footer__container-info-footer",
    "flex-layout.row#footer__container-allies-footer"*/

  ]},

  "flex-layout.row#footer__container-top-footer":{
    "children": [
      "flex-layout.col#top__footer-productos",
      "flex-layout.col#top__footer-compras",
      "flex-layout.col#top__footer-puntos",
      "flex-layout.col#top__footer-pagos"
    ]
  },

  "flex-layout.col#top__footer-productos":{
    "children":[
      "icon#top__footer-productos",
      "rich-text#top__footer-productos"
    ]
  },
  "icon#top__footer-productos": {
    "props": {
        "id": "mpa-location-input",
        "size": 20
    }
  },
  "rich-text#top__footer-productos": {
    "props": {
        "text": " ¿Como quieres recibir tu pedido?",
        "color": "c-on-emphasys",
        "blockClass": "header__top-paragraph"
    }
  },

"flex-layout.col#top__footer-compras":{
  "children":[
    "icon#top__footer-productos",
    "rich-text#top__footer-productos"
  ]
},

"flex-layout.col#top__footer-puntos":{
  "children":[
    "icon#top__footer-productos",
    "rich-text#top__footer-productos"
  ]
},

"flex-layout.col#top__footer-pagos":{
  "children":[
    "icon#top__footer-productos",
    "rich-text#top__footer-productos"
  ]
},

/*ejemplo*/

"footer-layout.desktop": {
  "children": [
    "flex-layout.row#footer-desktop"
  ]
},
"footer-layout.mobile": {
  "children": [
    "flex-layout.row#footer-mobile"
  ]
},
"flex-layout.row#footer-desktop": {
  "children": [
    "social-networks",
    "accepted-payment-methods",
    "powered-by"
  ]
},
"flex-layout.row#footer-mobile": {
  "children": [
    "social-networks",
    "accepted-payment-methods",
    "powered-by"
  ]
},
"social-networks": {
  "props": {
    "socialNetworks": [
      { "url": "https://facebook.com/foo", "name": "Facebook" },
      { "url": "https://twitter.com/foo", "name": "Twitter" }
    ]
  }
},
"accepted-payment-methods": {
  "props": {
    "paymentMethods": ["mastercard", "visa", "diners club"]
  }
}
}