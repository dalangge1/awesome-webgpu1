# Awesome WebGPU [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Lovely curated list of WebGPU ressources, libraries and tools.

[WebGPU](https://en.wikipedia.org/wiki/WebGPU) is a work in progress Web standard from W3C for modern 3D and GPU computing. Its purpose is to get the best performances from recent GPUs from desktop to mobile. Unlike WebGL, WebGPU is not a port of an existing native API. It borrows concepts from Metal, Vulkan and Direct3D12.

## Contents

- [Websites](#websites)
- [Browser support](#browser-support)
- [Articles](#articles)
- [Tutorial](#tutorial)
- [Demos](#demos)
- [Libraries](#libraries)
- [Videos](#videos)
- [Presentations](#presentations)
- [Community](#community)

## Website

 [GPU for the Web Community Group](https://github.com/gpuweb/gpuweb/wiki/Implementation-Status) - Official website 

[GPUWeb](https://github.com/gpuweb/gpuweb) - Offical Github repository

[WIP Specs](https://gpuweb.github.io/gpuweb/) - Official Specifications

[Firefox Nightly can run WebGPU compute demo](https://www.reddit.com/r/firefox/comments/eu0xxi/firefox_nightly_can_run_webgpu_compute_demo/)

[WebGPU shading language](https://gpuweb.github.io/gpuweb/wgsl.html)

## Browser support

Support is actually available as an experimental feature on [Chrome Canary](https://www.google.com/chrome/canary/), [Edge Canary](https://www.microsoftedgeinsider.com/en-us/download), [Firefox Nightly](https://nightly.mozilla.org/) and [Safari Technology Preview](https://developer.apple.com/safari/technology-preview/).

- [Implementation status](https://github.com/gpuweb/gpuweb/wiki/Implementation-Status) - From Official W3C Group
- [Chrome Platform Status](https://www.chromestatus.com/feature/6213121689518080) - From Chrome dev
- [WebGPU and WSL in Safari](https://webkit.org/blog/9528/webgpu-and-wsl-in-safari/) - From Webkit website
-[WebGPU on iOS](https://mil-tokyo.github.io/webdnn/docs/tips/enable_webgpu_ios.html) - Don't work on my iPhone6+


## Articles

- [Get started with GPU Compute on the Web](https://developers.google.com/web/updates/2019/08/get-started-with-gpu-compute-on-the-web)
- [Implementing WebGPU in Gecko](https://kvark.github.io/web/gpu/gecko/2019/12/10/gecko-webgpu.html)
- [A Taste of WebGPU in Firefox](https://hacks.mozilla.org/2020/04/experimental-webgpu-in-firefox/)
- [From WebGL to WebGPU in Construct](https://www.construct.net/en/blogs/ashleys-blog-2/webgl-webgpu-construct-1519)
- [wgpu-rs on the web](https://gfx-rs.github.io/2020/04/21/wgpu-web.html)

## Tutorials

- [Raw WebGPU](https://alain.xyz/blog/raw-webgpu)
- [WebGPU training](https://github.com/drawmindmap/webgpu-training) - Not finished
- [Real-Time Ray-Tracing in WebGPU](https://maierfelix.github.io/2020-01-13-webgpu-ray-tracing/)

## Libraries

- [Babylon.js](https://doc.babylonjs.com/extensions/webgpu) - Experimental support
- [Three.js](https://github.com/takahirox/THREE.WebGPURenderer) - Experimental support
- [Dawn](https://dawn.googlesource.com/dawn) - Google implementation
- [Gfx-rs/wgpu](https://github.com/gfx-rs/wgpu) - Mozilla implementation
- [Webcore module WebGPU](https://trac.webkit.org/browser/webkit/trunk/Source/WebCore/Modules/webgpu) - Webkit / Safari

## Demos

If they are not from Apple, demos will work only on Chrome. Firefox implementation is not complete.

- [Safari Webkit demos](https://webkit.org/demos/webgpu/)
- [WebGPU Samples](https://austineng.github.io/webgpu-samples/) - by Austin Eng (Google)
- [WebGPU study](https://redcamel.github.io/webgpu/) - by [Redcamel](https://github.com/redcamel)
- [Small examples of SPIR-V compatible WebGPU usage](https://tsherif.github.io/webgpu-examples/) - by [Tarek Sherif](https://github.com/tsherif)
- [Three.js WebGPURenderer](https://takahirox.github.io/THREE.WebGPURenderer/examples/index.html) - by [Takahiro](https://github.com/takahirox)
- [WebGPU point cloud](https://github.com/m-schuetz/webgpu_pointcloud) - by [Markus Schütz](https://github.com/m-schuetz)
- [Forest WebGPU](https://www.babylonjs.com/demos/webgpu/forestwebgpu) - by Babylon.js

## Videos

- [From WebGL to WebGPU: A perspective from Babylon js by David Catuhe](https://www.youtube.com/watch?v=A2FxeEl4nWw)
- [Next-Generation 3D Graphics on the Web (Google I/O ’19)](https://www.youtube.com/watch?v=K2JzIUIHIhc)
- [000 : INTRO : WebGL 2 WebGPU](https://www.youtube.com/watch?v=iKzbTB9XCq4)
- [001 : A Triangle : WebGL 2 WebGPU](https://www.youtube.com/watch?v=nLe4QMieQYs)

## Presentations

- [Google Tint](https://docs.google.com/presentation/d/1qHhFq0GJtY_59rNjpiHU--JW4bW4Ji3zWei-gM6cabs/edit#slide=id.p) - Proposal for textual shader language
- [Building WebGPU with Rust](https://fosdem.org/2020/schedule/event/rust_webgpu/) - By [Kvark](https://github.com/kvark) from Mozilla

## Community

- [Public GPU](https://lists.w3.org/Archives/Public/public-gpu/) - W3C Mailing list
- [Gitter chat](https://gitter.im/gfx-rs/webgpu) - by Mozilla - DEPRECATED
- [Matrix WebGPU](https://matrix.to/#/#WebGPU:matrix.org) - Unofficial channel

### Bug support
- [Webkit](https://bugs.webkit.org/buglist.cgi?bug_status=UNCONFIRMED&bug_status=NEW&bug_status=ASSIGNED&bug_status=REOPENED&component=WebGPU)
- [Firefox](https://bugzilla.mozilla.org/buglist.cgi?product=Core&component=Graphics%3A%20WebGPU)
- [Chromium](https://bugs.chromium.org/p/chromium/issues/list?q=component:Blink%3EWebGPU)

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.


## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, Mik BRY has waived all copyright and
related or neighboring rights to this work.
