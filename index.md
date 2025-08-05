---
title: Home
layout: home
---

Virtual Mesh is a Nanite-inspired virtualized geometry solution for Unity.

What it can do:

- Continuous LOD graph – meshlets are dynamically selected based on an error metric, ensuring smooth transitions with minimal LOD popping.
- GPU-driven culling – per-instance, per-meshlet, and even per-triangle culling to minimize vertex shader work.
- Fewer draw calls – instances with the same materials are drawn in a single draw call, even if their meshes differ.
- Streaming – mesh vertices and triangles get dynamically loaded/unloaded based on what is currently used and requested on the GPU.

Everything runs in Unity 6 + URP + DX11, with no strict hardware requirements (no need for Mesh Shader support).

<html>
    <video controls width="85%"><source src="/assets/videos/home_page_video.mp4" type="video/mp4" /><video>
</html>