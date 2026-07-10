# Rotor Blade Helicopter Design

CAD and technical drawing package for a two-blade helicopter rotor (71.10 in overall diameter), developed as part of an aeronautical engineering coursework project applying blade element theory to a fully modeled and drafted rotor geometry.

## Overview
 
The rotor consists of two main components — a blade and a hub — modeled individually in SolidWorks and mated into a full rotor assembly. The design process started with manual orthographic drafting on tracing paper before being transferred into parametric CAD, and a formal dimensioned engineering drawing was produced from the final model.

## Project Files
 
| File | Type | Description |
|---|---|---|
| `3d-model-propeller.sldasm` | SolidWorks Assembly | Full rotor assembly — blade mated to hub |
| `prop-blade.sldprt` | SolidWorks Part | Individual rotor blade |
| `prop-hub.sldprt` | SolidWorks Part | Rotor hub |
| `3d-model-propeller-50x25.pdf` | Drawing (PDF) | Dimensioned orthographic drawing: front, top, right-side, and isometric views |
| `tracing paper borders.SLDDRW` | SolidWorks Drawing | Drawing sheet/border template used for the manual drafting exercise |
| `drafted-tracing-paper-view-of-act6-helicopter...` | Scan/Image | Hand-drafted orthographic views on tracing paper; manual precursor to the CAD model |

## Design Specifications
 
Pulled directly from the dimensioned drawing:
 
| View | Dimension | Value |
|---|---|---|
| Front | Overall span | 71.10 in |
| Front | Dimension (unlabeled here) | 5.50 in |
| Front | Dimension (unlabeled here) | 1.84 in |
| Front | Bolt/hole pattern | 4 × 0.67 in |
| Top | Overall span | 71.10 in |
| Top | Dimension (unlabeled here) | 3.00 in |
| Right side | Blade angle, station 1 | 23.52° |
| Right side | Blade angle, station 2 | 39.82° |
| Right side | Blade angle, station 3 | 78.04° |

## Methodology
 
1. **Manual drafting** — orthographic views hand-drafted on tracing paper (Activity 6) to establish rotor geometry and drawing conventions before CAD work began.
2. **CAD modeling** — blade and hub modeled as separate SolidWorks parts, then mated into a full rotor assembly.
3. **Blade twist** — the three angles on the drawing (23.52°, 39.82°, 78.04°) point to a nonlinear twist distribution along the span, which is the expected result of blade element theory: pitch angle decreases toward the tip to keep angle of attack roughly constant as local velocity (Ωr) increases with radius.
4. **Drawing generation** — a formal dimensioned drawing was produced in SolidWorks for documentation/manufacturing reference.

## Tools Used
SolidWorks (part modeling, assembly, engineering drawing)
