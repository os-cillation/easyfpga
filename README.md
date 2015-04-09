# easyFPGA
easyFPGA is a toolkit that simplifies the design of FPGA-based systems. For further information regarding its features and for obtaining the hardware, please take a look at [easyfpga.de](http://www.easyfpga.de).

## Wiki
A detailed documentation can be found in the [SDK wiki](https://github.com/os-cillation/easyfpga-sdk-java/blob/master/wiki/README.md) which is included in the easyfpga-sdk-java submodule.

## Cloning
This is the main repository containing everything that is required to use the easyFPGA Java-SDK. The SDK and the HDL sources that are required to build it are included using git submodules. In order to clone everything at once use the recursive switch:

```
git clone --recursive https://github.com/os-cillation/easyfpga.git
```

## Changelog

#### 2015-04-09
* Small wiki changes

#### 2015-02-17
* Add upload tool GUI
* Optimize SoC area usage
* Handle FPGA-Toolchain without shellscript
* Revise board device detection

#### 2015-01-14
* Add upload tool that allows uploading any FPGA binary without using the SDK
* Add standalone application template for developing custom HDL projects
* Revise logging facility

#### 2015-01-08
* Revise build process: Skip synthesis when HDL is unchanged. Merge build and buildFPGA targets
* Revise UART core class and documentation
