# Opensource

A list of opensource contribution I made during my studies

## [openapi-fuzzer](https://github.com/matusf/openapi-fuzzer)

openapi-fuzzer is a tool to test if there's difference between the OpenApi definition and the behavior of API endpoints. I used this project to test the [nethsm](https://github.com/Nitrokey/nethsm) API in a CI. I needed the fuzzer to connect using HTTPS without checking the certificates so I modified the project to allow this and then proposed the modification on the upstream repository. This change also changed the way connections are handled, improving performances.

- State of the project : in production
- Community : not very active
- Stack : Rust, OpenApi

## [ureq](https://github.com/algesten/ureq)

Ureq is a library to make HTTP requests in rust synchronously. I started contributing to add a feature to retrieve all headers in one function call. This would improve performance in nethsm-pkcs11. My contribution is not yet merged.

- State of the project : in production
- Community : active
- Stack : Rust

## [discordgo](https://github.com/bwmarrin/discordgo)

Discordgo is a library for making discord bot in go. I found a small bug and decided to fix it in a pull request.

- State of the project : in production
- Community : not very active
- Stack : Go, Discord API

## [openapi-json-schema-generator](https://github.com/openapi-json-schema-tools/openapi-json-schema-generator)

openapi-json-schema-generator is a tool to generate source code from an OpenApi definition. I used it when working on pynitrokey and [nethsm-sdk-py](https://github.com/Nitrokey/nethsm-sdk-py) and found some issues with types, the handling of query parameters in paths and handling of content types. I only reported the issues and gave feedback (no code contribution).

- State of the project : in production
- Community : somewhat active
- Stack : Python, OpenApi

## [Aster](https://github.com/aster-do/aster)

Aster is a metrics collector that can be used to charge customers based on these metrics, it also includes a dashboard to configure how the user is billed based on the different metrics and explore the metrics data.
This was a school group project, I mainly worked on the presentation of the data and the frontend infrastructure.

- State of the project : not deployed
- Community : inactive
- Stack : Rust, Axum, Typescript, React.js

## [Faast](https://github.com/faast-rt)

A serverless runtime that manages microVMs to execute code on demand. This is a school group project where I mostly worked on the lumper component, making MMIO possible for virtio-net and adding documentation.

- State of the project : not deployed
- Community : inactive
- Stack : Rust, KVM, Virtio

## [Oh my ade](https://gitlab.com/nilsponsard/oh-my-ade)

Oh my ade is an app I created to display plannings provided by Adesoft's pladform. Some students are using it.

- State of the project : in production
- Community : not very active
- Stack : Typescript, React.js

## [TourDO](https://github.com/nponsard/tourdo-backend)

A tournament management web application made for a school project.

- State of the project : not deployed
- Community : inactive
- Stack : Typescript, React.js, Deno


## [pynitrokey](https://github.com/Nitrokey/pynitrokey)

Pynitrokey is a tool to interact with and configure Nitrokey devices. I contributed to the improvement of the part that interacts with NetHSM. These improvements added new functions, made the code clearer and fixed some bugs.

- State of the project : in production
- Community : active
- Stack : Python


## [NetHSM](https://github.com/Nitrokey/nethsm)

NetHSM is a project started by Nitrokey for creating an open source Hardware Security Module accessible from the network.
During my internship I worked on the NetHSM firmware that is now open source on GitHub. I mainly worked on improving the CI and test cases.

- State of the project : in production
- Community : small, not very active
- Stack : Ocaml, MirageOS

## [nethsm-pkcs11](https://github.com/Nitrokey/nethsm-pkcs11)

This is the main project I worked on during my internship, the goal is to create a PKCS#11 module so applications implementing the PKCS#11 protocol can use a [NetHSM](https://www.nitrokey.com/products/nethsm) without needing to modify the application. I did most of the developpement and now I'm helping the team to matain the project.

- State of the project : in production
- Community : small, not very active
- Stack : Rust, C library, PKCS#11
