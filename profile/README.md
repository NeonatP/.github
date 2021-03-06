# NeonatP

This project is part of a bachelor work at the [HEIG-VD](https://heig-vd.ch/) conducted during the last academic semester 2022.

## Description

NeonatP is a web platform for the management of medical data related to pain in neonates. This organisation regroups the main building-blocks of the web platform.

## Architecture

The frontend was designed in Vue.js on a SPA (Single-Page-Application) model.

The backend follows a microservice architecture. The microservices developed in this project were realized with the SpingBoot framework, except for the secret manager where Vault is used.

![System](./assets/archi_sys_final.png)

## General deployment instruction

Each service has further deployment instruction explained in their corresponding README. To deploy or test the full platform, you will need to need to follow the instruction of each service in the following order: 

- Back end
  
  - Secret management service (aka Vault)
  
  - Authentication service
  
  - Web App

- Front end

## Members

**Teacher in charge**: Dr. Laura Elena Raileanu

**Student**: Miguel Do Vale Lopes

**Contributors**: Hayman Lotfy, Loïc Dessaules
