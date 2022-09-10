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



/*disclosure*/


  "disclosure-layout#simple": {
    "children": [
      "disclosure-trigger#simple",
       "disclosure-content#simple"
      ]
  },
  "disclosure-trigger#simple": {
    "children": [
      "rich-text#question"
    ]
  },
  "disclosure-content#simple": {
    "children": [
      "rich-text#answer"
    ]
  },
  "rich-text#question": {
    "props": {
      "text": "How can I change my shipping address?"
    }
  },
  "rich-text#answer": {
    "props": {
      "text": "Call us at the number (212) 1234-1234"
    }
  },

  /*Disclosure group*/
  "flex-layout.row#footer__desktop-middle":{
    "children":[
      "flex-layout.col#footer__desktop-middle"
  ]
  },
  "flex-layout.col#footer__desktop-middle":{
    "children":[
    "disclosure-layout-group#group__desktop"
  ]
  },

  "disclosure-layout-group#group__desktop": {
    "children": [
      
      "disclosure-layout#first",
       "disclosure-layout#second",
       "disclosure-layout#third"
      ]
  },

  "flex-layout.row#disclosure__desktop": {
    "children": [
      "disclosure-layout-group#group__desktop"
      
      ]
  },

  "disclosure-layout#first": {
    "children": [
      "disclosure-trigger#first",
       "disclosure-content#first"
      ]
  },
  "disclosure-trigger#first": {
    "children": [
      "rich-text#question1"
    ],
    "props":{
      "as":"p"
    }
  },
  "disclosure-content#first": {
    "children": [
      "rich-text#answer1",
      "rich-text#answer1",
      "rich-text#answer1",
      "rich-text#answer1"

    ]
  },
  "rich-text#question1": {
    "props": {
      "text": "esto deberia ser un p"
    }
  },


  "rich-text#answer1": {
    "props": {
      "text": "respuesta 1"
    }
  },

  "disclosure-layout#second": {
    "children": [
      "disclosure-trigger#first",
       "disclosure-content#first"
      ]
  },
  "disclosure-trigger#second": {
    "children": [
      "rich-text#question1"
  ]
  },
  "disclosure-content#second": {
    "children": [
      "rich-text#answer1",
      "rich-text#answer1",
      "rich-text#answer1"
    ]
  },
  "rich-text#question2": {
    "props": {
      "text": "How can I track my order?"
    }
  },
  "rich-text#answer2": {
    "props": {
      "text": "After logging into your account, you can find this info at the link Orders."
    }
  },
  "disclosure-layout#third":{
  "children": [
    "disclosure-trigger#first",
     "disclosure-content#first"
    ]},
  //-----------------Start one footer column Second group


  //-----------------End one footer column Second group
  "footer-layout.mobile": {
    "children": [
      "flex-layout.row#footer-mobile"
    ]
  },
  "flex-layout.row#footer-mobile": {
    "children": [
      "social-networks",
      "accepted-payment-methods"
    ]
  }
}


--------------------------------------------------------------------------------
"flex-layout.row#footer__desktop-middle": {
    "children": [
      "flex-layout.row#footer__desktop-middle1"
    ]
    
  },
  "flex-layout.row#footer__desktop-middle1": {
    "children": [
      "flex-layout.col#footer__desktop-container-one",
      "flex-layout.row#footer__desktop-container-two"
    ]
  },
  "flex-layout.col#footer__desktop-container-one": {
    "children": [
      "disclosure-layout#information__desktop"
    ],
    "props": {
      " horizontalAlign": "center"
    }
  },
  "flex-layout.row#footer__desktop-container-two": {},
  "disclosure-layout#information__desktop": {
    "children": [
      "disclosure-trigger#information",
      "disclosure-content#information"
    ]
  },
  "disclosure-trigger#information": {
    "children": [
      "flex-layout.row#text__information"
    ],
    "props": {
      "as": "h4"
    }
  },
  "flex-layout.row#text__information": {
    "children": [
      "rich-text#information"
    ]
  },
  "rich-text#information": {
    "props": {
      "text": "Más Información",
      "textAlignment": "CENTER",
      "textPosition": "CENTER"
    }
  },
  "disclosure-content#information": {
    "children": [
      //"flex-layout.col#footer__desktop-container-two-a"
      "disclosure-layout-group#group-one__desktop"
    ],
    "props":{
      "blockClass": "disclosure__information"
    }
  },
  "flex-layout.row#footer__desktop-container-two-a": {  //isn't work
    "children": [
      "flex-layout.row#container__two-group-one"
    ],
    "props":{
      "blockClass": "footer__desktop-container-two-a"
    }
  },
  "flex-layout.row#container__two-group-one": {
    "children": [
      "disclosure-layout-group#group-one__desktop"
    ],
    "props":{
      "blockClass": "container__two-group-one"
    }
  },
  "disclosure-layout-group#group-one__desktop": {
    "children": [
      "disclosure-layout#first",
      "disclosure-layout#first",
      "disclosure-layout#first"
    ],
    "props":{
      "blockClass": "disclosure__group-one__desktop"
    }
  },
  "disclosure-layout#first": {
    "children": [
      "flex-layout.row#disclosure__firts-container"
    ],
    "props":{
      "blockClass": "disclosure__layout-first"
    }
  },
  "flex-layout.row#disclosure__firts-container": {
    "children": [
      "flex-layout.row#disclosure__firts1-container"
    ],
    "props":{
      "blockClass": "disclosure__firts-container"
    }
  },
  "flex-layout.row#disclosure__firts1-container": {
    "children": [
      "disclosure-trigger#first",
      "disclosure-content#first"
    ]
  },
  "disclosure-trigger#first": {
    "children": [
      "rich-text#question1"
    ],
    "props": {
      "as": "h3"
    }
  },
  "disclosure-content#first": {
    "children": [
      "rich-text#answer1",
      "rich-text#answer2",
      "rich-text#answer3",
      "rich-text#answer4",
      "rich-text#answer5"
    ]
  },
  "rich-text#question1": {
    "props": {
      "text": "Centro de Ayuda"
    }
  },
  "rich-text#answer1": {
    "props": {
      "text": "[Chat](https://api.whatsapp.com/send?phone=573052614467&text=Hola,+quiero+realizar+una+compra&utm_source=Webchat&utm_medium=Webchat_Carulla&utm_campaign=Webchat_Carulla&utm_id=232901)"
    }
  },
  "rich-text#answer2": {
    "props": {
      "text": "[Preguntas Frecuentes](/preguntas-frecuentes)"
    }
  },
  "rich-text#answer3": {
    "props": {
      "text": "[Política de cambio y devoluciones](https://www.carulla.com/politicas-cambios-devoluciones)"
    }
  },
  "rich-text#answer4": {
    "props": {
      "text": "[Contacto](https://www.carulla.com/contacto)"
    }
  },
  "rich-text#answer5": {
    "props": {
      "text": "[Almacenes](https://www.carulla.com/almacenes)"
    }
  }

  --------------------menú sin mega menu--------------
  
    /* lo anulo porque  quise cambiar al mega-menu
    "drawer": {
        "children": [
            "vtex.menu@2.x:menu#drawer"
        ]
    },
    "vtex.menu@2.x:menu#drawer": {
        "children": [
            "rich-text#head-menu",
            "menu-item#category-eventos",
            "menu-item#category-lanzamientos",
            "rich-text#body-menu-text",
            "rich-text#body-menu-line",
            "menu-item#category-vinos",
            "menu-item#category-bebidas",
            "menu-item#category-delicatessen",
            "menu-item#category-panaderia",
            "menu-item#category-pollo",
            "menu-item#category-frutas",
            "menu-item#category-despensa",
            "menu-item#category-lacteos",
            "menu-item#category-preparados",
            "menu-item#category-congelados",
            "menu-item#category-limpieza",
            "menu-item#category-salud",
            "menu-item#category-electrodomesticos",
            "menu-item#category-tecnologia",
            "menu-item#category-moda",
            "menu-item#category-hogar",
            "menu-item#category-deporte",
            "menu-item#category-otros",
            "menu-item#category-cocina" /*,
         "rich-text#footer-menu",
          "rich-text#footer-menu",
          "rich-text#footer-menu"
        ],
        "props": {
            "orientation": "vertical"
        }
    },
    */
    "rich-text#head-menu": {
        "props": {
            "text": "Lo Ultimo"
        }
    },
    /*firts category example  with mega menu  and icons*/
    "menu-item#category-eventos": {
        "props": {
            "id": "menu-item-eventos",
            "type": "custom",
            "highlight": false,
            "itemProps": {
                "type": "internal",
                "href": "/",
                "noFollow": false,
                "tagTitle": "Eventos del mes",
                "text": "Eventos del mes"
            },
            "iconProps": {
                "id": "mpa-play",
                "size": 16,
                "viewBox": "0 0 16 16",
                "activeClassName": "",
                "mutedClassName": "c-action-primary"
            },
            "onMountBehavior": "open"
        },
        "blocks": [
            "vtex.menu@2.x:submenu.accordion#departments-eventos"
        ]
    },
    /* first category submenu */
    "vtex.menu@2.x:submenu.accordion#departments-eventos": {
        "children": [
            "vtex.menu@2.x:menu#department__one-eventos"
        ]
    },
    "vtex.menu@2.x:menu#department__one-eventos": {
        "children": [
            "menu-item#category__one-eventos",
            "menu-item#category__two-eventos"
        ],
        "props": {
            "orientation": "vertical"
        }
    },
    /* first category with submenu */
    "menu-item#category__one-eventos": {
        "props": {
            "id": "category__one-eventos",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Nuestros Eventos",
                "text": "Nuestros Eventos"
            },
            "onMountBehavior": "open"
        },
        "blocks": [
            "vtex.menu@2.x:submenu#subcategory__one-eventos"
        ]
    },
    "vtex.menu@2.x:submenu#subcategory__one-eventos": {
        "children": [
            "vtex.menu@2.x:menu#subcategory__one-eventos"
        ]
    },
    "vtex.menu@2.x:menu#subcategory__one-eventos": {
        "children": [
            "menu-item#subcategory__one-eventos",
            "menu-item#subcategory__two-eventos"
        ]
    },
    "menu-item#subcategory__one-eventos": {
        "props": {
            "id": "subcategory__one-eventos",
            "type": "category",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Cumpleaños Carulla",
                "text": "Cumpleaños Carulla"
            }
        }
    },
    "menu-item#subcategory__two-eventos": {
        "props": {
            "id": "subcategory__two-eventos",
            "type": "category",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Cumpleaños septiembre",
                "text": "Cumpleaños septiembre"
            }
        }
    },
    /* firts category second item*/
    "menu-item#category__two-eventos": {
        "props": {
            "id": "category__two-eventos",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Promociones",
                "text": "Promociones"
            }
        }
    },
    /*second category*/
    "menu-item#category-lanzamientos": {
        "props": {
            "id": "menu-item-lanzamientos",
            "type": "custom",
            "highlight": false,
            "itemProps": {
                "type": "internal",
                "href": "/",
                "noFollow": false,
                "tagTitle": "Nuevos Lanzamientos",
                "text": "Nuevos Lanzamientos"
            },
            "iconProps": {
                "id": "mpa-globe",
                "size": 16,
                "viewBox": "0 0 16 16",
                "activeClassName": "",
                "mutedClassName": "c-action-primary"
            },
            "iconToTheRight": false
        },
        "blocks": [
            "submenu.accordion#departments-lanzamientos"
        ]
    },
    "submenu.accordion#departments-lanzamientos": {
        "children": [
            "menu#department__one-lanzamientos"
        ]
    },
    "menu#department__one-lanzamientos": {
        "children": [
            "menu-item#category__one-lanzamientos"
        ],
        "props": {
            "orientation": "vertical"
        }
    },
    "menu-item#category__one-lanzamientos": {
        "props": {
            "id": "category__one-lanzamientos",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "moda",
                "text": "Moda"
            }
        }
    },
    /*title of categories*/
    "rich-text#body-menu-text": {
        "props": {
            "text": "**Categoría** "
        }
    },
    "rich-text#body-menu-line": {
        "props": {
            "text": "_______________  "
        }
    },
    /* category*/
    "menu-item#category-delicatessen": {
        "props": {
            "id": "menu-item-delicatessen",
            "type": "custom",
            "highlight": false,
            "itemProps": {
                "type": "internal",
                "href": "/",
                "noFollow": false,
                "tagTitle": "delicatessen",
                "text": "delicatessen"
            },
            "iconProps": {
                "id": "hpa-telemarketing",
                "size": 16,
                "viewBox": "0 0 16 16",
                "activeClassName": "",
                "mutedClassName": "c-action-primary"
            },
            "iconToTheRight": false
        },
        "blocks": [
            "submenu.accordion#departments-delicatessen"
        ]
    },
    "submenu.accordion#departments-delicatessen": {
        "children": [
            "menu#department__one-delicatessen"
        ]
    },
    "menu#department__one-delicatessen": {
        "children": [
            "menu-item#category__one-delicatessen",
            "menu-item#category__two-delicatessen",
            "menu-item#category__three-delicatessen"
        ],
        "props": {
            "orientation": "vertical"
        }
    },
    "menu-item#category__one-delicatessen": {
        "props": {
            "id": "category__one-delicatessen",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Quesos ",
                "text": "Quesos"
            }
        }
    },
    "menu-item#category__two-delicatessen": {
        "props": {
            "id": "category__two-delicatessen",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Carnes Maduradas",
                "text": "Carnes Maduradas"
            }
        }
    },
    "menu-item#category__three-delicatessen": {
        "props": {
            "id": "category__three-delicatessen",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Encurtidos, patés y dulces",
                "text": "Encurtidos, patés y dulces"
            }
        }
    },
    /* Category*/
    "menu-item#category-bebidas": {
        "props": {
            "id": "menu-item-bebidas",
            "type": "custom",
            "highlight": false,
            "itemProps": {
                "type": "internal",
                "href": "/",
                "noFollow": false,
                "tagTitle": "Bebidas",
                "text": "Bebidas, pasabocas y dulces"
            },
            "iconProps": {
                "id": "mpa-play",
                "size": 16,
                "viewBox": "0 0 16 16",
                "activeClassName": "",
                "mutedClassName": "c-action-primary"
            },
            "iconToTheRight": false
        },
        "blocks": [
            "submenu.accordion#departments-bebidas"
        ]
    },
    "submenu.accordion#departments-bebidas": {
        "children": [
            "menu#department__one-bebidas"
        ]
    },
    "menu#department__one-bebidas": {
        "children": [
            "menu-item#category__one-bebidas",
            "menu-item#category__two-bebidas",
            "menu-item#category__three-bebidas",
            "menu-item#category__four-bebidas",
            "menu-item#category__five-bebidas",
            "menu-item#category__six-bebidas"
        ],
        "props": {
            "orientation": "vertical"
        }
    },
    "menu-item#category__one-bebidas": {
        "props": {
            "id": "category__one-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Bebidas ",
                "text": "Bebidas"
            }
        }
    },
    "menu-item#category__two-bebidas": {
        "props": {
            "id": "category__two-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Chocolate",
                "text": "Chocolate"
            }
        }
    },
    "menu-item#category__three-bebidas": {
        "props": {
            "id": "category__three-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Frutos secos",
                "text": "Frutos secos"
            }
        }
    },
    "menu-item#category__four-bebidas": {
        "props": {
            "id": "category__four-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Confiteria y dulces",
                "text": "Confiteria y dulces"
            }
        }
    },
    "menu-item#category__five-bebidas": {
        "props": {
            "id": "category__five-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Pasabocas",
                "text": "Pasabocas"
            }
        }
    },
    "menu-item#category__six-bebidas": {
        "props": {
            "id": "category__six-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Dulces Tipicos",
                "text": "Dulces Típicos"
            }
        }
    },
    /*Category*/
    "menu-item#category-vinos": {
        "props": {
            "id": "menu-item-vinos",
            "type": "custom",
            "highlight": false,
            "itemProps": {
                "type": "internal",
                "href": "/",
                "noFollow": false,
                "tagTitle": "Vainos",
                "text": "Vinos y licores"
            },
            "iconProps": {
                "id": "hpa-telemarketing",
                "size": 16,
                "viewBox": "0 0 16 16",
                "activeClassName": "",
                "mutedClassName": "c-action-primary"
            },
            "iconToTheRight": false
        },
        "blocks": [
            "submenu.accordion#departments-vinos"
        ]
    },
    "submenu.accordion#departments-vinos": {
        "children": [
            "menu#department__one-vinos"
        ]
    },
    "menu#department__one-vinos": {
        "children": [
            "menu-item#category__one-vinos",
            "menu-item#category__two-vinos",
            "menu-item#category__three-vinos",
            "menu-item#category__four-vinos",
            "menu-item#category__five-vinos",
            "menu-item#category__six-vinos",
            "menu-item#category__seven-vinos",
            "menu-item#category__eigth-vinos",
            "menu-item#category__nine-vinos"
        ],
        "props": {
            "orientation": "vertical"
        }
    },
    "menu-item#category__one-vinos": {
        "props": {
            "id": "category__one-vinos",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Vinos",
                "text": "Vinos"
            }
        }
    },
    "menu-item#category__two-vinos": {
        "props": {
            "id": "category__two-vinos",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Whisky",
                "text": "Whisky"
            }
        }
    },
    "menu-item#category__three-vinos": {
        "props": {
            "id": "category__three-vinos",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Vodkas",
                "text": "Vodkas"
            }
        }
    },
    "menu-item#category__four-vinos": {
        "props": {
            "id": "category__four-vinos",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Cervezas",
                "text": "Cervezas"
            }
        }
    },
    "menu-item#category__five-vinos": {
        "props": {
            "id": "category__five-vinos",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Tequilas",
                "text": "Tequilas"
            }
        }
    },
    "menu-item#category__six-vinos": {
        "props": {
            "id": "category__six-vinos",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Ron",
                "text": "Ron"
            }
        }
    },
    "menu-item#category__seven-vinos": {
        "props": {
            "id": "category__seven-vinos",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Aguardiente",
                "text": "Aguardiente"
            }
        }
    },
    "menu-item#category__eigth-vinos": {
        "props": {
            "id": "category__eigth-vinos",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Ginebras",
                "text": "Ginebras"
            }
        }
    },
    "menu-item#category__nine-vinos": {
        "props": {
            "id": "category__nine-vinos",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Cocteles y bases",
                "text": "Cocteles y bases"
            }
        }
    },
    /*Category*/
    "menu-item#category-panaderia": {
        "props": {
            "id": "menu-item-panaderia",
            "type": "custom",
            "highlight": false,
            "itemProps": {
                "type": "internal",
                "href": "/",
                "noFollow": false,
                "tagTitle": "panaderia",
                "text": "panaderia"
            },
            "iconProps": {
                "id": "hpa-telemarketing",
                "size": 16,
                "viewBox": "0 0 16 16",
                "activeClassName": "",
                "mutedClassName": "c-action-primary"
            },
            "iconToTheRight": true
        },
        "blocks": [
            "submenu.accordion#departments-bebidas"
        ]
    },
    "submenu.accordion#departments-panaderia": {
        "children": [
            "menu#department__one-panaderia"
        ]
    },
    "menu#department__one-panaderia": {
        "children": [
            "menu-item#category__one-panaderia",
            "menu-item#category__two-panaderia",
            "menu-item#category__three-panaderia",
            "menu-item#category__four-panaderia",
            "menu-item#category__five-panaderia"
        ],
        "props": {
            "orientation": "vertical"
        }
    },
    "menu-item#category__one-panaderia": {
        "props": {
            "id": "category__one-panaderia",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Panadería Fresca",
                "text": "Panadería Fresca"
            }
        }
    },
    "menu-item#category__two-panaderia": {
        "props": {
            "id": "category__two-panaderia",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Panadería Saludable",
                "text": "Panadería Saludable"
            }
        }
    },
    "menu-item#category__three-panaderia": {
        "props": {
            "id": "category__three-panaderia",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Panadería Empacada",
                "text": "Panadería Empacada"
            }
        }
    },
    "menu-item#category__four-panaderia": {
        "props": {
            "id": "category__four-panaderia",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Postres y tortas",
                "text": "Postres y tortas"
            }
        }
    },
    "menu-item#category__five-panaderia": {
        "props": {
            "id": "category__five-panaderia",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Panaderia Dulce",
                "text": "Panaderia Dulce"
            }
        }
    },
    /*Category*/
    "menu-item#category-pollo": {
        "props": {
            "id": "menu-item-pollo",
            "type": "custom",
            "highlight": false,
            "itemProps": {
                "type": "internal",
                "href": "/",
                "noFollow": false,
                "tagTitle": "Pollo, carnes y  pescado",
                "text": "Pollo, carnes y  pescado"
            },
            "iconProps": {
                "id": "mpa-play",
                "size": 16,
                "viewBox": "0 0 16 16",
                "activeClassName": "",
                "mutedClassName": "c-action-primary"
            },
            "iconToTheRight": false
        },
        "blocks": [
            "submenu.accordion#departments-bebidas"
        ]
    },
    "submenu.accordion#departments-bebidas": {
        "children": [
            "menu#department__one-bebidas"
        ]
    },
    "menu#department__one-bebidas": {
        "children": [
            "menu-item#category__one-bebidas",
            "menu-item#category__two-bebidas",
            "menu-item#category__three-bebidas",
            "menu-item#category__four-bebidas",
            "menu-item#category__five-bebidas",
            "menu-item#category__six-bebidas"
        ],
        "props": {
            "orientation": "vertical"
        }
    },
    "menu-item#category__one-bebidas": {
        "props": {
            "id": "category__one-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Bebidas ",
                "text": "Bebidas"
            }
        }
    },
    "menu-item#category__two-bebidas": {
        "props": {
            "id": "category__two-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Chocolate",
                "text": "Chocolate"
            }
        }
    },
    "menu-item#category__three-bebidas": {
        "props": {
            "id": "category__three-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Frutos secos",
                "text": "Frutos secos"
            }
        }
    },
    "menu-item#category__four-bebidas": {
        "props": {
            "id": "category__four-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Confiteria y dulces",
                "text": "Confiteria y dulces"
            }
        }
    },
    "menu-item#category__five-bebidas": {
        "props": {
            "id": "category__five-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Pasabocas",
                "text": "Pasabocas"
            }
        }
    },
    /*Category*/
    "menu-item#category-frutas": {
        "props": {
            "id": "menu-item-frutas",
            "type": "custom",
            "highlight": false,
            "itemProps": {
                "type": "internal",
                "href": "/",
                "noFollow": false,
                "tagTitle": "Frutas y Verduras",
                "text": "Frutas y Verduras"
            },
            "iconProps": {
                "id": "mpa-play",
                "size": 16,
                "viewBox": "0 0 16 16",
                "activeClassName": "",
                "mutedClassName": "c-action-primary"
            },
            "iconToTheRight": true
        },
        "blocks": [
            "submenu.accordion#departments-bebidas"
        ]
    },
    "submenu.accordion#departments-bebidas": {
        "children": [
            "menu#department__one-bebidas"
        ]
    },
    "menu#department__one-bebidas": {
        "children": [
            "menu-item#category__one-bebidas",
            "menu-item#category__two-bebidas",
            "menu-item#category__three-bebidas",
            "menu-item#category__four-bebidas",
            "menu-item#category__five-bebidas",
            "menu-item#category__six-bebidas"
        ],
        "props": {
            "orientation": "vertical"
        }
    },
    "menu-item#category__one-bebidas": {
        "props": {
            "id": "category__one-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Bebidas ",
                "text": "Bebidas"
            }
        }
    },
    "menu-item#category__two-bebidas": {
        "props": {
            "id": "category__two-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Chocolate",
                "text": "Chocolate"
            }
        }
    },
    "menu-item#category__three-bebidas": {
        "props": {
            "id": "category__three-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Frutos secos",
                "text": "Frutos secos"
            }
        }
    },
    "menu-item#category__four-bebidas": {
        "props": {
            "id": "category__four-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Confiteria y dulces",
                "text": "Confiteria y dulces"
            }
        }
    },
    "menu-item#category__five-bebidas": {
        "props": {
            "id": "category__five-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Pasabocas",
                "text": "Pasabocas"
            }
        }
    },
    /*Category*/
    "menu-item#category-despensa": {
        "props": {
            "id": "menu-item-despensa",
            "type": "custom",
            "highlight": false,
            "itemProps": {
                "type": "internal",
                "href": "/",
                "noFollow": false,
                "tagTitle": "Despensa",
                "text": "Despensa"
            },
            "iconProps": {
                "id": "mpa-play",
                "size": 16,
                "viewBox": "0 0 16 16",
                "activeClassName": "",
                "mutedClassName": "c-action-primary"
            },
            "iconToTheRight": true
        },
        "blocks": [
            "submenu.accordion#departments-bebidas"
        ]
    },
    "submenu.accordion#departments-bebidas": {
        "children": [
            "menu#department__one-bebidas"
        ]
    },
    "menu#department__one-bebidas": {
        "children": [
            "menu-item#category__one-bebidas",
            "menu-item#category__two-bebidas",
            "menu-item#category__three-bebidas",
            "menu-item#category__four-bebidas",
            "menu-item#category__five-bebidas",
            "menu-item#category__six-bebidas"
        ],
        "props": {
            "orientation": "vertical"
        }
    },
    "menu-item#category__one-bebidas": {
        "props": {
            "id": "category__one-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Bebidas ",
                "text": "Bebidas"
            }
        }
    },
    "menu-item#category__two-bebidas": {
        "props": {
            "id": "category__two-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Chocolate",
                "text": "Chocolate"
            }
        }
    },
    "menu-item#category__three-bebidas": {
        "props": {
            "id": "category__three-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Frutos secos",
                "text": "Frutos secos"
            }
        }
    },
    "menu-item#category__four-bebidas": {
        "props": {
            "id": "category__four-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Confiteria y dulces",
                "text": "Confiteria y dulces"
            }
        }
    },
    "menu-item#category__five-bebidas": {
        "props": {
            "id": "category__five-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Pasabocas",
                "text": "Pasabocas"
            }
        }
    },
    /*Category*/
    "menu-item#category-lacteos": {
        "props": {
            "id": "menu-item-lacteos",
            "type": "custom",
            "highlight": false,
            "itemProps": {
                "type": "internal",
                "href": "/",
                "noFollow": false,
                "tagTitle": "Lácteos, huevos y refrigerados",
                "text": "Lácteos, huevos y refrigerados"
            },
            "iconProps": {
                "id": "mpa-play",
                "size": 16,
                "viewBox": "0 0 16 16",
                "activeClassName": "",
                "mutedClassName": "c-action-primary"
            },
            "iconToTheRight": true
        },
        "blocks": [
            "submenu.accordion#departments-bebidas"
        ]
    },
    "submenu.accordion#departments-bebidas": {
        "children": [
            "menu#department__one-bebidas"
        ]
    },
    "menu#department__one-bebidas": {
        "children": [
            "menu-item#category__one-bebidas",
            "menu-item#category__two-bebidas",
            "menu-item#category__three-bebidas",
            "menu-item#category__four-bebidas",
            "menu-item#category__five-bebidas",
            "menu-item#category__six-bebidas"
        ],
        "props": {
            "orientation": "vertical"
        }
    },
    "menu-item#category__one-bebidas": {
        "props": {
            "id": "category__one-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Bebidas ",
                "text": "Bebidas"
            }
        }
    },
    "menu-item#category__two-bebidas": {
        "props": {
            "id": "category__two-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Chocolate",
                "text": "Chocolate"
            }
        }
    },
    "menu-item#category__three-bebidas": {
        "props": {
            "id": "category__three-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Frutos secos",
                "text": "Frutos secos"
            }
        }
    },
    "menu-item#category__four-bebidas": {
        "props": {
            "id": "category__four-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Confiteria y dulces",
                "text": "Confiteria y dulces"
            }
        }
    },
    "menu-item#category__five-bebidas": {
        "props": {
            "id": "category__five-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Pasabocas",
                "text": "Pasabocas"
            }
        }
    },
    /*Category*/
    "menu-item#category-preparados": {
        "props": {
            "id": "menu-item-preparados",
            "type": "custom",
            "highlight": false,
            "itemProps": {
                "type": "internal",
                "href": "/",
                "noFollow": false,
                "tagTitle": "Comidas Preparadas",
                "text": "Comidas Preparadas"
            },
            "iconProps": {
                "id": "mpa-play",
                "size": 16,
                "viewBox": "0 0 16 16",
                "activeClassName": "",
                "mutedClassName": "c-action-primary"
            },
            "iconToTheRight": true
        },
        "blocks": [
            "submenu.accordion#departments-bebidas"
        ]
    },
    "submenu.accordion#departments-bebidas": {
        "children": [
            "menu#department__one-bebidas"
        ]
    },
    "menu#department__one-bebidas": {
        "children": [
            "menu-item#category__one-bebidas",
            "menu-item#category__two-bebidas",
            "menu-item#category__three-bebidas",
            "menu-item#category__four-bebidas",
            "menu-item#category__five-bebidas",
            "menu-item#category__six-bebidas"
        ],
        "props": {
            "orientation": "vertical"
        }
    },
    "menu-item#category__one-bebidas": {
        "props": {
            "id": "category__one-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Bebidas ",
                "text": "Bebidas"
            }
        }
    },
    "menu-item#category__two-bebidas": {
        "props": {
            "id": "category__two-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Chocolate",
                "text": "Chocolate"
            }
        }
    },
    "menu-item#category__three-bebidas": {
        "props": {
            "id": "category__three-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Frutos secos",
                "text": "Frutos secos"
            }
        }
    },
    "menu-item#category__four-bebidas": {
        "props": {
            "id": "category__four-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Confiteria y dulces",
                "text": "Confiteria y dulces"
            }
        }
    },
    "menu-item#category__five-bebidas": {
        "props": {
            "id": "category__five-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Pasabocas",
                "text": "Pasabocas"
            }
        }
    },
    /*Category*/
    "menu-item#category-congelados": {
        "props": {
            "id": "menu-item-congelados",
            "type": "custom",
            "highlight": false,
            "itemProps": {
                "type": "internal",
                "href": "/",
                "noFollow": false,
                "tagTitle": "Congelados",
                "text": "Congelados"
            },
            "iconProps": {
                "id": "mpa-play",
                "size": 16,
                "viewBox": "0 0 16 16",
                "activeClassName": "",
                "mutedClassName": "c-action-primary"
            },
            "iconToTheRight": true
        },
        "blocks": [
            "submenu.accordion#departments-bebidas"
        ]
    },
    "submenu.accordion#departments-bebidas": {
        "children": [
            "menu#department__one-bebidas"
        ]
    },
    "menu#department__one-bebidas": {
        "children": [
            "menu-item#category__one-bebidas",
            "menu-item#category__two-bebidas",
            "menu-item#category__three-bebidas",
            "menu-item#category__four-bebidas",
            "menu-item#category__five-bebidas",
            "menu-item#category__six-bebidas"
        ],
        "props": {
            "orientation": "vertical"
        }
    },
    "menu-item#category__one-bebidas": {
        "props": {
            "id": "category__one-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Bebidas ",
                "text": "Bebidas"
            }
        }
    },
    "menu-item#category__two-bebidas": {
        "props": {
            "id": "category__two-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Chocolate",
                "text": "Chocolate"
            }
        }
    },
    "menu-item#category__three-bebidas": {
        "props": {
            "id": "category__three-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Frutos secos",
                "text": "Frutos secos"
            }
        }
    },
    "menu-item#category__four-bebidas": {
        "props": {
            "id": "category__four-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Confiteria y dulces",
                "text": "Confiteria y dulces"
            }
        }
    },
    "menu-item#category__five-bebidas": {
        "props": {
            "id": "category__five-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Pasabocas",
                "text": "Pasabocas"
            }
        }
    },
    /*Category*/
    "menu-item#category-limpieza": {
        "props": {
            "id": "menu-item-limpieza",
            "type": "custom",
            "highlight": false,
            "itemProps": {
                "type": "internal",
                "href": "/",
                "noFollow": false,
                "tagTitle": "Limpieza del hogar",
                "text": "Limpieza del hogar"
            },
            "iconProps": {
                "id": "mpa-play",
                "size": 16,
                "viewBox": "0 0 16 16",
                "activeClassName": "",
                "mutedClassName": "c-action-primary"
            },
            "iconToTheRight": true
        },
        "blocks": [
            "submenu.accordion#departments-bebidas"
        ]
    },
    "submenu.accordion#departments-bebidas": {
        "children": [
            "menu#department__one-bebidas"
        ]
    },
    "menu#department__one-bebidas": {
        "children": [
            "menu-item#category__one-bebidas",
            "menu-item#category__two-bebidas",
            "menu-item#category__three-bebidas",
            "menu-item#category__four-bebidas",
            "menu-item#category__five-bebidas",
            "menu-item#category__six-bebidas"
        ],
        "props": {
            "orientation": "vertical"
        }
    },
    "menu-item#category__one-bebidas": {
        "props": {
            "id": "category__one-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Bebidas ",
                "text": "Bebidas"
            }
        }
    },
    "menu-item#category__two-bebidas": {
        "props": {
            "id": "category__two-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Chocolate",
                "text": "Chocolate"
            }
        }
    },
    "menu-item#category__three-bebidas": {
        "props": {
            "id": "category__three-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Frutos secos",
                "text": "Frutos secos"
            }
        }
    },
    "menu-item#category__four-bebidas": {
        "props": {
            "id": "category__four-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Confiteria y dulces",
                "text": "Confiteria y dulces"
            }
        }
    },
    "menu-item#category__five-bebidas": {
        "props": {
            "id": "category__five-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Pasabocas",
                "text": "Pasabocas"
            }
        }
    },
    /*Category*/
    "menu-item#category-salud": {
        "props": {
            "id": "menu-item-salud",
            "type": "custom",
            "highlight": false,
            "itemProps": {
                "type": "internal",
                "href": "/",
                "noFollow": false,
                "tagTitle": "Salud y belleza",
                "text": "Salud y belleza"
            },
            "iconProps": {
                "id": "mpa-play",
                "size": 16,
                "viewBox": "0 0 16 16",
                "activeClassName": "",
                "mutedClassName": "c-action-primary"
            },
            "iconToTheRight": true
        },
        "blocks": [
            "submenu.accordion#departments-bebidas"
        ]
    },
    "submenu.accordion#departments-bebidas": {
        "children": [
            "menu#department__one-bebidas"
        ]
    },
    "menu#department__one-bebidas": {
        "children": [
            "menu-item#category__one-bebidas",
            "menu-item#category__two-bebidas",
            "menu-item#category__three-bebidas",
            "menu-item#category__four-bebidas",
            "menu-item#category__five-bebidas",
            "menu-item#category__six-bebidas"
        ],
        "props": {
            "orientation": "vertical"
        }
    },
    "menu-item#category__one-bebidas": {
        "props": {
            "id": "category__one-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Bebidas ",
                "text": "Bebidas"
            }
        }
    },
    "menu-item#category__two-bebidas": {
        "props": {
            "id": "category__two-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Chocolate",
                "text": "Chocolate"
            }
        }
    },
    "menu-item#category__three-bebidas": {
        "props": {
            "id": "category__three-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Frutos secos",
                "text": "Frutos secos"
            }
        }
    },
    "menu-item#category__four-bebidas": {
        "props": {
            "id": "category__four-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Confiteria y dulces",
                "text": "Confiteria y dulces"
            }
        }
    },
    "menu-item#category__five-bebidas": {
        "props": {
            "id": "category__five-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Pasabocas",
                "text": "Pasabocas"
            }
        }
    },
    /*Category*/
    "menu-item#category-electrodomesticos": {
        "props": {
            "id": "menu-item-electrodomesticos",
            "type": "custom",
            "highlight": false,
            "itemProps": {
                "type": "internal",
                "href": "/",
                "noFollow": false,
                "tagTitle": "Electrodomesticos",
                "text": "Electrodomesticos"
            },
            "iconProps": {
                "id": "mpa-play",
                "size": 16,
                "viewBox": "0 0 16 16",
                "activeClassName": "",
                "mutedClassName": "c-action-primary"
            },
            "iconToTheRight": true
        },
        "blocks": [
            "submenu.accordion#departments-bebidas"
        ]
    },
    "submenu.accordion#departments-bebidas": {
        "children": [
            "menu#department__one-bebidas"
        ]
    },
    "menu#department__one-bebidas": {
        "children": [
            "menu-item#category__one-bebidas",
            "menu-item#category__two-bebidas",
            "menu-item#category__three-bebidas",
            "menu-item#category__four-bebidas",
            "menu-item#category__five-bebidas",
            "menu-item#category__six-bebidas"
        ],
        "props": {
            "orientation": "vertical"
        }
    },
    "menu-item#category__one-bebidas": {
        "props": {
            "id": "category__one-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Bebidas ",
                "text": "Bebidas"
            }
        }
    },
    "menu-item#category__two-bebidas": {
        "props": {
            "id": "category__two-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Chocolate",
                "text": "Chocolate"
            }
        }
    },
    "menu-item#category__three-bebidas": {
        "props": {
            "id": "category__three-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Frutos secos",
                "text": "Frutos secos"
            }
        }
    },
    "menu-item#category__four-bebidas": {
        "props": {
            "id": "category__four-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Confiteria y dulces",
                "text": "Confiteria y dulces"
            }
        }
    },
    "menu-item#category__five-bebidas": {
        "props": {
            "id": "category__five-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Pasabocas",
                "text": "Pasabocas"
            }
        }
    },
    /*Category*/
    "menu-item#category-tecnologia": {
        "props": {
            "id": "menu-item-tecnologia",
            "type": "custom",
            "highlight": false,
            "itemProps": {
                "type": "internal",
                "href": "/",
                "noFollow": false,
                "tagTitle": "Tecnologia",
                "text": "Tecnologia"
            },
            "iconProps": {
                "id": "mpa-play",
                "size": 16,
                "viewBox": "0 0 16 16",
                "activeClassName": "",
                "mutedClassName": "c-action-primary"
            },
            "iconToTheRight": true
        },
        "blocks": [
            "submenu.accordion#departments-bebidas"
        ]
    },
    "submenu.accordion#departments-bebidas": {
        "children": [
            "menu#department__one-bebidas"
        ]
    },
    "menu#department__one-bebidas": {
        "children": [
            "menu-item#category__one-bebidas",
            "menu-item#category__two-bebidas",
            "menu-item#category__three-bebidas",
            "menu-item#category__four-bebidas",
            "menu-item#category__five-bebidas",
            "menu-item#category__six-bebidas"
        ],
        "props": {
            "orientation": "vertical"
        }
    },
    "menu-item#category__one-bebidas": {
        "props": {
            "id": "category__one-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Bebidas ",
                "text": "Bebidas"
            }
        }
    },
    "menu-item#category__two-bebidas": {
        "props": {
            "id": "category__two-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Chocolate",
                "text": "Chocolate"
            }
        }
    },
    "menu-item#category__three-bebidas": {
        "props": {
            "id": "category__three-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Frutos secos",
                "text": "Frutos secos"
            }
        }
    },
    "menu-item#category__four-bebidas": {
        "props": {
            "id": "category__four-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Confiteria y dulces",
                "text": "Confiteria y dulces"
            }
        }
    },
    "menu-item#category__five-bebidas": {
        "props": {
            "id": "category__five-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Pasabocas",
                "text": "Pasabocas"
            }
        }
    },
    /*Category*/
    "menu-item#category-moda": {
        "props": {
            "id": "menu-item-moda",
            "type": "custom",
            "highlight": false,
            "itemProps": {
                "type": "internal",
                "href": "/",
                "noFollow": false,
                "tagTitle": "Moda y Accesorios",
                "text": "Moda y Accesorios"
            },
            "iconProps": {
                "id": "mpa-play",
                "size": 16,
                "viewBox": "0 0 16 16",
                "activeClassName": "",
                "mutedClassName": "c-action-primary"
            },
            "iconToTheRight": true
        },
        "blocks": [
            "submenu.accordion#departments-bebidas"
        ]
    },
    "submenu.accordion#departments-bebidas": {
        "children": [
            "menu#department__one-bebidas"
        ]
    },
    "menu#department__one-bebidas": {
        "children": [
            "menu-item#category__one-bebidas",
            "menu-item#category__two-bebidas",
            "menu-item#category__three-bebidas",
            "menu-item#category__four-bebidas",
            "menu-item#category__five-bebidas",
            "menu-item#category__six-bebidas"
        ],
        "props": {
            "orientation": "vertical"
        }
    },
    "menu-item#category__one-bebidas": {
        "props": {
            "id": "category__one-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Bebidas ",
                "text": "Bebidas"
            }
        }
    },
    "menu-item#category__two-bebidas": {
        "props": {
            "id": "category__two-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Chocolate",
                "text": "Chocolate"
            }
        }
    },
    "menu-item#category__three-bebidas": {
        "props": {
            "id": "category__three-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Frutos secos",
                "text": "Frutos secos"
            }
        }
    },
    "menu-item#category__four-bebidas": {
        "props": {
            "id": "category__four-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Confiteria y dulces",
                "text": "Confiteria y dulces"
            }
        }
    },
    "menu-item#category__five-bebidas": {
        "props": {
            "id": "category__five-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Pasabocas",
                "text": "Pasabocas"
            }
        }
    },
    /*Category*/
    "menu-item#category-hogar": {
        "props": {
            "id": "menu-item-hogar",
            "type": "custom",
            "highlight": false,
            "itemProps": {
                "type": "internal",
                "href": "/",
                "noFollow": false,
                "tagTitle": "Hogar y Decoración",
                "text": "Hogar y Decoración"
            },
            "iconProps": {
                "id": "mpa-play",
                "size": 16,
                "viewBox": "0 0 16 16",
                "activeClassName": "",
                "mutedClassName": "c-action-primary"
            },
            "iconToTheRight": true
        },
        "blocks": [
            "submenu.accordion#departments-bebidas"
        ]
    },
    "submenu.accordion#departments-bebidas": {
        "children": [
            "menu#department__one-bebidas"
        ]
    },
    "menu#department__one-bebidas": {
        "children": [
            "menu-item#category__one-bebidas",
            "menu-item#category__two-bebidas",
            "menu-item#category__three-bebidas",
            "menu-item#category__four-bebidas",
            "menu-item#category__five-bebidas",
            "menu-item#category__six-bebidas"
        ],
        "props": {
            "orientation": "vertical"
        }
    },
    "menu-item#category__one-bebidas": {
        "props": {
            "id": "category__one-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Bebidas ",
                "text": "Bebidas"
            }
        }
    },
    "menu-item#category__two-bebidas": {
        "props": {
            "id": "category__two-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Chocolate",
                "text": "Chocolate"
            }
        }
    },
    "menu-item#category__three-bebidas": {
        "props": {
            "id": "category__three-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Frutos secos",
                "text": "Frutos secos"
            }
        }
    },
    "menu-item#category__four-bebidas": {
        "props": {
            "id": "category__four-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Confiteria y dulces",
                "text": "Confiteria y dulces"
            }
        }
    },
    "menu-item#category__five-bebidas": {
        "props": {
            "id": "category__five-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Pasabocas",
                "text": "Pasabocas"
            }
        }
    },
    /*Category*/
    "menu-item#category-deporte": {
        "props": {
            "id": "menu-item-deporte",
            "type": "custom",
            "highlight": false,
            "itemProps": {
                "type": "internal",
                "href": "/",
                "noFollow": false,
                "tagTitle": "Deporte y tiempo libre",
                "text": "Deporte y tiempo libre"
            },
            "iconProps": {
                "id": "mpa-play",
                "size": 16,
                "viewBox": "0 0 16 16",
                "activeClassName": "",
                "mutedClassName": "c-action-primary"
            },
            "iconToTheRight": true
        },
        "blocks": [
            "submenu.accordion#departments-bebidas"
        ]
    },
    "submenu.accordion#departments-bebidas": {
        "children": [
            "menu#department__one-bebidas"
        ]
    },
    "menu#department__one-bebidas": {
        "children": [
            "menu-item#category__one-bebidas",
            "menu-item#category__two-bebidas",
            "menu-item#category__three-bebidas",
            "menu-item#category__four-bebidas",
            "menu-item#category__five-bebidas",
            "menu-item#category__six-bebidas"
        ],
        "props": {
            "orientation": "vertical"
        }
    },
    "menu-item#category__one-bebidas": {
        "props": {
            "id": "category__one-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Bebidas ",
                "text": "Bebidas"
            }
        }
    },
    "menu-item#category__two-bebidas": {
        "props": {
            "id": "category__two-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Chocolate",
                "text": "Chocolate"
            }
        }
    },
    "menu-item#category__three-bebidas": {
        "props": {
            "id": "category__three-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Frutos secos",
                "text": "Frutos secos"
            }
        }
    },
    "menu-item#category__four-bebidas": {
        "props": {
            "id": "category__four-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Confiteria y dulces",
                "text": "Confiteria y dulces"
            }
        }
    },
    "menu-item#category__five-bebidas": {
        "props": {
            "id": "category__five-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Pasabocas",
                "text": "Pasabocas"
            }
        }
    },
    /*Category*/
    "menu-item#category-otros": {
        "props": {
            "id": "menu-item-otros",
            "type": "custom",
            "highlight": false,
            "itemProps": {
                "type": "internal",
                "href": "/",
                "noFollow": false,
                "tagTitle": "Otras Categorías",
                "text": "Otras Categorías"
            },
            "iconProps": {
                "id": "mpa-play",
                "size": 16,
                "viewBox": "0 0 16 16",
                "activeClassName": "",
                "mutedClassName": "c-action-primary"
            },
            "iconToTheRight": true
        },
        "blocks": [
            "submenu.accordion#departments-bebidas"
        ]
    },
    "submenu.accordion#departments-bebidas": {
        "children": [
            "menu#department__one-bebidas"
        ]
    },
    "menu#department__one-bebidas": {
        "children": [
            "menu-item#category__one-bebidas",
            "menu-item#category__two-bebidas",
            "menu-item#category__three-bebidas",
            "menu-item#category__four-bebidas",
            "menu-item#category__five-bebidas",
            "menu-item#category__six-bebidas"
        ],
        "props": {
            "orientation": "vertical"
        }
    },
    "menu-item#category__one-bebidas": {
        "props": {
            "id": "category__one-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Bebidas ",
                "text": "Bebidas"
            }
        }
    },
    "menu-item#category__two-bebidas": {
        "props": {
            "id": "category__two-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Chocolate",
                "text": "Chocolate"
            }
        }
    },
    "menu-item#category__three-bebidas": {
        "props": {
            "id": "category__three-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Frutos secos",
                "text": "Frutos secos"
            }
        }
    },
    "menu-item#category__four-bebidas": {
        "props": {
            "id": "category__four-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Confiteria y dulces",
                "text": "Confiteria y dulces"
            }
        }
    },
    "menu-item#category__five-bebidas": {
        "props": {
            "id": "category__five-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Pasabocas",
                "text": "Pasabocas"
            }
        }
    },
    /*Category*/
    "menu-item#category-cocina": {
        "blocks": [
            "submenu.accordion#departments"
        ],
        "props": {
            "id": "menu-item-cocina",
            "type": "custom",
            "highlight": false,
            "itemProps": {
                "type": "internal",
                "href": "/",
                "noFollow": false,
                "tagTitle": "Escuela de Cocina",
                "text": "Escuela de Cocina"
            },
            "iconProps": {
                "id": "mpa-play",
                "size": 16,
                "viewBox": "0 0 16 16",
                "activeClassName": "",
                "mutedClassName": "c-action-primary"
            },
            "iconToTheRight": true
        },
        "blocks": [
            "submenu.accordion#departments-bebidas"
        ]
    },
    "submenu.accordion#departments-bebidas": {
        "children": [
            "menu#department__one-bebidas"
        ]
    },
    "menu#department__one-bebidas": {
        "children": [
            "menu-item#category__one-bebidas",
            "menu-item#category__two-bebidas",
            "menu-item#category__three-bebidas",
            "menu-item#category__four-bebidas",
            "menu-item#category__five-bebidas",
            "menu-item#category__six-bebidas"
        ],
        "props": {
            "orientation": "vertical"
        }
    },
    "menu-item#category__one-bebidas": {
        "props": {
            "id": "category__one-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Bebidas ",
                "text": "Bebidas"
            }
        }
    },
    "menu-item#category__two-bebidas": {
        "props": {
            "id": "category__two-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Chocolate",
                "text": "Chocolate"
            }
        }
    },
    "menu-item#category__three-bebidas": {
        "props": {
            "id": "category__three-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Frutos secos",
                "text": "Frutos secos"
            }
        }
    },
    "menu-item#category__four-bebidas": {
        "props": {
            "id": "category__four-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Confiteria y dulces",
                "text": "Confiteria y dulces"
            }
        }
    },
    "menu-item#category__five-bebidas": {
        "props": {
            "id": "category__five-bebidas",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Pasabocas",
                "text": "Pasabocas"
            }
        }
    },
    /*Ejemplo de submenu  */
    "submenu.accordion#departments": {
        "children": [
            "menu#department__one"
        ]
    },
    "menu#department__one": {
        "children": [
            "menu-item#category__one",
            "menu-item#category__two"
        ],
        "props": {
            "orientation": "vertical"
        }
    },
    "menu-item#category__one": {
        "props": {
            "id": "category__one",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "Sin Alcohol",
                "text": "Sin Alcohol"
            }
        }
    },
    "menu-item#category__two": {
        "props": {
            "id": "category__one",
            "type": "custom",
            "itemProps": {
                "type": "internal",
                "href": "/",
                "notFollow": true,
                "tagTitle": "con Alcohol",
                "text": "con Alcohol"
            }
        }
    }
}
/ footer nuevo 08 09 22/

"flex-layout.row#footer__desktop-middle": {
    "children": [
      "flex-layout.col#desktop__middle-top-content-information"
    ],
    "props": {
      "blockClass": "footer__desktop-middle"
  }
  },

  "flex-layout.col#desktop__middle-top-content-information": {
    "children": [
      "flex-layout.row#container__text-information",
      "flex-layout.row#container__disclosure-information"
    ],
    "props": {
      "blockClass": "desktop__middle-top-content-information"
  }
},

  "flex-layout.row#container__text-information": {
    "children": [
      "rich-text#information"
    ],
    "props": {
      "blockClass": "container__text-information"
  }},

  "rich-text#information": {
    "props": {
      "text": "Más Información",
      "textAlignment": "CENTER",
      "textPosition": "CENTER",
      "blockClass": "principal-text"
    }
  },


  "flex-layout.row#container__disclosure-information": {
    "children": [
      "flex-layout.col#container__disclosure-information"
      

    ],
    "props": {
      "blockClass": "container__disclosure-information-first"
  }
  },
  "flex-layout.col#container__disclosure-information": {
    "children": [
      "disclosure-layout#information__desktop"
      

    ],
    "props": {
      "blockClass": "container__disclosure-information-second"
  }
  },
  "disclosure-layout#information__desktop": {
    "children": [
      "disclosure-trigger#information",
      "disclosure-content#information"
    ],
    "props": {
      "blockClass": "disclosure__layout-information__desktop"
  }
  },

  //---------------trigger--------------------//
  "disclosure-trigger#information": {
    "children": [
      "flex-layout.row#trigger__container-information-one"
    ],
    "props": {
      "as": "h4",
      "blockClass": "container__trigger-information"
    }
  },


  "flex-layout.row#trigger__container-information-one":{
    "children":[
      "flex-layout.row#trigger__container-information-one-group",
      "flex-layout.row#trigger__container-information-one-group",
      "flex-layout.row#trigger__container-information-one-group"
    ],
      "props":{
        "blockClass":"different__container"

      }
    },


  "flex-layout.row#trigger__container-information-one-group":{
    "children": [
      "rich-text#first__inner-text",
      "disclosure-state-indicator"
    ],
    "props": {
      "blockClass": "trigger__container-information-one"
  }
  },

  "rich-text#first__inner-text": {
    "props": {
      "text": "Centro de ayuda",
      "blockClass": "principal-text"
    }
  },

  "disclosure-state-indicator": {
    "props": {
      "Show": "icon-caret#state-indicator-down",
      "Hide": "icon-caret#state-indicator-up",
      "blockClass": "state--disclosure"
    }
  },
  "icon-caret#state-indicator-down": {
    "props": {
      "id": "nav-caret--down"
    }
  },
  "icon-caret#state-indicator-up": {
    "props": {
      "id": "nav-caret--up"
    }
  },
//----------------End trigger----------------------//
//------------------content-----------------------//

  "disclosure-content#information": {
    "children": [
      "flex-layout.row#desktop__middle-bottom-content"
    ],
    "props": {
      "blockClass": "disclosure__content-information"
  }
  },
  "flex-layout.row#desktop__middle-bottom-content": {
    "children": [
      "flex-layout.col#bottom__content-first",
      "flex-layout.col#bottom__content-first",
      "flex-layout.col#bottom__content-first"
    ],
    "props": {
      "blockClass": "desktop__middle-bottom-content"
    }
  },
  "flex-layout.col#bottom__content-first": {
    "children": [
      "rich-text#answer1",
      "rich-text#answer2",
      "rich-text#answer3",
      "rich-text#answer4",
      "rich-text#answer5"
    ],
    "props": {
      "blockClass": "bottom__content-first"
  }
  },
  "rich-text#answer1": {
    "props": {
      "text": "[Chat](/preguntas-frecuentes)",
      "blockClass": "subgroup__text-information"
    }
  },
  "rich-text#answer2": {
    "props": {
      "text": "[Preguntas Frecuentes](/preguntas-frecuentes)",
      "blockClass": "subgroup__text-information"
    }
  },
  "rich-text#answer3": {
    "props": {
      "text": "[Política de cambio y devoluciones](/preguntas-frecuentes)",
      "blockClass": "subgroup__text-information"
    }
  },
  "rich-text#answer4": {
    "props": {
      "text": "[Contacto](/preguntas-frecuentes)",
      "blockClass": "subgroup__text-information"
    }
  },
  "rich-text#answer5": {
    "props": {
      "text": "[Almacenes](/preguntas-frecuentes)",
      "blockClass": "subgroup__text-information"
    }