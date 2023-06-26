role infrastructure_satellite
=======================================

Registers the nodes against Red Hat Satellite, so that they are properly subscribed to a Red Hat subscription using a activation key 
and with SCA (simple content access) enabled.


Requirements
------------

* Make sure you use a Satellite credential that fills the environment variables `SATELLITE_RHN_CREDENTIAL_ID` and `SATELLITE_RHN_PASSWORD`.


Variables
---------

### Required variables
```yaml
satellite_server: hostname.of.satellite
satellite_environment: Development/ccv-linux  # {Lifecycle environment name}/{content view name}



### Optional variables

```yaml
```
