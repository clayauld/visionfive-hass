# StarFive VisionFive Development for Home Assistant

The intent of this project is to develop/port [Home Assistant](homeassistant.io) over to the [StarFive VisionFive RISC-V SBC](https://rvspace.org/en/Product/VisionFive/Technical_Documents/VisionFive_Single_Board_Computer_Quick_Start_Guide).

This repo will be updated as the development work proceeds.

The plan is to develop a docker container for RISC-V that will contain all the required dependencies to run Home Assistant. The current Home Assistant docker containers are not ported over to RISC-V.

The current Docker image is a RISC-V fork of [Linuxserver.io/docker-homeassistant](https://gitlab.com/Linuxserver.io/docker-homeassistant/) based on the Debian-unstable slim base image. See the Linuxserver.io repo for more information.
