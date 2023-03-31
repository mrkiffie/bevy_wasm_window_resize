# Bevy WASM window resize

This crate makes [Bevy](https://github.com/bevyengine/bevy) application canvas match window size.

# Install

```
cargo add bevy_wasm_window_resize

```

# Usage

Just add `WindowResizePlugin`during app creation process.

```rust
use bevy::prelude::*;
use bevy_wasm_window_resize::WindowResizePlugin;

fn main() {
    App::new()
        .add_plugins(DefaultPlugins)
        .add_plugin(WindowResizePlugin)
        .run();
}
```

# Bevy compatibility table
Bevy version | bevy_window_title_diagnostics version
--- | ---
0.10 | 0.1