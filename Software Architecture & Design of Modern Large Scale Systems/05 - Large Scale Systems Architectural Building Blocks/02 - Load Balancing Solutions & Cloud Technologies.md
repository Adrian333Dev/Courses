# Load Balancing Solutions & Cloud Technologies

## Open Source Software Load Balancing Solutions

### [HAProxy](https://www.haproxy.org/)

HAProxy is a free and open-source, reliable, high performance TCP/HTTP load balancer.
It is particularly suited for very high traffic web sites, and powers a significant portion of the world's most visited ones. It is considered the de-facto standard open-source load balancer, and is shipped with most mainstream Linux distributions.
HAProxy supports most Unix style operating systems.

### [NGINX](https://www.nginx.com/)

NGINX is a free, open-source, high-performance HTTP server and reverse proxy (load balancer). It is known for its high performance, stability, rich feature set and simple configuration.
For a full tutorial on how to install, configure and use NGINX follow this [link](https://www.nginx.com/resources/wiki/start/).

---

## Cloud Based Load Balancing Solutions

### [AWS - Elastic Load Balancing (ELB)](https://aws.amazon.com/elasticloadbalancing/)

Amazon ELB is a highly scalable load balancing solution.

It is an ideal solution for running on AWS, and integrates seamlessly with all of AWS services.

It can operate on 4 different modes:

1. [Application (Layer 7) Load Balancer](https://aws.amazon.com/elasticloadbalancing/application-load-balancer/?nc=sn&loc=2&dn=2) - Ideal for advanced load balancing of HTTP and HTTPS traffic
2. [Network (Layer 4) Load Balancer](https://aws.amazon.com/elasticloadbalancing/network-load-balancer/?nc=sn&loc=2&dn=3) - Ideal for load balancing of both TCP and UDP traffic
3. [Gateway Load Balancer](https://aws.amazon.com/elasticloadbalancing/gateway-load-balancer/) - Ideal for deploying, scaling, and managing your third-party virtual appliances.
4. [Classic Load Balancer (Layer 4 and 7)](https://aws.amazon.com/elasticloadbalancing/classic-load-balancer/?nc=sn&loc=2&dn=5) - Ideal for routing traffic to EC2 instances.

For the full documentation on Amazon ELB and its autoscaling policies follow this [link](https://docs.aws.amazon.com/autoscaling/ec2/userguide/autoscaling-load-balancer.html).

### [GCP - Cloud Load Balancing](https://cloud.google.com/load-balancing)

Google Cloud Platform Load Balancer is Google's, highly scalable and robust load balancing solution.

"Cloud Load Balancing allows you to put your resources behind a single IP address that is externally accessible or internal to your Virtual Private Cloud (VPC) network".

Some of the load balancer types available as part of the [GCP Cloud Load Balancing](https://cloud.google.com/load-balancing/docs) are:

1. [External HTTP(S) Load Balancer](https://cloud.google.com/load-balancing/docs/https) - Externally facing HTTP(s) (Layer 7) load balancer which enables you to run and scale your services behind an internal IP address.
2. [Internal HTTP(S) Load Balancer](https://cloud.google.com/load-balancing/docs/l7-internal) - Internal Layer 7 load balancer that enables you to run and scale your services behind an internal IP address.
3. [External TCP/UDP Network Load Balancer](https://cloud.google.com/load-balancing/docs/network/networklb-backend-service) - Externally facing TCP/UDP (Layer 4) load balancer
4. [Internal TCP/UDP Load Balancer](https://cloud.google.com/load-balancing/docs/internal) - Internally facing TCP/UDP (Layer 4) load balancer

### [Microsoft Azure Load Balancer](https://azure.microsoft.com/en-us/products/load-balancer/)

Microsoft Azure load balancing solution provides 3 different types of load balancer:

1. [Standard Load Balancer](https://learn.microsoft.com/en-us/azure/load-balancer/load-balancer-overview) - Public and internal Layer 4 load balancer
2. [Gateway Load Balancer](https://learn.microsoft.com/en-us/azure/load-balancer/gateway-overview) - High performance and high availability load balancer for third-party Network Virtual Appliances.
3. [Basic Load Balancer](https://learn.microsoft.com/en-us/azure/load-balancer/skus) - Ideal for small scale application

### GSLB(Global Server Load Balancers) Solutions (Global Server Load Balancers are used to distribute traffic across multiple data centers and multiple cloud providers. They are used to provide high availability and disaster recovery.)

1. [Amazon Route 53](https://aws.amazon.com/route53/) - Amazon Route 53 is a highly available and scalable cloud Domain Name System (DNS) web service.
2. [Google Cloud Platform Load Balancer & Cloud DNS](https://cloud.google.com/dns) - Reliable, resilient, low-latency DNS serving from Google's worldwide network with everything you need to register, manage, and serve your domains.
3. [Azure Traffic Manager](https://azure.microsoft.com/en-us/products/traffic-manager/) - DNS-based load balancing
