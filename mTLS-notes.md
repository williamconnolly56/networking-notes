# **mTLS Notes**


## *How is mTLS different from TLS?*


TLS (Transport Layer Security) and mTLS (mutual Transport Layer Security) both aim to secure communications between clients and servers, but they differ in their authentication processes:

*TLS*

- The server presents its digital certificate to the client for authentication.
- The client verifies the server's certificate to ensure it is valid and issued by a trusted Certificate Authority (CA). This allows the client to establish trust and encrypt the communication channel.

*mTLS*

- Both the client and the server present certificates to each other for mutual authentication.
- This mutual authentication ensures that both the client and the server are verified and authenticated.

So, the key difference lies in the mutual authentication aspect of mTLS.


## *Where is mTLS frequently used?*


mTLS is frequently used wherever the mutual authentication of both parties involved in communication is critical to maintaining the integrity, confidentiality, and security of the data being exchanged.


## *Give an example application which uses mTLS*


Financial Transactions: In the financial sector, mTLS helps secure transactions between banking systems, ensuring that both the client and the server are authenticated, reducing the risk of fraudulent activities and protecting sensitive financial data.


## *Diagram*


![mTls_smaller](https://github.com/williamconnolly56/networking-notes/assets/146080335/78ac622d-3ceb-4287-bc63-a4351681d75c)


## References

- https://www.cloudflare.com/en-gb/learning/access-management/what-is-mutual-tls/
- https://en.wikipedia.org/wiki/Mutual_authentication
- https://buoyant.io/mtls-guide
- https://www.f5.com/labs/learning-center/what-is-mtls

