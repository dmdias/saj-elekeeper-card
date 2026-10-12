# Changelog

## 1.1.1

- Solar panels on the overview house drawn as individual modules that follow
  the roof perspective (the grid lines no longer cross the panel edges, and
  the chimney no longer covers the array)
- PV flow line starts at the panels; PV and Load labels point at the panels
  and the house

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
