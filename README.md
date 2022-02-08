# TV Shows SPA
TV Shows dashboard with listings by genres and ratings. Find the TV Show you want to know more about.

## Prerequisites
Download Node.js at https://nodejs.org/en/download/ (latest version - contains npm)

### Main stack
- HTML5
- Sass
- ECMAScript 6 (ES6)
- Vue

Below I show you the packages I developed the application with:

- Vue cli (v4.3.1)
- HTTP client: Axios
- Store management: Vuex (v3.4.0)
- Components design: Vuetify
- Preprocessor: Sass (dart-sass)

### Api
TV shows API: http://www.tvmaze.com/api

#### Endpoints
Shows listing: http://api.tvmaze.com/shows
Show detail: http://api.tvmaze.com/shows/:id and http://api.tvmaze.com/shows/:id/images
Search shows: http://api.tvmaze.com/search/shows?q=:query

## Setup

To install dependencies and start working on the project run:
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Run unit tests
```
npm run test:unit
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
