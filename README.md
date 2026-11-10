Tensegrity Supplement Probe

A compact browser-based prototype to inspect supplemental files (CSV/TSV/JSON/ZIP) and normalize simple module pose/connectivity tables into one CSV, with a provenance report.

Usage
- Open index.html in a modern browser.
- Paste a URL to a ZIP or a direct file, or use the file picker to load local supplements.
- The app lists machine-readable files found, extracts CSV/TSV/JSON, attempts a basic normalization (columns: id, x,y,z,conn), and shows a provenance report linking filenames and locations.

Limitations
- Prototype only. Heuristic parsing: works for straightforward tables with obvious headers (id, x,y,z, conn/connection/links). Complex formats or binary archives may not be parsed.
- No network calls performed unless you paste a URL and your browser allows cross-origin fetch; CORS may block some remote files.

License: MIT
