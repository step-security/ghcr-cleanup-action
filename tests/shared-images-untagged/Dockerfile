FROM node:22.6.0-alpine3.20@sha256:4162c8a0f1fef9d3b003eb1fd3d8a26db46815288832aa453d829f4129d4dfd3 AS base-image
WORKDIR /app

FROM base-image
ENV NODE_ENV=production
ENV PORT=3000
USER node
HEALTHCHECK CMD curl --fail http://localhost:3000 || exit 1",
EXPOSE 3000
