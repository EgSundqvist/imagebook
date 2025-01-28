# ImageBook Microservices

This repository contains links and documentation for the ImageBook project's microservices.

## Microservices

- [ImageBook Client](https://github.com/EgSundqvist/imagebook-client): Frontend application, built with React and TypeScript.
- [ImageBook User API](https://github.com/EgSundqvist/imagebook-userapi): API for user management, built with Python.
- [ImageBook Image API](https://github.com/EgSundqvist/imagebook-imageapi): API for image management, built with Go.

## Documentation

## Example of application flow

![Example of application flow](https://github.com/EgSundqvist/imagebook/blob/main/ImagebookMicroservicesFlow.png)

## CI/CD and cluster flow

![CI/CD and cluster flow](https://github.com/EgSundqvist/imagebook/blob/main/ImagebookClusterFlow.png)

## Purpose

The purpose of this project has been to build an application according to Cloud Native.
This concept includes: Logic and functionality is divided into small Microservices instead of larger
apis and services.
Container technology such as Docker to package and isolate applications and services and optimize
use of hardware performance.
Orchestration with tools such as Kubernetes for distribution and scaling of
container-based applications.
CI/CD for continuous integration and delivery and automation of workflows and processes in
development such as Codebuild.
In addition, my purpose has also been to develop my knowledge in two previously unfamiliar
languages ​​that are commonly used for building microservices. Go and Python.

## Description and use

Imagebook - Is a web application that is intended as a private photo album.
Currently, the user can register, log in, manage account and profile, upload and delete
images and view their uploaded images in an infinite scroll. There is also a plan to build on the
application and make it more social and interactive by implementing functionality to
be able to interact with other users and view their resources.
