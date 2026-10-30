[HibikiStudio Discord](https://discord.gg/Jxj3nQwKj)

[Download latest version](https://github.com/HomuraMiko/HibikiStudio/releases/tag/V0.7.X)

A standalone, hardware-accelerated broadcasting and interactive content creation workstation for Windows.

Hibiki replaces the usual mess of browser sources, virtual audio cables, chat overlays, media players, and bots with a single native application. Everything a live stream needs — compositing, audio routing, chat, alerts, media requests — runs in one place, natively.

![example1](example.png)

![SoundStage](SoundStage.png)

![MediaDeck](MediaDeck.png)

![StreamHub](StreamHub.png)

![RightPanel](RightPanel.png)

Build scenes from window captures, images, text, media players, chat, color fills, and Spout2 VTuber avatar feeds. Drag sources around a live canvas, resize, layer, and switch between scenes with hardware-accelerated transitions — cut, fade, slide, luma wipe, glitch tear, and a glass-shatter physics transition.
Chat bubbles, media items, and props can fall, collide, stack, and break. Objects can be grabbed and thrown with the mouse, pinned in place with hinge joints, or shattered into fragments. Bass hits from audio can kick the floor and launch everything into the air.
A full post-processing pipeline that runs per-source or per-scene. Includes chroma keying (standard and perceptual quality modes), color correction, luma key, audio-reactive scale/shake/bloom/glow, CRT and VHS analog degradation, VHS tape emulation, datamosh glitch, halftone, pixelate, lens distortion, heat haze, animated rain on glass, frosted acrylic glass, normal map refraction, comic outline, night vision, retro pixel upscalers (Scale2x, xBR, 2xSaI), blur suite, drop shadow, sepia, and more.
Connects directly to Twitch chat. Messages can display as a clean scrolling list, an organic sticker-collage layout, or drop as physical objects into the physics arena. Supports animated Twitch and 7TV emotes natively. Alerts for follows, subs, bits, and raids have a two-phase behavior — a spotlight hold, then a physics drop into the arena with impact effects.
Viewers request YouTube tracks via chat command. Hibiki handles playback internally, routing audio through the mixer with no speaker bleed. Includes a threat filter that screens requests against blacklists and keywords before they play.
Six independent audio buses covering microphone, media player, song requests, background music, application capture, and peripherals. Each bus has its own DSP chain: EQ, compressor, expander, noise gate, limiter, pitch/formant shifter, reverb, noise suppression, and more. Auto-ducking, binaural positioning, and per-bus room reverb are also available.
A transparent overlay that sits over full-screen games. Shows broadcast health, live viewer stats, and a floating chat box with animated emotes. A hotkey lets you interact with physics objects directly over your game without alt-tabbing.
Built-in audio player with playlist management, tag-based metadata, auto-ducking when the mic is active, and smooth crossfading between tracks.
Hardware-accelerated H.264 encoding via NVIDIA NVENC. Streams directly to Twitch over RTMP. Local recording to FLV. Twitch title, category, tags, and content labels can be updated from inside the app.
- NVIDIA GPUs only for hardware video encoding (GTX 600 or newer). AMD and Intel support is in progress.
- Dual-track stream/VOD audio separation is partially implemented and may have routing issues.
- VMC head tracking is present but has known calculation issues; a full overhaul is planned.
- AMD AMF & Intel QuickSync encoding support
- CPU x264/x265 fallback encoding
- YouTube Live streaming
- VMC 6-DoF tracking overhaul
- Custom HLSL shader import
- Standalone audio visualizers
- Local chat rewards, channel points, and item shop system
- Custom chat bubble shapes, themes, and animations
