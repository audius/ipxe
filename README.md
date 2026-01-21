# ipxe

Allow to boot your machine from the network. 

```bash
iPXE> dhcp
```

Load the [netboot.xyz](https://netboot.xyz/docs/quick-start):

```text
iPXE> chain --autofree http://boot.netboot.xyz/ipxe/netboot.xyz.lkrn
```

Choose *iPXE shell* and then load a `*.ipxe`  from this repo.

```text
iPXE> chain https://raw.githubusercontent.com/audius/ipxe/master/rocky-10.ipxe
```
