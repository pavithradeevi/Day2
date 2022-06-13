**1.Write a blog on Difference between HTTP1.1 vs HTTP2**

HTTP 1.1
  It Works Textual format
  It compresses data by itself.
  HTTP2 is much faster and more reliable than HTTP1.
  1997-Introduced persistent connection, pipelining,cache-control, and many other features.
  It supports connection reuse i.e. for every TCP connection there could be multiple requests and responses, and pipelining where the client can request several resources from the server at once. 
  Introduces a warning header field to carry additional information about the status of a message. Can define 24 status codes, error reporting is quicker and more efficient.
  
HTTP2
  It works on the binary protocol.
  It uses HPACK for data compression.
  2015-Based on Google’s SPDY allows multiplexing and server push.
  Uses multiplexing, where over a single TCP connection resources to be delivered are interleaved and arrive at the client almost at the same time. It is done using streams that can be prioritized and can have dependencies and individual flow control.
  The underlying semantics of HTTP such as headers, and status codes remain the same.
  
  
  
**2. Write a blog about objects and their internal representation in Javascript**

Objects:

      In JavaScript, is it’s most important data-type and forms the building blocks for modern JavaScript. These objects are quite different from JavaScript’s primitive data-types(Number, String, Boolean, null, undefined and symbol) in the sense that while these primitive data-types all store a single value each (depending on their types).

Creating Objects in JavaScript:
            By object literal
            By creating an instance of Object directly (using the new keyword)







