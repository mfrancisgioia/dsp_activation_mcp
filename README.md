# DV360 × CM360 MCP Integration Prototype

This prototype is an interactive HTML form that demonstrates how normalized campaign inputs translate into platform-specific API payloads for Google DV360 and CM360. Fill out a single form covering your campaign, insertion order, line item, and creative details — the tool handles the field mapping, budget conversion, and API call sequencing automatically. An optional CM360 linking toggle reveals cascading dropdowns to map any DV360 line item to an existing CM360 placement, without requiring floodlight setup.

## Usage

Download `dsp_activation_mcp.html`, open it in any modern browser, and fill out the form. Use the output tabs to copy your normalized JSON, DV360 API payload, CM360 linking configuration, or full workflow sequence. Payloads are ready to paste directly into Postman or wire into a backend MCP server. Mock data is included for advertisers, placements, and audiences — replace with real account values when connecting to live APIs.

## Live Prototype 
**[Launch `dsp_activation_mcp.html` →](https://mfrancisgioia.github.io/prototype/dsp_activation_mcp.html)**
