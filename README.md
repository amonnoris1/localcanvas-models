# Local Canvas models

On-device Core ML files used by Local Canvas. The iOS app downloads them from the `v1` GitHub Release, then checks each file against a baked-in SHA-256.

This repository does **not** store the weights in git. The Release assets are the source of truth.

These are redistributed copies of third-party Core ML conversions. Original sources and licenses:

| App model | Original repo | License | Pinned revision |
|---|---|---|---|
| CyberRealistic | [LocalMuseAI/coreml-cyberrealistic-v9-6bit](https://huggingface.co/LocalMuseAI/coreml-cyberrealistic-v9-6bit) | CreativeML Open RAIL-M | `bee03429ed90e56825e3cb59cef079909f302da6` |
| Cartoon (ReV Animated) | [darkmaniac7/tokforge-ios-coreml-image-models](https://huggingface.co/darkmaniac7/tokforge-ios-coreml-image-models) | CreativeML Open RAIL-M | `6040f1e761563fd4a9eca2da31bd15726d7b7ba3` |
| DDColor Tiny | [mlboydaisuke/DDColor-Tiny-CoreML](https://huggingface.co/mlboydaisuke/DDColor-Tiny-CoreML) | Apache-2.0 | `48c9a506b578460681078e31378e2eaae424a044` |
| LaMa | [hujaber/mixme-photoedit-models](https://huggingface.co/hujaber/mixme-photoedit-models) | Apache-2.0 | `4c84d86d49d020cbf010c41303ea5c26a78e1bc3` |

Asset names are `{model-id}--{relative-path-with-slashes-as-dashes}`.
