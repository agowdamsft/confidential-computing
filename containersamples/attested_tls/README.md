# The attested_tls sample

The sample source codes are from [the attested_tls sample of the Open Enclave SDK](https://github.com/openenclave/openenclave/tree/master/samples/attested_tls).

The corresponding docker image was published in Docker Hub. Please see [attested_tls/Dockerfile](Dockerfile) for details of the docker image.

You can use yaml file for your Azure Kubernetes Service deployment. There are two pods, TLS server and TLS client. TLS server can be deployed by using [attested_tls/attested_tls_server.yaml](attested_tls_server.yaml). Before TLS client deployment, please populate external server IP in [attested_tls/attested_tls_client.yaml](attested_tls_client.yaml).
