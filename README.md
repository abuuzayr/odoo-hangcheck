# odoo-hangcheck

This xmlrpc script will periodically connect to a odoo backend. If it doesn't respond, systemctl restart odoo@&lt;profile&gt; is called.

## Architecture

This script must be in a `m2opg` architecture to work properly.

## Dependencies

This script requires the following libraries to run:

1. python-etcd
2. erppeek
