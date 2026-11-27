# Home-lab

## Objectivo
Construir un laboratorio virtual para practicar redes, administración de sistemas y monitorización de securidad

## Arquitectura
```mermaid
flowchart TD
    A((Internet)) --> B[OPNsense Firewall]
    B --> C[Internal Network]

    C --> D[Ubuntu Server]
    C --> E[Kali Linux]
    C --> F[Metasploitable 2]
    C --> G[Windows Server]
    C --> H[Windows 11]

    D --> J[Wazuh]

## Entorno
- Hypervisor: [VirtualBox]
- OPNsense []: []
- Ubuntu Server [24.10]: []
- Kali Linux []: []
- Wazuh [4.14]: []
- Windows 11 []: []
