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
}