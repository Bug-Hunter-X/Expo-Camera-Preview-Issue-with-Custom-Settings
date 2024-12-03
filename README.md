# Expo Camera Preview Rendering Issue

This repository demonstrates a bug encountered when using the Expo Camera API with custom camera configurations. The camera preview fails to render, yet no errors are logged to the console. The issue seems to stem from an asynchronous operation conflict within the camera component.  This repository includes the buggy code and a proposed solution.

## Bug Report

The problem lies within the specific configuration of the camera. Certain combinations of options, like setting specific resolutions or frame rates, can prevent the preview from rendering correctly. The behaviour is intermittent.  The original code is in `bug.js`.