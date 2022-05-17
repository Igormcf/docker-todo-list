FROM mjgargani/puppeteer:trybe1.0 AS todotests
WORKDIR /app
ADD /node_modules.tar.gz ./
COPY . .
RUN ["npm", "install"]
CMD ["npm", "start"]
ENV FRONT_HOST="localhost"
ENV FRONT_PORT="3000"