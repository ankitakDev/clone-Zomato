FROM node:alpine

WORKDIR /app

COPY ./package*.json ./

RUN npm install

COPY . ./

ENV MONGO_URI=mongodb+srv://adityaGusain:adityaGusain@zomato.iem30.mongodb.net/zomato?retryWrites=true&w=majority
ENV GOOGLE_CLIENT_ID=340910053462-utkliaob4b5lj821841ve7hfmf437ls7.apps.googleusercontent.com
ENV GOOGLE_CLIENT_SECRET=PXIW1i_4OcWDnmD2aQqDLDH4
ENV AWS_S3_ACCESS_KEY=AKIAS2KUM2FUQ22Y7SZT
ENV AWS_S3_SECRET_KEY=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
ENV MAILGUN__API__KEY=28b779c4b19d2b59a6b8348bce2655b6-443ec20e-333e1de7
ENV MAILGUN__DOMAIN=sandbox5a4da10e46c24e059117360504a33799.mailgun.org
ENV RZR_PAY_ID=rzp_test_q1aD8S4CGOEb75
ENV RZR_PAY_SECRET=7ZVrvejztwccSuJbgdLvMw76
ENV PORT=4000

CMD ["npm", "run", "start"]