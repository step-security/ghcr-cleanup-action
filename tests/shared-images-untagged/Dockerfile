FROM node:24.1.0-alpine3.20@sha256:8fe019e0d57dbdce5f5c27c0b63d2775cf34b00e3755a7dea969802d7e0c2b25 AS base-image
WORKDIR /app

FROM base-image
ENV NODE_ENV=production
ENV PORT=3000
USER node
HEALTHCHECK CMD curl --fail http://localhost:3000 || exit 1",
EXPOSE 3000
