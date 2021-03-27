
# Apache::Access::Headers

mod_perl HTTP header authorization module

## Documentation

```
NAME
    Apache::Access::Headers - mod_perl HTTP header authorization module

SYNOPSIS
     # in httpd.conf
     PerlSetVar HeadersAccessConf conf/headers_access.conf

     DocumentRoot /usr/local/apache/htdocs
     <Directory "/usr/local/apache/htdocs">
        PerlModule Apache::Access::Headers
        PerlAccessHandler Apache::Access::Headers
     </Directory>

DESCRIPTION
    This module is intended to be used as a mod_perl PerlAccessHandler. It's
    function is to authorize requests for server resources based on the
    existence of and content of HTTP headers.

    Authorizing HTTP headers may be be set by a web browser, a software
    agent, or an authenitcating proxy server. This module was originally
    written to work with the latter.

    Note: The default reponse from the handler is currently FORBIDDEN. This
    behavior is not yet configurable.

    [...]
```

#### Complete Documentation

- [Original README](README.txt)

## CPAN Links

- https://metacpan.org/source/JEFFO/Apache-Access-Headers-0.01
- https://metacpan.org/author/JEFFO
