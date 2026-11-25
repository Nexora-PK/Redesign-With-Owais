# Redesign With Owais: Bidirectional Layout Guidelines (RTL)

For international interfaces in Arabic, Persian, Urdu, or Hebrew:

1. **Logical Layout Properties:**
   - Use CSS logical properties instead of physical directions (`margin-inline-start`, `padding-inline-start`, `ms-*`, `me-*`).
2. **Icon Mirroring:**
   - Directional icons (arrows, chevrons, step indicators) MUST be flipped in RTL.
3. **Typography for Nastaliq / Arabic Scripts:**
   - Arabic and Urdu scripts require generous line-heights (`leading-loose` or `leading-[2]`).
