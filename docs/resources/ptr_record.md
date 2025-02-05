---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "infoblox_ptr_record Resource - terraform-provider-infoblox"
subcategory: ""
description: |-
  
---

# infoblox_ptr_record (Resource)





<!-- schema generated by tfplugindocs -->
## Schema

### Required

- `ptrdname` (String) The domain name in FQDN to which the record should point to.

### Optional

- `cidr` (String) The network address in cidr format under which record has to be created.
- `comment` (String) A description about PTR record.
- `dns_view` (String) Dns View under which the zone has been created.
- `ext_attrs` (String) The Extensible attributes of PTR record to be added/updated, as a map in JSON format
- `ip_addr` (String) IPv4/IPv6 address for record creation. Set the field with valid IP for static allocation. If to be dynamically allocated set cidr field
- `network_view` (String) Network view name of NIOS server.
- `record_name` (String) The name of the DNS PTR record in FQDN format
- `ttl` (Number) TTL attribute value for the record.

### Read-Only

- `id` (String) The ID of this resource.


