# **agi-econ-sim**  
*Interactive simulation that visualises the trade-off between API pricing, subscription revenue and AGI-driven R&D for AI model providers.*

---

## 📝 Product-Requirements Document (PRD)

| **Abschnitt** | **Inhalt** |
|---------------|-----------|
| **Vision** | Transparente Sandbox, mit der Gründer, Investoren und Policy-Maker in < 60 Sekunden verstehen, wie Preisstrategie, GPU-Allokation und Gründer-Idealismus (φ) langfristigen Gewinn **und** AGI-Fortschritt beeinflussen. |
| **Zielgruppe** | • AI-Start-ups (Anthropic-ähnlich) <br>• VCs & Analysten <br>• Regulierungsbehörden, die Preisregeln oder F&E-Quoten diskutieren |
| **User-Stories (MVP)** | 1. **Als CFO** ändere ich API-Preis, Abo-Preis und F&E-Quote per Slider, um sofort neue Gewinnkurven zu sehen. <br>2. **Als Gründer** erhöhe ich φ, um zu sehen, wie Idealismus Profite verdrängt. <br>3. **Als Analyst** exportiere ich CSV-Daten der Simulation für tiefergehende Auswertungen. |
| **Funktionen v0.1 (fertig)** | • Vier Slider (p_A, p_S, a, φ) <br>• 24-Perioden-Simulation <br>• Dual-Chart (Profit & Utility) via Chart.js <br>• Single-file `index.html` (keine Build-Steps) |
| **Roadmap** | **v0.2** — URL-Query-Parameter + “Share Scenario”-Button; Wettbewerbs-Toggle (λ, μ) <br>**v0.3** — Regulierungs-Presets (Preisdeckel, GPU-Steuer) <br>**v1.0** — JSON-Export/Import, Mobile-Optimierung, Unit-Tests (Jest + Playwright) |
| **Tech-Stack** | Reines Frontend: HTML5, Vanilla JS, Chart.js — perfekt für GitHub Pages (kein Backend nötig). |
| **Dateistruktur** | `index.html` – App <br>`README.md` – Modell & Gleichungen <br>`LICENSE` – MIT |
| **Deployment** | 1. Repo `agi-econ-sim` anlegen. <br>2. `index.html` ins Root committen. <br>3. *Settings ▸ Pages*: Branch =`main`, Folder =`/`. |
| **Akzeptanz­kriterien** | • Ladezeit \< 1 s (3 G-Netz) <br>• Slider aktualisieren Diagramm ohne Reload <br>• README erklärt alle Gleichungen <br>• Lighthouse Performance ≥ 90 <br>• Keine externen Tracker |
| **Nicht-Ziele** | • Kein Backend <br>• Keine persistente DB <br>• Kein Echtzeit-Mehrspieler |
| **Lizenz** | MIT – Forks & akademische Nutzung ausdrücklich erlaubt |

---

> **Repo-URL (GitHub Pages)**  
> `https://<your-username>.github.io/agi-econ-sim/`
