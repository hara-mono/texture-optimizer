# Blender Texture Optimizer (BTO)
![Version](https://img.shields.io/badge/version-1.0.0-8A2BE2)
![Blender](https://img.shields.io/badge/Blender-3.6%2B-orange)
![License](https://img.shields.io/badge/license-GPLv2-blue)
![Status](https://img.shields.io/badge/status-production_ready-success)

**Reduce Blender texture memory safely in seconds.**

**Blender Texture Optimizer** is a lightweight production utility that helps artists reduce VRAM usage, shrink oversized textures, and clean up bloated scenes without breaking materials or disrupting workflows.

Built for Blender artists, game developers, and technical artists, BTO scans your entire scene, identifies wasteful texture usage, and generates safe optimization recommendations that can dramatically reduce memory usage in just a few clicks.

> Make existing Blender scenes lighter without rebuilding materials manually.

## 🚀 Features
### Intelligent Scene Analysis
Quickly scan your Blender scene to detect:
- oversized textures
- duplicate images
- packed textures
- inefficient file formats
- excessive VRAM usage
- missing or unused texture maps

BTO builds a clear optimization report so you instantly know what's consuming memory.                    

---
### Smart Optimization Recommendations
BTO automatically generates optimization suggestions based on texture type, resolution, and usage context.

Recommendations are grouped into simple safety tiers:
- 🟢 Safe — Low-risk optimizations suitable for most production scenes
- 🔵 Balanced — Moderate reductions with minimal visible impact
- 🟡 Review — More aggressive optimizations requiring manual inspection

Review items are automatically disabled by default to help protect important hero textures and detailed assets.

---
### Batch Texture Downscaling
Resize oversized textures in bulk using customizable optimization presets and maximum texture size limits.

Reduce texture memory usage across entire scenes in a single pass.

---
### Batch Texture Conversion
Convert inefficient texture formats automatically:
- PNG → WebP
- PNG → JPEG
- TIFF → PNG
- EXR → PNG (*optional*)

Optional preservation settings help retain:
- alpha channels
- original source files
- non-destructive workflows

---
### Duplicate Texture Detection & Cleanup
Detect duplicate textures by analyzing:
- image dimensions
- file hashes
- texture contents

BTO can automatically relink materials to a single master texture datablock to reduce redundant memory usage and scene clutter.

---
### Real-Time VRAM & Storage Analytics
See immediate before-and-after optimization impact including:
- estimated GPU VRAM usage
- disk storage savings
- texture count reductions
- duplicate cleanup totals

Quickly identify the biggest memory offenders in your scene.

---
### Non-Destructive Workflow
All optimizations are designed around safe production usage.

BTO includes:
- original file preservation
- rollbak support
- recovery tools
- optional backup generation

Optimize confidently without permanently damaging source assets.

## 🛠️ Installation
1. Download the `BlenderTextureOptimizer.zip` package.
2. In Blender, open **Edit** → **Preferences** → **Add-ons**.
3. Click **Install**...
4. Select the downloaded `.zip` file.
5. Enable **Optimization: Blender Texture Optimizer**
6. Open the **Optimization** tab in the 3D Viewport sidebar (`N` panel).

## Quick Start
1. Choose an optimization preset such as:
   - Game Ready
   - Mobile
   - VRChat Quest
   - Portfolio Render
   - Web Optimized
2. Set your desired **Max Texture Size**
3. Click **Analyze Scene**
4. Review the generated optimization recommendations
5. Click **Optimize Selected** to apply changes safely 

## ⚠️ Current Limitations
### Saved Projects Required
BTO Requires a saved `.blend` file before optimization can begin so texture paths and local asset operations can be resolved safely.

---
### File-Based Texture Scope
BTO currently analyzes:
- disk-backed textures
- packed images
- external image files

Procedural shader-generated textures and dynamic render outputs are excluded from optimization passes.

---
### Compression Results Vary
Optimization savings depend heavily on:
- original texture formats
- compression levels
- alpha usage
- image content complexity

Some already-compressed textures may show smaller reductions than large uncompressed maps or EXR sources.
