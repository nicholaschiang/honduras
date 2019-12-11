# Honduras - Social Justice Project

Final history project where we present on a country and various historical
events surrounding it. The idea here is to make whatever I create accessible to
everyone, everywhere (on the web).

## Project Structure

The file structure of most of my web projects are pretty much the same (with the
exception of [Tutorbook](https://github.com/nicholaschiang/tutorbook) that uses
[Lerna](https://github.com/lerna/lerna) to split code into sub-packages):

```bash
.
├── build
│   ├── index.html
│   ├── scripts
│   │   └── bundle.min.js
│   └── styles
│       └── bundle.min.css
├── README.md
└── src
    ├── package.json
    ├── scripts
    │   └── index.js
    ├── styles
    │   ├── style.css
    │   └── style.scss
    └── webpack.config.js
```

Everything in the `src/` directory is webpacked into the three files in `build/`
that are then served via [Netlify](https://netlify.com) on repository push.
