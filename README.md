# DomainGen
This script generates a domain name based on either the public IP address of the machine or a custom IP address.

# Examples:

- Generates a domain name based on the public IP address:<br>
`curl -s https://fastly.jsdelivr.net/gh/pmkol/domaingen@tbcache/domaingen | bash`

- Generates a domain name based on the custom IP address:<br>
`curl -s https://fastly.jsdelivr.net/gh/pmkol/domaingen@tbcache/domaingen | bash -s 127.0.0.1`
