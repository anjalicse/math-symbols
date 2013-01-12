
# math-symbols

This will let you input Math symbols and styled texts, and convert it from/to LaTeX.

This tool use the data from [unimathsymbols.txt](http://milde.users.sourceforge.net/LUCR/Math/data/unimathsymbols.txt).

You can input various mathematical symbols by `M-x math-input'.

You can convert Math symbols to TeX commands and vice versa by `M-x math-symbols-from-tex-region' and `M-x math-symbols-to-tex-region'.

## Examples:

    "Fractur" → "𝔉𝔯𝔞𝔠𝔱𝔲𝔯" (M-x math-fraktur-region)
    "black" → "𝒷ℓ𝒶𝒸𝓀" (M-x math-script-region)
    "Quo Vadis" → "ℚ𝕦𝕠 𝕍𝕒𝕕𝕚𝕤" (M-x math-double-struck-region)
