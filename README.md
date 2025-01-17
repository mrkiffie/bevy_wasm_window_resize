# Bevy WASM window resize

This crate makes [Bevy](https://github.com/bevyengine/bevy) application canvas match window size.

Original idea and code behind: [ManevilleF](https://github.com/ManevilleF)

# Install

```
cargo add bevy_wasm_window_resize

```

# Usage

Just add `WindowResizePlugin` during app creation process.

```rust
use bevy::prelude::*;
use bevy_wasm_window_resize::WindowResizePlugin;

fn main() {
    App::new()
        .add_plugins(DefaultPlugins)
        .add_plugins(WindowResizePlugin)
        .run();
}
```

# Bevy compatibility table
Bevy version | crate version
--- | ---
0.10 | 0.1.0
0.11 | 0.2.0