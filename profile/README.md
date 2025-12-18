## Project Dependency Tree
```mermaid
flowchart TD
    A(rust-ffmpeg-sys) --> B(rust-ffmpeg)
    D(nvidia-video-codec-rust) --> E
    F{{cudarc: Not Owned}} --> D
    F --> E(Aperture)
    B --> E
```
