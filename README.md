# Aesthetic Persona Schema

> **v0.1.0-beta** — A comprehensive JSON Schema for defining visual and stylistic identity archetypes used in **concept art, AI image generation, character design**, and **creative workflows**.

Supports **SFW and NSFW** content with anatomically detailed, enum-driven fields for consistency across tools and teams.

---

## Purpose

This schema enables:
- **Consistent character design** across artists, AI models, and pipelines
- **Reusable persona templates** for games, novels, AI prompts, or mood boards
- **Structured data** for UI tools, databases, or generative AI backends
- **Version-controlled evolution** of character aesthetics

---

## Features

| Category | Highlights |
|--------|------------|
| **Identity** | Name, aliases, description |
| **Core Aesthetics** | Body type, facial features, posture |
| **Stylistic Atmosphere** | Color palette, lighting, fashion, symbolic elements |
| **Anatomical Detail** | Hair, skin (with regional variation), breasts, hips, genitals, etc. |
| **Technical Layer** | Prompt tags, negative tags for AI generation |
| **Mood Board** | Reference image URLs, sketches |
| **Versioning** | Schema version + JSON Schema spec compliance |

---

## Schema Overview

```json
{
  "aesthetic_persona": {
    "version": "v0.1.0",
    "identity": { ... },
    "core_aesthetic_traits": { ... },
    "anatomical_description": {
      "skin": { "overall_tone": "caramel", "freckles": { ... } },
      "hair": { "length": "long", "type": "wavy" },
      "breasts": { ... },
      "genitals": { "female": { ... } }
    },
    ...
  }
}
