# Re:View
Proxy server for Re:View, a restaurant rating website. There is a photo carousel at top, followed by an information section, a sidebar showing opening hours and a map to their location, a section with tips and articles related to the restaurant, and a grid showing similar restaurants by category and neighborhood.

## Individual Projects
  - https://github.com/hrr47-sdc8-webber/photo-carousel-service
  - https://github.com/hrr47-sdc8-webber/info-sidebar-service
  - https://github.com/hrr47-sdc8-webber/tips-recommendations-service
  - https://github.com/hrr47-sdc8-webber/similar-restaurants-service

## Table of Contents

1. [Requirements](#Requirements)
2. [Dependencies](#Dependencies)
3. [Usage](#Usage)


## Requirements
- Node v12.18.1
  - https://nodejs.org/


## Dependencies
From within this repository's root directory:
```sh
npm install
```

## Usage
> Example URL: http://localhost:3000/1/

To initialize the page:

```sh
npm start
```
All services must be running individually in order for the full page to render. Otherwise, this is a fairly simple proxy page that renders all Re:View modules. In order to access a particular product ID, direct the browser to /:id. All services have been optimized for 10M primary records, so any id between 1 and 10000000 will work. Happy viewing!
