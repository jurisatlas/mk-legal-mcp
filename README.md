# North Macedonia Legal Research MCP Server (`mk-legal-mcp`)

**[Македонски](#lang-mk) | [Shqip](#lang-sq) | [English Documentation](#english-documentation)**

---

<a id="lang-mk"></a>
## Правен MCP Сервер за Северна Македонија (`mk-legal-mcp`) — Македонски

### За овој репозиториум

Овој репозиториум содржи MCP сервер кој го поврзува вашиот AI асистент (Claude Desktop, Cursor, Windsurf, VS Code, Antigravity) со Службен весник на РСМ (`slvesnik.com.mk`) и националниот портал за судски одлуки (`sud.mk`), опфаќајќи ги сите основни судови, 4 апелациони судови (Скопје, Битола, Гостивар, Штип), Управниот суд, Врховниот суд и Уставниот суд.

### Брза инсталација (Избор на AI апликација)

1. **Преземање:** Кликнете на **`<> Code` -> `Download ZIP`** и отпакувајте ја папката.
2. **Стартување:** Двокликнете на **`Click_Here_To_Install_Windows.bat`** (Windows) или **`Click_Here_To_Install_Mac.command`** (macOS).
3. **Избор на AI клиент:** Изберете ја AI програмата што ја користите, кликнете за автоматско поврзување и рестартирајте ја избраната AI апликација.

**Безбедносна напомена:** Програмата работи исклучиво во режим на читање (read-only) и не ги допира вашите лични датотеки.

### Судска хиерархија и официјални извори

| Судски степен | Опфатени судови |
|:---|:---|
| **Првостепени (Основни) судови** | Osnovni sudovi (27 Basic Courts including Osnoven građanski sud Skopje & Osnoven krivičen sud Skopje) |
| **Апелациони и Управни судови** | 4 Apelacioni sudovi (Skopje, Bitola, Gostivar, Štip), Upravni sud & Viš upraven sud |
| **Врховен и Уставен суд** | Vrhoven sud na Republika Severna Makedonija (vsrm.mk) & Ustaven sud na RSM (ustavensud.mk) |

- **Služben vesnik na RSM (slvesnik.com.mk) & Akademika / Pravda Legislation:** [https://www.slvesnik.com.mk](https://www.slvesnik.com.mk) (`slvesnik.com.mk`, `pravo.org.mk`, `akademika.com.mk`, `pravda.gov.mk`)
- **Nacionalen portal na sudski odluki - Sud.mk (All Basic, Appellate, Administrative & Supreme Courts):** [http://www.sud.mk](http://www.sud.mk) (`sud.mk`, `vsrm.mk`, `ustavensud.mk`, `akademika.com.mk`)

---

<a id="lang-sq"></a>
## Serveri Ligjor MCP (`mk-legal-mcp`) — Shqip

### Rreth këtij depoje (Repository)

Ky depo përmban serverin Model Context Protocol (MCP) që lidh aplikacionin tuaj të inteligjencës artificiale (Claude Desktop, Cursor, Windsurf, VS Code / Copilot, Cline ose Antigravity) me fletoret zyrtare dhe bazat e të dhënave të vendimeve gjyqësore për **North Macedonia** (gjykatat e shkallës së parë / themelore, gjykatat e apelit dhe gjykatat e larta / supreme e kushtetuese).

### Instalimi i shpejtë (Zgjedhja e aplikacionit AI)

1. **Shkarkimi:** Klikoni **`<> Code` -> `Download ZIP`** dhe nxirrni dosjen në kompjuterin tuaj.
2. **Nisja e instaluesit:** Klikoni dy herë mbi **`Click_Here_To_Install_Windows.bat`** (Windows) ose **`Click_Here_To_Install_Mac.command`** (macOS).
3. **Zgjedhja e AI:** Zgjidhni programet AI që përdorni (Claude, Cursor, Windsurf, VS Code, Antigravity), klikoni butonin e instalimit dhe rinisni aplikacionin tuaj AI.

**Shënim sigurie:** Ky mjet funksionon vetëm në mënyrë leximi (read-only) dhe nuk prek ose ndryshon asnjë skedar personal në kompjuterin tuaj.

### Shkallët e gjyqësorit dhe burimet zyrtare

| Shkalla gjyqësore | Gjykatat e mbuluara |
|:---|:---|
| **Shkalla e Parë** | Osnovni sudovi (27 Basic Courts including Osnoven građanski sud Skopje & Osnoven krivičen sud Skopje) |
| **Gjykatat e Apelit** | 4 Apelacioni sudovi (Skopje, Bitola, Gostivar, Štip), Upravni sud & Viš upraven sud |
| **Gjykata e Lartë / Supreme & Kushtetuese** | Vrhoven sud na Republika Severna Makedonija (vsrm.mk) & Ustaven sud na RSM (ustavensud.mk) |

- **Služben vesnik na RSM (slvesnik.com.mk) & Akademika / Pravda Legislation:** [https://www.slvesnik.com.mk](https://www.slvesnik.com.mk) (`slvesnik.com.mk`, `pravo.org.mk`, `akademika.com.mk`, `pravda.gov.mk`)
- **Nacionalen portal na sudski odluki - Sud.mk (All Basic, Appellate, Administrative & Supreme Courts):** [http://www.sud.mk](http://www.sud.mk) (`sud.mk`, `vsrm.mk`, `ustavensud.mk`, `akademika.com.mk`)

---

<a id="english-documentation"></a>
## English Documentation

Model Context Protocol (MCP) server providing live, read-only access to **North Macedonia (MK)** legislation, official gazettes, multi-tier judicial decisions (First Instance, Regional/Cantonal/Appellate, and Supreme/Constitutional courts, including HTML and PDF full-text extraction), and statutory citation verification across all major AI clients (**ChatGPT Desktop, OpenAI Codex CLI, Claude Desktop, Claude Code CLI, Cursor, Windsurf, VS Code / GitHub Copilot / Cline / Roo Code, Google Antigravity / Gemini CLI, Perplexity, and Continue.dev**).

---

### Interactive Desktop Setup (Select Your AI Assistant)

This package includes a graphical installer for legal practitioners and non-technical users that lets you select which AI application(s) you use:

1. **Download:** Click **`<> Code`** at the top right of this repository, select **`Download ZIP`**, and extract the folder to your computer.
2. **Run the Setup Utility:**
   - **Windows:** Double-click `Click_Here_To_Install_Windows.bat`
   - **macOS:** Double-click `Click_Here_To_Install_Mac.command`
3. **Select Your AI Client(s) & Connect:** Check the box(es) for the AI assistant(s) installed on your computer (**ChatGPT Desktop & OpenAI Codex CLI**, **Claude Desktop & Claude Code CLI**, **Cursor**, **Windsurf**, **VS Code / GitHub Copilot / Cline / Roo Code**, **Google Antigravity / Gemini CLI**, or **Perplexity / Continue.dev**), click **Install to Selected AI Clients**, and restart your selected AI application.

**System Integrity Note:** The setup utility operates strictly in read-only mode with respect to your personal files and documents. It installs an isolated Python runtime inside the extracted folder and registers the server entry only in the AI client configuration files you select.

---

### Multi-Tier Judicial Hierarchy & Live Indexed National Archives

This server performs live queries across the full judicial hierarchy and official legal archives of **North Macedonia**, extracting full text from both HTML pages and official court/gazette PDF judgments:

| Judicial Tier | Covered Courts & Tribunals |
|:---|:---|
| **Tier 1 — First Instance** | Osnovni sudovi (27 Basic Courts including Osnoven građanski sud Skopje & Osnoven krivičen sud Skopje) |
| **Tier 2 — Regional / Cantonal / Appellate** | 4 Apelacioni sudovi (Skopje, Bitola, Gostivar, Štip), Upravni sud & Viš upraven sud |
| **Tier 3 — Supreme & Constitutional** | Vrhoven sud na Republika Severna Makedonija (vsrm.mk) & Ustaven sud na RSM (ustavensud.mk) |

#### Official Portals & Live Indexed Domains

- **National Legislation & Official Gazette:** Služben vesnik na RSM (slvesnik.com.mk) & Akademika / Pravda Legislation — [https://www.slvesnik.com.mk](https://www.slvesnik.com.mk)
  - *Indexed Legislation Domains:* `slvesnik.com.mk`, `pravo.org.mk`, `akademika.com.mk`, `pravda.gov.mk`
- **Court Decisions & Jurisprudence Archives:** Nacionalen portal na sudski odluki - Sud.mk (All Basic, Appellate, Administrative & Supreme Courts) — [http://www.sud.mk](http://www.sud.mk)
  - *Indexed Judicial & Open Case Law Domains:* `sud.mk`, `vsrm.mk`, `ustavensud.mk`, `akademika.com.mk`

---

### Available MCP Tools

| Tool | Description |
|:---|:---|
| `search_legislation` | Searches enacted statutes, codes, decrees, and official gazette publications in North Macedonia. |
| `search_case_law` | Searches national jurisprudence and open judicial archives for North Macedonia. |
| `search_tiered_court_decisions` | Filters case law specifically by judicial instance (`first_instance`, `appellate_regional`, `supreme_constitutional`) or specific regional/cantonal/district court. |
| `list_court_hierarchy` | Returns the complete 3-tier court structure and supported regional court filters for North Macedonia. |
| `get_legal_document_markdown` | Retrieves full statutory or judicial texts (both HTML and official `.pdf` court judgments) and converts them into clean Markdown. |
| `verify_citation` | Validates statutory and case law citations against official registries. |

---

<details>
<summary><b>Manual Configuration for Developers (Optional)</b></summary>

```json
{
  "mcpServers": {
    "mk-legal-mcp": {
      "command": "uvx",
      "args": [
        "--from",
        "https://github.com/jurisatlas/mk-legal-mcp/archive/refs/heads/main.zip",
        "mk-legal-mcp"
      ]
    }
  }
}
```
</details>
