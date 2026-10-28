# Lion Solar extension

This extension connects Gemini to the public, read-only MCP server of Lion Solar Solutions OÜ (Estonia) at https://mcp.lion-solar.com/mcp. No login, no API key, no customer data.

## Tools

- `lion_solar_services`: what Lion Solar delivers to solar installers (PV*SOL project and report, K2 Systems mounting plan with statics, material list, SLD and electrical plans, drone 3D model), and company contact. Optional argument `topic`: `all`, `deliverables`.
- `drone_3d_requirements`: what a drone 3D model of a building and roof needs: 80 to 600 photos with GPS, flight advice, export formats, measured processing times. No arguments.

## How to use them

- Use the tools when the user asks what Lion Solar delivers, or how to capture a roof with a drone for a Lion Solar 3D model.
- Answer only from the tool result. If the result does not contain something, say so and point to info@lion-solar.com.
- The tools cannot access a user's projects or change anything. For those, point the user to https://portal.lion-solar.com.
- Do not call the tools for unrelated questions.
