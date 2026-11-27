# Home-lab

## Objectivo
Construir un laboratorio virtual para practicar redes, administración de sistemas y monitorización de securidad

## Arquitectura
```mermaid
flowchart TD
    A((Internet)) --> B[OPNsense Firewall]
    B --> C[Internal Network]
    B --> E[Host-Only]

    C --> F[Ubuntu Server]
    E --> F[Ubuntu Server]
    C --> G[Kali Linux]
    E --> G[Kali Linux]
    C --> H[Metasploitable 2]
    C --> I[Windows Server]
    C --> J[Windows 11]

    F --> K[Wazuh]
    
```
## Entorno
- Hypervisor: [VirtualBox]
- OPNsense []: []
- Ubuntu Server [24.10]: []
- Kali Linux []: []
- Wazuh [4.14]: []
- Windows 11 []: []
