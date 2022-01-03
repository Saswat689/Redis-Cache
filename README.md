 # Caching in Node.js :rocket:

 Caching is a powerful technique that makes web servers serve content faster about 10 to 20 times on GET endpoints.This code is just an implementation of caching using Redis in Node.

## Getting started

If you want this as a template:

- **Clone the repo:**

```
git clone https://github.com/Saswat689/Redis-Cache.git .
```

- **Run the server:**

```
npm start	
```

- Redis must be installed on your system.
- **Note** that a type:module is specified in the package.json because we are using node-fetch as a module.

## Endpoints

`/repos/:username`

- Rate limit: none
- Secure: none
- Caching: true

**Return value** Number of repos created by the `:username` param.

