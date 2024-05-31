# eUPF Snap

[eUPF](https://github.com/edgecomllc/eupf) is 5G User Plane Function (UPF) based on eBPF.

The snap for eUPF is the simplest way to get started with eUPF on Ubuntu.

## Usage

```bash
sudo snap install eupf
sudo snap connect eupf:network-control
sudo snap connect eupf:process-control
sudo snap connect eupf:bpf
sudo snap start eupf
```

## Configuration

Update the configuration file at `/var/snap/eupf/common/config.yaml` following the syntax outlined [here](https://github.com/edgecomllc/eupf/blob/main/docs/Configuration.md), then restart the service.

```bash
sudo snap restart eupf
```
