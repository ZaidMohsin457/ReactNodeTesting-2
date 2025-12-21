FROM node:18
WORKDIR /usr/src/app
COPY package*.json ./
RUN npm i
COPY . .
ENV PORT=3000
EXPOSE 3000
#HEALTHCHECK --interval=30s --timeout=5s --start-period=10s --retries=3 \
CMD ["node", "index.js"]
