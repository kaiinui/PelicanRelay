# PelicanRelay

Pelican Relay is a proxy server which relays server side events and batching RPC in one TCP connection to backend services.

It aims to provide high performance, low latency, battery-friendly communication for native mobile applications.

## Features Provided

1. Channel based server side events a.k.a. push notifications.
2. Requesting batch RPCs and translate them into HTTP/2 requests for backend services.

## Performance Features

1. All requests and responses in just one TCP connection.
2. Encryption without TLS to eliminate handshake roundtrips. (Pre-bundled public key)
3. Keep TCP connections between backend services alived.

<img src="https://i.gyazo.com/4e957a9de9503a2f3c3e30c131b15315.png" width=320px />
