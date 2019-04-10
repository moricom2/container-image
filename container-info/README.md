Gathering the Container Info
============================

### Usage
> docker run --name \<CON_NAME\> -p \<PORT:8080\> -d \<IMAGE\> \<MESSAGE\>

### Example
> docker run --name cinfo -p 80:8080 -d c1t1d0s7/container-info "Hello Docker!"

### Default Message
> Hello World!

### OUTPUT
> curl http://X.X.X.X  
> Message: Hello Docker!  
> Hostname: 25259da8d120  
> Platform: linux  
> Uptime: 17105  
> IP: 172.17.0.2  
> DNS: 192.168.65.1  
