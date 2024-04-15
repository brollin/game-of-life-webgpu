# WebGPU learnings

Following along with
https://codelabs.developers.google.com/your-first-webgpu-app#0

Clip space: the canvas will ALWAYS be in this. Left edge is at -1, right edge is
at +1. Bottom edge is -1, etc. Doesn't matter how big or small the canvas is.

The purpose of a vertex shader is to transform the location of a given vertex
into clip space.
