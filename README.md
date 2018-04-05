# Vulkan-Ecosystem
This repository is used as a tracker for cross-functional issues that affect
Vulkan users. It is meant to facilitate triaging, discussion and routing of
issues that don't necessarily fit under the scope of a single project within
the Vulkan ecosystem.

# Map of Vulkan Ecosystem projects
The Vulkan ecosystem is a big place and there's a lot out there that is useful! In no particular order...

## Vulkan® Specification
Vulkan® Specification - formal documentation of the Vulkan API. This includes the main API Specification, the reference (man) pages, the XML API Registry, and related tools and scripts.

* Landing page: https://www.khronos.org/vulkan/
* Website: https://www.khronos.org/registry/vulkan/
* Repository: https://github.com/KhronosGroup/Vulkan-Docs
* License: [mixed](https://github.com/KhronosGroup/Vulkan-Docs/blob/1.0/COPYING.md) &mdash; approximately:
    * Proprietary Khronos license for the Vulkan Specification published by Khronos on its website
    * CC-BY 4.0 for asciidoctor sources for the Specification and related documents such as the reference pages, style guide, and XML schema documentation.
    * Apache 2 for code, including the XML registry defining API interfaces
* Contacts:
    * [Vulkan forum](https://forums.khronos.org/forumdisplay.php/114-Vulkan)
* Compiler requirements: python 3 (3.4.2 known working), ruby 2 (2.3.3 known working)

## SPIRV-Tools
The SPIR-V Tools project provides an API and commands for processing SPIR-V modules.

* Repository: https://github.com/KhronosGroup/SPIRV-Tools
* License: [Apache](https://github.com/KhronosGroup/SPIRV-Tools/blob/master/LICENSE)
* Contacts:
    * https://www.khronos.org/spir/spirv-tools-mailing-list/
    * David Neto <dneto@google.com>
* Compiler requirements: C++11 compatible compiler (MSVC 2013+ on Windows)

## glslang
glslang is a GLSL and HLSL to SPIR-V compiler, usable both as a command-line tool as well as a library.

* Website: https://www.khronos.org/opengles/sdk/tools/Reference-Compiler/
* Repository: https://github.com/KhronosGroup/glslang
* License: 3-clause BSD
* Contact: David Neto <dneto@google.com>
* Compiler requirements: C++11 compatible compiler (MSVC 2013+ on Windows)

## Vulkan-LoaderAndValidationLayers
Source code for the Vulkan loader and validation layers, Vulkan API header files, demos and tests.

* Repository: https://github.com/KhronosGroup/Vulkan-LoaderAndValidationLayers
* License: [Apache](https://github.com/KhronosGroup/Vulkan-LoaderAndValidationLayers/blob/master/LICENSE.txt)
* Contacts:
    * Tobine Ehlis <tobine@google.com>
    * Mark Lobodzinski <mark@lunarg.com>
* Code of conduct: https://github.com/KhronosGroup/Vulkan-LoaderAndValidationLayers/blob/master/GOVERNANCE.md
* Compiler requirements: MSVC 2013+ / gcc 4.8.2+ / clang 3.4+

## MoltenVK
MoltenVK is an implementation of the high-performance, industry-standard Vulkan graphics and compute API, that runs on Apple's Metal graphics framework, bringing Vulkan compatibility to iOS and macOS

* Repository: https://github.com/KhronosGroup/MoltenVK
* License: [Apache](https://github.com/KhronosGroup/MoltenVK/blob/master/LICENSE)
* Contacts: bill.hollings@brenwill.com
* Compiler requirements: Xcode 9 / asciidoctor / python 3

## Vulkan-HPP
Vulkan-Hpp is a set of lightweight C++ bindings for the Vulkan API.

* Repository: https://github.com/KhronosGroup/Vulkan-Hpp
* License: [Apache](https://github.com/KhronosGroup/Vulkan-Hpp/blob/master/LICENSE.txt)
* Compiler requirements: MSVC 2013+ / gcc 4.8.2+ / clang 3.3+
* Contact: Markus Tavenrath <mtavenrath@nvidia.com>

## SPIRV-Cross
SPIRV-Cross is a practical tool and library for performing reflection on SPIR-V and
disassembling SPIR-V back to high level languages.

* Repository: https://github.com/KhronosGroup/SPIRV-Cross
* License: [Apache](https://github.com/KhronosGroup/SPIRV-Cross/blob/master/LICENSE)
* Contacts:
	* hans-kristian.arntzen@arm.com (@HansKristian-ARM)
* Compiler requirements: MSVC 2013 / gcc 4.8/4.9+ / clang 3.x+

## RenderDoc
RenderDoc - a graphics debugger, currently available for Vulkan, D3D11, D3D12, and OpenGL development on Windows 7 - 10 and Linux.

* Website: https://renderdoc.org/
* Repository: https://github.com/baldurk/renderdoc
* License: [MIT](https://github.com/baldurk/renderdoc/blob/v0.x/LICENSE.md)
* Contacts:
    * baldurk@baldurk.org
    * [#renderdoc on freenode IRC](https://kiwiirc.com/client/irc.freenode.net/#renderdoc)
* Code of conduct: [contributor covenant](https://github.com/baldurk/renderdoc/blob/v0.x/CODE_OF_CONDUCT.md)
* Compiler requirements: MSVC 2015 / gcc 5 / clang 3.4

## VulkanTools
Source code for various Vulkan Tools: vktrace/vkreplay, device simulation layer, API dump layer, fps monitor layer, screenshot layer, assistant layer, layer factory framework, and Vulkan installation analyzer.

* Repository: https://github.com/LunarG/VulkanTools
* License: [Apache](https://github.com/LunarG/VulkanTools/blob/master/LICENSE.txt)
* Contact: David Pinedo <david@lunarg.com>
* Code of conduct: https://github.com/LunarG/VulkanTools/blob/master/GOVERNANCE.md
* Compiler requirements: MSVC 2013+ / gcc 4.8.2+ / clang 3.4+

## gfx-rs
gfx-rs is Vulkan-ic graphics abstraction layer in Rust, running on Vulkan, D3D12, Metal, and OpenGL, as well as providing [C bindings](https://github.com/gfx-rs/portability) as a Vulkan Portability implementation.

* Repository: https://github.com/gfx-rs/gfx
* License: [Apache](https://github.com/gfx-rs/gfx/blob/master/LICENSE-APACHE) or [MIT](https://github.com/gfx-rs/gfx/blob/master/LICENSE-MIT)
* Contacts:
  * [gfx-rs on Gitter](https://gitter.im/gfx-rs/gfx)
  * [Dzmitry Malyshau](mailto:kvarkus@gmail.com)
* Compiler requirements: Rust 1.22, gcc 5 / clang 3.4 for the portability layer

## Vulkano
Vulkano is a type-safe wrapper around Vulkan API in Rust.

* Website: http://vulkano.rs/
* Repository: https://github.com/vulkano-rs/vulkano
* License: [Apache](https://github.com/vulkano-rs/vulkano/blob/master/LICENSE-APACHE) or [MIT](https://github.com/vulkano-rs/vulkano/blob/master/LICENSE-MIT)
* Contacts:
  * [Vulkano on Gitter](https://gitter.im/vulkano-rs/Lobby)
* Compiler requirements: Rust 1.22, gcc-4.8
