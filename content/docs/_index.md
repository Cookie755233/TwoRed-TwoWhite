---
title: Aviation Notes
toc: false
width: normal
cssclasses:
- wide-view
---

<style>
  /* 1. Force Title Container to Block so Ellipsis (...) works */
  .hextra-card-icon {
    font-size: 1.125rem !important;
    font-weight: 600 !important;
    display: block !important;      /* MUST be block for text-overflow to work on raw text */
    width: 100% !important;
    white-space: nowrap !important; /* Force text to one line */
    overflow: hidden !important;    /* Hide the excess */
    text-overflow: ellipsis !important; /* Triggers the "..." */
    line-height: 1.5rem !important;
  }

  /* 2. Lock the SVG inline with the text so it doesn't break to a new line */
  .hextra-card-icon svg {
    display: inline-block !important;
    vertical-align: middle !important; 
    margin-right: 0.5rem !important;
    margin-top: -2px !important;    /* Micro-adjustment to center icon with text */
    width: 1.25rem !important;
    height: 1.25rem !important;
  }

  /* 3. Keep the Subtitle standard and wrapped */
  .hextra-card-subtitle {
    height: 3rem !important;        
    margin-top: 0.75rem !important;
    display: -webkit-box !important;
    -webkit-line-clamp: 2 !important; 
    -webkit-box-orient: vertical !important;
    overflow: hidden !important;
    white-space: normal !important; /* Allow the description to wrap naturally */
  }

  /* 4. Clean padding */
  .hextra-card > div {
    padding: 10px;
  }
</style>

Some sections are still a work in progress and will be updated over time. 
**Always** cross-check with official documents.

> [!info]
> Some sections are still a work in progress and will be updated over time. Always cross-check with official sources.

{{< cards >}}
  {{< card link="aeronautical-decision-making" title="Aeronautical Decision Making" icon="light-bulb" subtitle="Judgment, risk management, and CRM." >}}
  {{< card link="airport-operations" title="Airport Operations" icon="flag" subtitle="Runways, taxiways, signs, lighting, and procedures." >}}
  {{< card link="principles-of-flight" title="Principles of Flight" icon="arrow-up" subtitle="Lift, drag, thrust, and the four forces." >}}
  {{< card link="aerodynamics" title="Aerodynamics" icon="refresh" subtitle="Stalls, stability, and airflow behaviour." >}}
  {{< card link="aircraft-systems" title="Aircraft Systems" icon="cog" subtitle="Engine, fuel, electrical, and hydraulic systems." >}}
  {{< card link="aircraft-instruments" title="Aircraft Instruments" icon="chart-bar" subtitle="Pitot-static, gyroscopic, and magnetic instruments." >}}
  {{< card link="airspaces" title="Airspaces" icon="globe" subtitle="Classes, requirements, and special use airspace." >}}
  {{< card link="performance" title="Performance" icon="trending-up" subtitle="Takeoff, landing, climb, and cruise performance." >}}
  {{< card link="weight-and-balance" title="Weight and Balance" icon="scale" subtitle="CG limits, loading, and moment calculations." >}}
  {{< card link="meteorology" title="Meteorology" icon="cloud" subtitle="Weather, fronts, clouds, and hazards." >}}
  {{< card link="navigation" title="Navigation" icon="map" subtitle="VFR charts, dead reckoning, and navigation aids." >}}
  {{< card link="flight-documents" title="Flight Documents" icon="document-text" subtitle="Logbooks, certificates, NOTAMs, and regulations." >}}
  {{< card link="aeromedical" title="Aeromedical" icon="heart" subtitle="Hypoxia, spatial disorientation, and fitness to fly." >}}
{{< /cards >}}
