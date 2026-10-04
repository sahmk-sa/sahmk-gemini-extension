# SAHMK

SAHMK provides read-only data for companies listed on the Saudi Exchange.

Use the SAHMK tools when the user requests Saudi stock quotes, company discovery, company profiles, market summaries, movers, sector performance, financial statements, financial ratios, company comparisons, dividends, historical prices, market depth, recent trades, or stock events.

Use `get_depth` for the order book, bid/ask ladder, spread, and imbalance. It requires an active Market Depth entitlement. Use `get_trades` for recent trade prints and `get_events` for event summaries; both require Pro or above. Use `get_company` with an exact exchange symbol, and call `companies_list` first when the user gives a company name.

Always identify the symbol and market when available. Include the data timestamp when returned by the tool. Do not describe delayed data as real time, and do not imply that SAHMK can place trades or move financial assets.

Users may ask questions in Arabic or English.
