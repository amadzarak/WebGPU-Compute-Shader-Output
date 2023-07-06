# WebGPU-Compute-Shader-Output
quick and dirty webgpu output. i was having some trouble with actually being able to use the output from webgpu shaders. i still have quite 
a bit to learn, as this is my first foray into graphics programming.

i was going to keep this repo private, as i only was testing a few things for a larger project. but then i figured anyone else
that is a beginner to webgpu can use this code a reference also.

the code is divided into two parts, the compute shader and then the draw function. for my purposes, the value of the matmul operation
was more important. i suppose if you want you could extend this into some sort of gpu accelerate matrix multiplication calculator.

the main thing different here is that I am not drawing with webgpu, because all I really wanted was the array and nothing else. 
