# Strapi Google Auth Android Example

An example application containing Strapi Application with installed plugin Google Auth Mobile https://www.npmjs.com/package/strapi-plugin-google-auth-mobile and an Android app (Kotlin).

The server can be started using Docker:

```bash
cd strapi-server
cp .env.example .env

cd ..
docker-compose -f docker-compose.yml up --build --remove-orphans
```