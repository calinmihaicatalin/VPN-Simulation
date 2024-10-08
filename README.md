# VPN Network Simulation Project
This served as my thesis application for my bachelor’s degree.

Video showcase of the project:
https://youtu.be/D0MvT9yMRUU 

Overview

This project demonstrates the implementation of a Virtual Private Network (VPN) using OpenVPN. The aim is to provide a secure and encrypted connection between a client and a server, allowing users to access a private network remotely while protecting sensitive data from unauthorized access.
Objectives

    Implement a VPN server and client using OpenVPN.
    Configure Public Key Infrastructure (PKI) with EasyRSA for secure certificate management.
    Utilize encryption algorithms such as AES for data security and RSA for key exchange.
    Monitor network traffic using Wireshark to ensure data integrity and confidentiality.

Features

    Secure Tunneling: Establishes a secure connection through tunneling protocols, ensuring data protection over public networks.
    Encryption: Implements AES for encrypting the data transmitted over the VPN, providing confidentiality and security.
    Key Exchange: Utilizes Diffie-Hellman for secure key exchange, enhancing security during the connection establishment.
    Traffic Monitoring: Employs Wireshark to analyze network traffic and verify encryption and data integrity.

Implementation Details

    Setup: Configured OpenVPN server and client, including all necessary dependencies.
    Certificate Management: Created and managed certificates using EasyRSA for secure client-server authentication.
    Encryption Configuration: Implemented AES and RSA encryption in the OpenVPN configuration files.
    Traffic Analysis: Used Wireshark to capture and analyze network packets, ensuring secure data transmission.

Conclusion

This VPN simulation serves as a practical demonstration of the theoretical concepts studied in network security, showcasing how VPNs protect communications and sensitive data in a corporate environment.
