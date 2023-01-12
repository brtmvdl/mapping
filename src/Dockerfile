FROM tmvdl/android:cordova

WORKDIR /app

RUN cordova create mapping com.brtmvdl.mapping mapping

WORKDIR /app/mapping

COPY www/html www

RUN cordova platform add android

RUN cordova build android
