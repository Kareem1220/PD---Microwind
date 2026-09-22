# PD - Microwind

Lab solutions and layout files for coursework done in **Microwind**, a CMOS IC layout and design tool used for physical design (PD) and analog/mixed-signal (AMS) training.

This repo collects the `.MSK` layout files (Microwind's native layout format) and accompanying `.xlsx` solution sheets produced while working through a set of lab exercises — logic gate layout, DRC/error correction, and inverter optimization.

## Contents

All files live in [`Lab Solutions/`](./Lab%20Solutions).

| File | Type | Description |
|---|---|---|
| `Kareem_NOR.MSK` | Layout | NOR gate layout (CMOS transistor-level design in Microwind). |
| `Lab3.MSK` | Layout | Lab 3 starting/base layout file. |
| `Lab3_Sol_KareemHamza.MSK` | Layout | Lab 3 solved/completed layout. |
| `Lab4_SOL_KareemHamza.MSK` | Layout | Lab 4 solution layout. |
| `Lab6_Errors.MSK` | Layout | Lab 6 layout containing intentional/unresolved DRC errors, used for debugging practice. |
| `lab6_take1.MSK` | Layout | Lab 6, first attempt at fixing the design. |
| `lab6_ZeroError.MSK` | Layout | Lab 6, final version with all DRC errors resolved. |
| `Optimal_Inverter.MSK` | Layout | Optimized CMOS inverter layout. |
| `LAB1_SOL_KareemHamza.xlsx` | Spreadsheet | Lab 1 solution/calculations. |
| `Lab2_SOL_KareemHamza.xlsx` | Spreadsheet | Lab 2 solution/calculations. |

## About the `.MSK` format

`.MSK` files are Microwind's plain-text layout format — they describe an IC layout as a series of geometric primitives (rectangles, vias, contacts, etc.) tagged by mask layer (e.g. `NW` for N-well, `DP`/`DN` for diffusion, `PO` for polysilicon, `ME` for metal, `CO`/`VI` for contacts/vias). They open directly in [Microwind](http://www.microwind.net/) for viewing, editing, and running DRC/simulation.

## Notes

- These are personal lab solutions from coursework, kept here for backup, version history, and reference.
- To open the `.MSK` files, you'll need Microwind (Lite or full version) installed.
- The `.xlsx` files contain the written/calculated portions of the corresponding labs.
