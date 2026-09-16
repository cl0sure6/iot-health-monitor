# MetaSense IoT — Metabolic Syndrome Monitoring Dashboard

A one-page website for an IoT-based healthcare system that monitors patients with
metabolic syndrome. Built with plain HTML and CSS for Seminar #3 of the Web
Development elective.

## Sections

- **Header** — system name and navigation menu
- **Introduction** — what the system does and how readings reach the dashboard
- **Patient Dashboard** — six monitored parameters with their normal ranges
- **Sensor Cards** — sensor name, device model, measured value, unit and status
- **Patient Information** — registration data, monitoring status, manual-reading form
- **Alert Section** — normal, warning and critical examples, plus a measurement log
- **Footer** — system information and contact details

## Monitored parameters

| Parameter | Sensor | Normal range |
|---|---|---|
| Body temperature | MAX30205 skin sensor | 36.1–37.2 °C |
| Blood glucose | CGM patch | 4.0–7.8 mmol/L |
| Heart rate | MAX30102 optical sensor | 60–100 bpm |
| Blood pressure | Digital cuff | below 130/85 mmHg |
| ECG | AD8232 single-lead monitor | regular sinus rhythm |
| Blood oxygen | Fingertip pulse oximeter | 95–100 % |

## CSS techniques used

Flexbox and CSS Grid layouts, styled cards / buttons / tables / forms / navigation,
five hover effects with transitions, class, ID and descendant selectors, the
`:hover`, `:focus`, `:active`, `:nth-child()` and `:last-child` pseudo-classes,
a `max-width: 768px` media query for mobile, shorthand properties and comments.

## Files

```
index.html      the page
style.css       the stylesheet
images/         SVG logo and sensor icons
```

## Validation

- HTML — W3C Nu Html Checker: no errors, no warnings
- CSS — W3C CSS Validation Service: valid CSS level 3 + SVG

## Note

All patient data and sensor readings on this page are simulated for educational
use. This is not a real medical record.
