# GPUEnablerExample

This is a sample program which is used to demonstrate the capabilities of the GPUEnabler package found under [this link](https://github.com/IBMSparkGPU/GPUEnabler).

To run this program, as a pre-req [GPUEnabler package](https://github.com/IBMSparkGPU/GPUEnabler) should be installed. Then run the following command after cloning this project,

* mvn scala:run -DmainClass=com.ibm.sample.GpuEnablerExample

The GPU native program can be found under src/main/resources along with the Makefile. The GPU binary "GpuEnablerExamples.ptx" is generated for the GpuEnablerExamples.cu program by running the "make" command from the directory src/main/resources.

