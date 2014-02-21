
![Icinga](screenshot.png)

### icinga configuration

```
define service{
        use                             passive-service         ; Name of service template to use
        host_name                       localhost
        service_description             OwnTracks jpm
        }
define service{
        use                             passive-service         ; Name of service template to use
        host_name                       localhost
        service_description             OwnTracks jjolie
        }

define service{
        use                             passive-service         ; Name of service template to use
        host_name                       localhost
        service_description             OwnTracks andy
        }
```

Requires [pynsca](https://github.com/djmitche/pynsca)
