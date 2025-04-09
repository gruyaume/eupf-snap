# eUPF Snap

[eUPF](https://github.com/edgecomllc/eupf) is 5G User Plane Function (UPF) based on eBPF.

The snap for eUPF is the simplest way to get operate eUPF on Linux systems.

## Usage

```bash
sudo snap install eupf
sudo snap connect eupf:network-control
sudo snap connect eupf:process-control
sudo snap connect eupf:sys-fs-bpf-upf-pipeline
sudo snap connect eupf:system-observe
```

Edit the configuration file at `/var/snap/eupf/common/config.yaml`

Start the service:

```shell
sudo snap start eupf
```
