# tomaru

<i>The pomodoro timer project I've wanted but not found, so I'm building one for myself</i>

## Technologies
- Rust 🦀
- Tauri for cross platform build & deployment
- Leptos for UI
  
## Development Roadmap
### MVP - CLI
- CLI tool 
- Simple, easy to configure settings via command line flags and a default config file:
  - work period length
  - short break
  - long break
  - number of cycles before long break
- Visible and audible notifications on all platforms (using system notifications where possible)
- Mac / Windows / Linux (WSL) support

### Phase 2 - Native
- Compile to web and native mobile and desktop platforms with simple UI
- Add synchronization for web (allow multiple users to share a timer via URL)

### Phase 3 - Embedded
- Build an esp32 based standalone timer device with LEDs, e-ink screen and small speaker that runs same/derived code for core logic
