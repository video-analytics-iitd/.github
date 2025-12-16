## Project Dependency Tree
```mermaid
flowchart TD
    A(rust-ffmpeg-sys) --> B(rust-ffmpeg)
    C(ort) --> E(Aperture)
    D(nvidia-video-codec-rust) --> E
    F{{cudarc: Not Owned}} --> C
    F --> D
    F --> E 
    B --> E
```
