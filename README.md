# Description
This a public repository of some of the shaders that I converted from ShaderToy.com into SparkSL (GLSL 1.0 superset) for fun, 
- ShaderToy is quadtree random sampling
- OSCL2 is an oscilloscope effect, For the texture coordinates, there are two kind of texture coordinates. One is normalized texture coordinates, which is in the range [0, 1]. The other is texel space, which is in the range [0, size), where size is the size of the texture. For texelFetch(), the texel space is used. I could never actually get this one to work. I could'nt run the texelFetch on the phone BUT it worked on my laptop. Probably would work on a Android, was unsure of how to debug
- CRT-Shader provides a noticeable scanline effect and appears blurry

see the shaderCodeAsset.sca for the Shader Language

# Installation
You will need a version of the Meta Spark Studio.
You should be able drag and drop the project file in a 'New Project'


# Meta-Spark-Shaders
The shader code asset allows you to program your own shaders using SparkSL, Meta Spark's own shading language.
As a superset of GLSL 1.0, SparkSL provides a number of features in addition to the usual data types and functions

A shader is a set of algorithms that determines the appearance of a 3D object's surface. They're particularly useful for applying complex changes to a material. Visual shaders can be used to determine the appearance of an object, instead of applying Meta Spark Studio's built-in shaders through the Inspector.


# Discontinued
Meta Spark’s platform of third party tools and content will no longer be available effective January 14, 2025.
