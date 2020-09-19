# Strapi x 11ty - A Simple Blog Site using [11ty](https://www.11ty.dev/), built with Strapi 

This application helps you get started building a blog website with a few other pages. Feel free to fork, edit and customise it for your own use.

![Screenshot]()

## Features
- Minimal design 
- Page Slugs
- GraphQL first approach

## Content Model
- `title` : Text
- `content` : Rich Text
- `published_at` : Date
- `author` : Text
- `slug` : Text

## In the works
- Testing Pagination

## Pages
- A home page :`/`
- An about me page :`/about`
- A blog page :`/blog`

## Getting Started

To get started clone the repo
```bash
git clone https://github.com/malgamves/11ty-x-strapi.git
cd 11ty-x-strapi
```

The project has two folders `frontend` for your 11ty frontend and `backend` for your Strapi backend.


### Frontend
The frontend is built with 11ty. This sets up your frontend.
```bash
cd frontend

yarn install
```

Then run `yarn serve` to start your frontend server.

### Backend
The backend is built with Strapi. This sets up your backend.
```bash
cd backend

yarn install
```

Then run `yarn develop` to start your backend server.


## Deployment 

### 11ty

[Add Deets]


For your backend, Strapi has numerous options in it's [deployment guide](https://strapi.io/documentation/3.0.0-beta.x/getting-started/deployment.html).


## Contributing

Feel free to send over a PR for any changes you think should be included.
