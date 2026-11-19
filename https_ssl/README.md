# https_ssl

Project on DNS, load balancing and HTTPS.

## Files

- `0-world_wide_web`: Bash script that audits a domain's subdomains (`www`, `lb-01`, `web-01`, `web-02`). It prints each record type and destination. Pass a domain, and optionally a subdomain.

## Usage

    ./0-world_wide_web example.com
    ./0-world_wide_web example.com web-02
