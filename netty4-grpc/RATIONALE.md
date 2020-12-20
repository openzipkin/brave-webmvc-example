## Why Netty HTTP frontend?
While gRPC is HTTP/2, it is difficult to invoke without a compiled client. This
example aims to show gRPC client-server communication, but not distract users
who maybe aren't very familiar with how to compile protos.

While coding a Netty HTTP handler is distracting, due to dealing directly with
keep alives, it is less dependencies to worry about. Also, it serves as an
example of how to use Brave's Netty instrumentation.