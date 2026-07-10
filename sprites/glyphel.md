# Glyphel — Poke-issue-dex №34

*The Fault Pokémon*

![Glyphel](glyphel.png)

**Type:** bug

**Rank:** medium

**Species:** Fault Pokémon  
**Height:** 0.4 m   **Weight:** 25.3 kg

> Glyphel is the Rendering Pokémon — a meticulous card-scribe that lives inside the Region Safari's info-card pop-up. Today the card betrays it: markdown in an issuemon's description surfaces as raw glyphs (**bold**, `code`, bullet lists, and [links]) instead of formatted text, and the pop-up shows only a name and number with no face at all. Glyphel escapes every character first, then re-etches a safe subset of markdown — bold, italic, inline code, bullet lists, links, and line breaks — so untrusted issue text can never inject markup, and it pins the issuemon's own sprite into the card head so the pop-up finally mirrors the creature you clicked. Where Glyphel passes, the info card reads clean and looks like the monster it describes.
