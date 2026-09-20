## Kaala Android Build 21 (v1.0.8) — Shubh Muhurat Hub & Sacred Granths Reader

### ✨ What's New

#### 🪔 1. Shubh Muhurat Hub & Auspicious Timing Finders
- **Dedicated Hub (`/vedic/shubh-muhurat`):** Category discovery for auspicious life rituals with upcoming timing timelines, category cards (Vivah & Griha Pravesh), and Shastric trust explanations (*Muhurta Chintamani*).
- **Interactive Availability Bar & Jump Filters:** 12-month visual availability overview and quick month jump chips on both Vivah and Griha Pravesh screens.
- **Multi-Window & Overnight Clarifications:** Time slots now clearly distinguish multi-window days ("Window 1", "Window 2") and mark overnight windows crossing midnight IST ("Next day").
- **Add to Calendar (.ics export):** One-tap sync of auspicious windows directly to your device calendar.
- **Griha Pravesh Refinements:** Supports Apoorva (new build) and Sapoorva (resale/rental) modes, alongside a Dvara Chakra door direction sheet.

#### 📖 2. Sacred Granths Reader & Search
- **On-Page Search & Filter Chips:** Instantly search sacred texts by title, description, or keyword, and filter across Scriptures, Chalisas, and Aartis.
- **Featured Granth Spotlight:** Dynamic spotlight card for primary granths with reading progress tracking ("Start Reading" / "Continue Reading Chapter N").
- **Reading Options Guide:** Quick discovery for Sanskrit verses, Roman transliteration, translations, and bookmarks.

#### ⏱️ 3. Dedicated Choghadiya & Festival Hub Screens
- **Dedicated `/choghadiya`:** Live active slot status hero, remaining countdown minutes, next auspicious window alert, and 1-tap 9:16 WhatsApp image sharing.
- **Dedicated `/festivals` Hub:** Year toggle, horizontal month strip, category filter chips (Cards, Shaiva, Vaishnava, Shakta, Vrat, etc.), and festival card customization.

#### 🗓️ 4. Modernized Vedic Calendar Grid
- High-contrast day cells with Devanagari tithis and lunar event chips.
- Outbound explorer hubs for quick access to festivals, vrat guides, and muhurats.

#### 🔍 5. Global Search & Editorial Typography
- Full 5-language search parity (`en`, `hi`, `sa`, `ta`, `te`) across destinations, festivals, and live places.
- Premium Marcellus editorial heading typography for English titles.

---

### 🛠️ Bug Fixes & Reliability Hardening
- **Kundli Chart Legend:** Fixed planet and sign chips truncating on compact screens (e.g. "M...", "Ta..."); now wraps cleanly in a 2-per-row grid.
- **Play Billing Recovery:** Recovers gracefully from Play Store "item already owned" errors during Support Us donations.
- **Play Billing Reconnection:** Auto-resets and reconnects dropped Play Billing client connections without requiring an app force-close.
- **Festival Muhurat Card Speed:** Reduced card download/share latency from ~10s to near-instantaneous by forwarding target coordinates and date.
- **Touch Target Compliance:** Enforced 44pt minimum touch targets across all header controls, theme pills, location selectors, and filter chips.
