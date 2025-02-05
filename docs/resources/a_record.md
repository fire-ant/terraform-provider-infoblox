---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "infoblox_a_record Resource - terraform-provider-infoblox"
subcategory: ""
description: |-
  
---

# infoblox_a_record (Resource)





<!-- schema generated by tfplugindocs -->
## Schema

### Required

- `fqdn` (String) FQDN for the A-record.

### Optional

- `cidr` (String) Network to allocate an IP address from, when the 'ip_addr' field is empty (dynamic allocation). The address is in CIDR format. For static allocation, leave this field empty.
- `comment` (String) Description of the A-record.
- `dns_view` (String) DNS view which the zone does exist within.
- `ext_attrs` (String) Extensible attributes of the A-record to be added/updated, as a map in JSON format
- `ip_addr` (String) IP address to associate with the A-record. For static allocation, set the field with a valid IP address. For dynamic allocation, leave this field empty and set 'cidr' and 'network_view' fields.
- `network_view` (String) Network view to use when allocating an IP address from a network dynamically. For static allocation, leave this field empty.
- `ttl` (Number) TTL value for the A-record.

### Read-Only

- `id` (String) The ID of this resource.


