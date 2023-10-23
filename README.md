# WASM-GPT

Run any [ggml-compatible gpt-2](https://huggingface.co/ggerganov/ggml/tree/main) models **natively** in your browser! <br>
Chat with **WASM-GPT** @ https://alexwang0311.github.io/wasm-gpt/

## Description

**WASM-GPT** is an experimental demonstration of the potentials of **WebAssembly** and **Blazor WASM**. <br>
Once the app is downloaded, **WASM-GPT** can run without being connected to the Internet since there is no server-side dependency. In fact, it is even hosted **statically** on **GitHub Pages**. <br>

## Getting Started

### Dependencies

* Visual Studio 2022 with .NET WebAssembly build tools installed
* .NET 7

### Notes

* This project was hacked together over a weekend. There are still lots of issues within the code.
* The files under **\C++** are from **_Georgi_ _Gerganov_**'s [ggml](https://github.com/ggerganov/ggml) library. Some minor tweaks are made to get them compiled to WASM.
* These models aren't meant to be run in a browser environment, please make sure you are using a modern browser and a device with enough computation power.
* **Run on mobile at your own risk lol!**

## Contact

This is an ongoing personal project. If you have any suggestions or would like to collaborate, please feel free to reach out.
* Email: alexwang99311@yahoo.com
* Website: https://alexwang0311.github.io/

## Acknowledgments

Here are some of the inspirations behind this project.
* [ggml](https://github.com/ggerganov/ggml)
* [talk.wasm](https://github.com/ggerganov/whisper.cpp/tree/master/examples/talk.wasm)
* [BlazeOrbital](https://github.com/SteveSandersonMS/BlazeOrbital)
