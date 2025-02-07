# Multipass Example

Deliver Tomcat Web Application to local Multipass VMs by root moudle.

```bash
# setup infra
$ tf apply -auto-approve \
  -target=multipass_instance.example

# create service
$ tf apply -auto-approve
```

<!-- BEGIN_TF_DOCS -->
## Requirements

| Name | Version |
|------|---------|
| <a name="requirement_terraform"></a> [terraform](#requirement\_terraform) | >= 1.0 |
| <a name="requirement_courier"></a> [courier](#requirement\_courier) | >= 0.0.8 |
| <a name="requirement_multipass"></a> [multipass](#requirement\_multipass) | >= 1.4.2 |

## Providers

| Name | Version |
|------|---------|
| <a name="provider_multipass"></a> [multipass](#provider\_multipass) | >= 1.4.2 |

## Modules

| Name | Source | Version |
|------|--------|---------|
| <a name="module_this"></a> [this](#module\_this) | ../.. | n/a |

## Resources

| Name | Type |
|------|------|
| [multipass_instance.example](https://registry.terraform.io/providers/larstobi/multipass/latest/docs/resources/instance) | resource |
| [multipass_instance.example](https://registry.terraform.io/providers/larstobi/multipass/latest/docs/data-sources/instance) | data source |

## Inputs

No inputs.

## Outputs

| Name | Description |
|------|-------------|
| <a name="output_context"></a> [context](#output\_context) | n/a |
| <a name="output_refer"></a> [refer](#output\_refer) | n/a |
| <a name="output_connection"></a> [connection](#output\_connection) | n/a |
| <a name="output_address"></a> [address](#output\_address) | n/a |
| <a name="output_ports"></a> [ports](#output\_ports) | n/a |
| <a name="output_endpoints"></a> [endpoints](#output\_endpoints) | n/a |
<!-- END_TF_DOCS -->
