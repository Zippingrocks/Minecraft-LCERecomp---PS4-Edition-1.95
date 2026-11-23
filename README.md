# Minecraft LCERecomp - PS4 Edition 1.95

A static recompilation project targeting **Minecraft: PlayStation 4 Edition 1.95**, the final retail release of Minecraft: Legacy Console Edition developed by 4J Studios.

## Goal

Recompile the final Legacy Console Edition release into a native executable for modern host platforms while preserving the behavior, visuals, world formats, and gameplay of the original retail build.

The initial host target is Windows x64. Additional hosts may follow after the original build is running reliably.

## Status

Early research and project setup. No playable build is available yet.

## Scope

- Target one exact retail executable: PS4 Edition 1.95.
- Build a native runtime around statically translated game code.
- Preserve original gameplay behavior before adding extensions.
- Validate behavior against a legally obtained retail copy.
- Keep platform replacement code separate from translated game code.
- Do not distribute proprietary game code, executables, keys, or assets.

Xbox 360 TU75 and other Legacy Console releases may be used as behavioral and architectural references, but PS4 Edition 1.95 is the canonical target.

## Repository plan

```text
config/       Build fingerprints, symbol maps, and recompilation configuration
runtime/      Host platform, graphics, audio, input, filesystem, and networking
patches/      Version-specific hooks and compatibility fixes
tools/        Executable preparation and analysis tools
docs/         Architecture, research, and compatibility notes
tests/        Runtime and retail-parity tests
generated/    Locally generated recompilation output; never committed
```

## Original game files

This repository does not contain Minecraft, PS4 system software, retail executables, decrypted binaries, title updates, or copyrighted game assets.

Users and contributors must provide files from their own legally obtained copy. Local retail files and generated recompilation output must remain outside version control.

## Project identity

**Project:** LCERecomp  
**Canonical build:** Minecraft: PlayStation 4 Edition 1.95  
**Original developer:** 4J Studios  
**Initial host:** Windows x64

This is an independent preservation and compatibility project. It is not affiliated with or endorsed by Mojang Studios, Microsoft, Sony Interactive Entertainment, or 4J Studios.
