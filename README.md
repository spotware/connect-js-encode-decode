# connect-js-encode-decode
[![Build Status](https://travis-ci.org/spotware/connect-js-encode-decode.svg?branch=master)](https://travis-ci.org/spotware/connect-js-encode-decode)

Spotware Connect encoder/decoder for binary messages

![Alt text](http://g.gravizo.com/g?
  digraph usage {
    "connect-js-adapter-tls" -> "connect-js-api";
    "connect-protobuf-messages" -> "connect-js-api";
    "connect-js-encode-decode" -> "connect-js-api";
    "connect-js-encode-decode" [style=filled,color="grey"];
    "connect-js-api" -> "ctrader-telegram-bot";
    "connect-js-api" -> "connect-nodejs-samples";
  }
)
