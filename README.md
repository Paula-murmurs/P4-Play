# P4-Play
Record something useful information and experiments on P4. 

## Usage

This repository will record some information about how I learn P4 from hardly without any knowledge about networking. 
So it will have some basic concept about `networking command in Linux`, `mininet API learning`, and some `P4 spec` knowledge I read from [`p4.org/specs`](https://p4.org/specs/), like `PSA`, `P4_16`. All the practices will base on `P4_16` to illustrate.

* Repository Structure
    * [Installation](Installation/)
        * About install the p4 develop requirement environment. See more under this folder.
    * [P4-playground](P4-playground/)
        * [multiswitch](P4-playground/multiswitch)
            * Using `mininet` with python API support
            * Contain some experiments with P4 and multiple switches scenario.
                * `basic forwarding`
                * `multi-hop route inspection`
                * `load balancing (ECMP)`
        * [run-directly](P4-playground/run-directly)
            * Using `ip` command to build the network environment with single switch.
            * And then using `simple_switch` with P4 directly.
        * [run-mininet](P4-playground/run-mininet)
            * Using `mininet` to build the network environment with single switch.
            * And then using `p4_mininet.py` as P4 class.
            * Implement the basic forwarding scenario.
        * [net_build](P4-playground/net_build)
            * python script for building those scenario.
        * [psa](P4-playground/psa)
            * Record some P4 programs.
    * [Resource](Resource/)
        * Contain the image usage, flowchart source.
    * [docs](docs/)
        * Recording some useful information when you coding an P4 program.
        * And using `papogen` to generate them into static webpages.

## Some notes 

* Check out docs/
    * using command `make` to generate it.
    * using `papogen` as generator.

## About me

* [kevinbird61(Kevin Cyu, 瞿旭民)](https://github.com/kevinbird61)
    * Nation Cheng-Kung University. Major in `Software-defined network`, especially focus on `P4`.

## Some learning notes 

> This part record about some learning notes of mine, (About `P4`)
> Might help somebody know about `P4` quickly !

* [P4 Introduction/with tutorial - `Chinese`](http://slides.com/kevinbird61/p4/fullscreen)

## Reference

Record some good website about catch up P4 concept.

* [Official website of P4](https://p4.org/specs/)
    * The latest specification about P4.
* [SDNLAB - P4](https://www.sdnlab.com/tag/p4/)
    * Some useful information in Chinese.
* [p4lang - github](https://github.com/p4lang)
    * tutorials about P4 goes here.
* [Some good learning materials](LEARNING_MATERIALS.md)
