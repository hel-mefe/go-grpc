This repository contains a collection of small applications written in Go that demonstrate various aspects of using gRPC (Google Remote Procedure Call) framework. Whether you're new to gRPC or looking to sharpen your skills, this repository aims to provide practical examples to help you learn and practice.

![Cool gRPC Gopher](https://github.com/hel-mefe/go-grpc/blob/main/gopher/gRPC-gopher.png?raw=true)

## Contents:
<b>Unary RPC Example:</b> Learn how to implement and call unary RPC (single request, single response) using Go and gRPC.<br />
<b>Server Streaming Example:</b> Explore server streaming RPCs where the server sends a stream of responses to a single client request. <br /> 
<b>Client Streaming Example:</b> Dive into client streaming RPCs where the client sends a stream of requests to the server to receive a single response. <br /> 
<b>Bidirectional Streaming Example:</b> Discover bidirectional streaming RPCs, enabling both the client and server to send a stream of messages concurrently. <br />

## Questions about gRPC
### Does gRPC perform better than REST and GraphQL?
This probably not the right question to ask, each API architecture has its strengths and drawbacks, but gRPC excels at microservices architecture where the network latency is important, therefore if it's about internal system communication then gRPC is better of course, otherwise you may think about your systems needs and choose which one appropriate for your specific case.

