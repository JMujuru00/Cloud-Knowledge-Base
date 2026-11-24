# Numbers and Booleans

## Completed

- AboutBooleans
- AboutNumbers

## Quick Notes

### Numbers

- PowerShell uses **banker's rounding**.
  - `2.5` rounds to `2`
  - `3.5` rounds to `4`
- Integer types:
  - `[int]` = Int32
  - `[long]` = Int64
- `[int]` stores whole numbers.
- `[double]` stores decimal values.

### Booleans

- Boolean values are either:
  - `$true`
  - `$false`
- Comparisons return Boolean results.

Example:

```powershell
5 -gt 3
# Returns $true

2 -eq 5
# Returns $false