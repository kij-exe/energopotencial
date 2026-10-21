# Energy Potential Chart

A calculator that builds the numerology "energy potential" charts from a date of birth:

- **Life chart**: day × month × birth year. Each digit of the result covers one year, from one birthday to the next, and the sequence repeats in a 4 to 7 year cycle.
- **Year chart**: day × month × calendar year. Each digit covers one month, starting on the birthday.
- **"Zero in zero"**: periods when both charts are at 0 at the same time.

The dots on each chart are peaks. Between two peaks the line passes through the numbers in between. For example, going from a 2 to a 4, the line spends some time at 3. The site works out exactly when the line is at each number.

- Swipe the charts left and right (or drag them with the mouse). A phone shows about 10 years of the Life chart and 6 months of the Year chart at a time, and you can zoom out to 20 or 40 years and 12 or 24 months. The Year chart runs continuously from one year into the next.
- Tap anywhere on a chart to place a cursor. The number under the cursor is highlighted as a bar across its row, and the panel below the chart shows the dates it covers, its meaning and its peak.
- Open **Details** to see what the other chart does during that period. Use the arrows (or swipe the panel sideways) to step through the periods.

The interface is available in Russian, Ukrainian and English.

**Live site:** https://kij-exe.github.io/energopotencial/

To link to a specific date, add it after `#`: `https://kij-exe.github.io/energopotencial/#25.02.1960`

The whole site is one file, `index.html`, with no build step and no dependencies beyond Google Fonts.
