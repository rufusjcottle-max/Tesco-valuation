# Tesco-valuation - Equity valuation
Multi methodology equity valuation of Tesco PLC consisting of a DCF and trading comparables. Built on  the FY24/25 annual report data.
Built from scratch in Excel using the two methods.
I built this as a first year student to learn valuation properly, I had no Bloomberg or CapIQ access which shaped some of the decisions below.
Files:
Tesco_DCF.xlsx : WACC, unlevered free cash flow forecast, terminal value, equity bridge, sensitivity table.
Tesco_Comparable_analysis.xlsx : peer universe, multiples, benchmarking, implied valuation.
**Headline result**
Tesco traded at £4.70 at the time of the analysis
DCF - exit multiple terminal value : implied share price = £4.02
DCF - perpetuity growth terminal method : implied share price = £6.48
Trading comparables : implied share price = £3.10
The DCF straddles the market price however they also disagree.
Both terminal value methods sit on the same forecast, same revenue growth, same margins, same WACC of 6.94%. They only diverge in how they value the business beyond year five, and they come out £2.46 apart.
The perpetuity growth method takes terminal year unlevered free cash flow of £2,884m, grows it at 2% forever and discounts it back. That produces a terminal value worth 79% of total enterprise value. Almost the whole valuation rests on the last step, and that step is highly sensitive: a 0.5% move in either WACC or the growth rate shifts the implied price by roughly 40–60p.
The exit multiple method applies 6.5x to terminal year EBITDA of £5,537m instead. EMM anchors to something observable in the market.
I have shown both rather than picking one I preferred
Peer set: J Sainsbury, Carrefour, Ahold Delhaize, Jerónimo Martins, Colruyt, Kroger.
Tesco trades at 8.6x EV/EBITDA against a peer median of 5.5x, but only 19.8x P/E against a peer median of 14.9x. So a 56% premium on one multiple and 33% on the other, for the same company. Working out why became the most useful part of the project.
Applying a 4.7x–8.0x EV/EBITDA range to Tesco's EBITDA of £4,825m gives £1.93–£4.26, midpoint £3.10.
****The lease adjustment ****
Tesco's net debt is £9,454m, made up of £1,738m of financial net debt and £7,716m of lease liabilities. The leases are more than four times the underlying borrowings, reflecting a large leased store estate.
A enterprise value includes debt, the leases inflate Tesco's EV and therefore every EV based multiple. This only became visible once I restarted every peer onto a consistent lease inclusive basis. As before Sainsbury's showed an EV/EBITDA of 2.8x, which is not a plausible number for a listed grocer as the peers were being compared to each other on inconsistent debt definitions. Corrected, Sainsbury's comes out at 5.3x. 
Under IFRS 16 lease liabilities sit on the balance sheet, but as a separate line from borrowings rather than merged into them. If you pull "total debt" without consciously adding the lease lines, you get a figure that excludes them. Sainsbury's reports net debt of £5,758m, of which £5,494m is leases and only £264m is non-lease borrowings, so taking the wrong line understates its debt almost entirely.
