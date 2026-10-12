# Changelog

## 1.1.0

First release as a standalone HACS dashboard card.

- Overview, Device, Analysis and Comparison views in the style of the SAJ
  Elekeeper portal
- Sensors discovered automatically from the SAJ eSolar Cloud integration
- Charts drawn from the Home Assistant history and long-term statistics,
  with no other frontend dependencies
- Revenue card hidden when the API reports no revenue
- Devices whose sensors are all unavailable (e.g. a replaced inverter) are
  ignored
- Single-column layout on phones
