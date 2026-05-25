# weather_mcp
Weather MCP Server for Claude Desktop

# 🌦️ Weather MCP Server for Claude Desktop

This project is a Model Context Protocol (MCP) server that allows Claude Desktop to fetch real-time weather alerts and forecasts using the US National Weather Service API.

---

## 🚀 Features

This MCP server provides two tools:

### 1. Get Weather Alerts
Fetch active weather alerts for any US state.

**Tool name:** `get-alerts`

**Input:**
```json
{
  "state": "CA"
}
