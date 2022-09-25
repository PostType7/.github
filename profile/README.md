### Install PostType7 starter

- Clone empty next.js repo with typescript and tailwind<br/>
`git clone git@github.com:PostType7/NextStarterPack.git <your-project-name>`<br/><br/>
- Clone native UI components<br/>
`git clone git@github.com:PostType7/NativeTheme.git <your-project-name>/src/components/themes/NativeTheme`<br/><br/>
- Clone PostType7 basic theme (PureBaldrTheme)<br/>
`git clone git@github.com:PostType7/NativeTheme.git <your-project-name>/src/components/themes/PureBaldrTheme`<br/><br/>
- Clone example PureBaldrTheme page<br/>
`git clone git@github.com:PostType7/NativeTheme.git <your-project-name>/src/pages/PureBaldr-example-backOffice`<br/><br/>
- Go to your projectr `cd/<your-project-name>` install libraries `yarn` and run `yarn dev`<br/>


### Organisation repositories map

```
┌────────────────────────────────────────────────────────────────────────────┐      ┌──────────────────────────┐
│                                                                            │   ┌──┤       NPM: P7-State-Form │
│                                                                 /src/pages │   │  └──────────────────────────┘
│                                               PureBaldr-example-backOffice │   │
│                                                                            │   │  ┌──────────────────────────┐
└────────────────────────────────────────────┬───────────────────────────────┘   ├──┤   NPM: P7-Rest-Controler │
                                             │                                   │  └──────────────────────────┘
                                             ▼                                   │
┌───────────────────────────┐       ┌────────────────────────────────────────┐   │
│                           │       │                                        │   │
│   /src/components/themes/ │       │                                   /src │   │
│               NativeTheme ├───┬──►│                        NextStarterPack │ ◄─┘
│                           │   │   │                                        │
└───────────────────────────┘   │   └────────┬───────────────────────────────┘
                                │            │
┌───────────────────────────┐   │            │
│                           │   │            │      ┌────────────────────────┐
│   /src/components/themes/ │   │            │      │                        │
│            PuseBaldrTheme ├───┤            │◄─────┤  Strapi-PRESS-template │
│                           │   │            │      │                        │
└───────────────────────────┘   │            │      └────────────────────────┘
                                │            │
┌───────────────────────────┐   │    ┌───────┴─────┐
│                           │   │    │             │
│  /src/components/plugins/ │   │    │  RenderApp  │
│ RestStrapiProvidersPlugin ├───┘    │             │
│                           │        │             │
└───────────────────────────┘        └─────────────┘
```
Shemat createdby https://asciiflow.com/#/
