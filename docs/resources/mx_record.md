---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "infoblox_mx_record Resource - terraform-provider-infoblox"
subcategory: ""
description: |-
  
---

# infoblox_mx_record (Resource)





<!-- schema generated by tfplugindocs -->
## Schema

### Required

- `fqdn` (String) FQDN for the MX-record.
- `mail_exchanger` (String) A record used to specify mail server.
- `preference` (Number) Configures the preference (0-65535) for this MX-record.

### Optional

- `comment` (String) Description of the MX-Record.
- `dns_view` (String) DNS view which the zone does exist within
- `ext_attrs` (String) Extensible attributes of the MX-record to be added/updated, as a map in JSON format.
- `ttl` (Number) TTL value for the MX-record.

### Read-Only

- `id` (String) The ID of this resource.


