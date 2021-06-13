# acme

## Name
*acme* automates certificate management, issuance and revocation.

## Description

## Syntax
~~~txt
acme DOMAIN_NAME {
    challenge {
        http01 PORT |
        tlsalpn PORT
    }
}
~~~

*  The default ports of the challenges, `tlsalpn` and `http01`, are 443 and 80 respectively. They will be used if no port is provided.
* DNS01 will always be used.

You can specify one or more challenges the CA can use to verify that
you own the domain.

## Examples
## See Also
