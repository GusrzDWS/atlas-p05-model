# Atlas P05 model

Published coordination model: CAT6 P05 and compressed air REV17.

Public viewer: https://gusrzdws.github.io/atlas-p05-model/

Phone navigation includes 44px controls, explicit zoom buttons, persistent part-panel Close, orientation-aware camera framing and gesture selection protection.

New IDF-02–06 cabinet bottoms are 15 ft AFF. Cable screens use a 15-ft entry and 18-ft vertical allowance from the 33-ft tray; exact internal entry and patch-panel path need confirmation. Existing warehouse security IDFs D4/D10/D16 remain position references only and receive none of our CAT6 connections. Air REV17 geometry is unchanged.

Current proposal and 17-sheet CAD PDF include the 15-ft height basis. All 160 active endpoints / 672 cables remain assigned only to five NEW IDFs. The drawings and model contain proposed routes and unresolved confirmation items.

Over-limit review:31 locations /114 cables remain above the90m fixed-link screen; all serve IDF-02/E4. New marked drawing:CAT6-P05-Overlength-Runs.pdf (3 sheets). The model has a filtered over-limit selector and shows length/excess for each route.

IDF-01 is excluded from all project copper and fiber connections. It remains a reference marker; its prior670.06LF horizontal fiber interconnection is removed. Five corporate warehouse-IDF backbone paths remain,1858.9LF horizontal before verticals/slack.


## Separate review option: fixed-IDF length corrections

[Review drawing](CAT6-P05-Proposed-Length-Corrections.pdf) and [before/after schedule](CAT6-P05-Proposed-Length-Corrections.csv).

This is an unadopted proposal; the P05 model and baseline quantities remain unchanged. All five warehouse IDFs stay at their current locations, cabinet bottoms at 15 ft AFF, and proposed pathways at 33 ft AFF. The option adds 248.30 LF of tray and 44.55 LF of separate supported approaches. Of 31 previously over-limit locations, 9 fall within the planning screen (including one AP minimum), 5 become near-limit holds, and 17 locations / 50 original services receive proposed fiber paths from the same warehouse IDF. Exact optics, endpoint power/PoE, supported route, speed, clearances and near-limit cases require review. The fiber service count is not a fiber-strand or converter purchase quantity. No IDF-01 or security-IDF use, cabinet relocation or extra IDF is proposed.

All 160 endpoints / 672 original services were independently checked; no new over-limit runs occur. The drawing includes the ordinary 90-m fixed-link / 100-m channel distinction and 1 / 2.5 / 5 / 10-Gbps cable guidance, plus manufacturer-specific extended-reach examples as a conditional alternative.


## P05 red route review

The unchanged P05 baseline now highlights 31 over-limit locations / 114 CAT6 cables in red, following their existing full paths including known verticals. Open `?review=over-limit` for the focused 3D review. The CAT6 menu includes a Show all over-limit routes in red toggle and individual route selector. Other selected routes remain orange. Air-only and floor-only hide the red overlay. AP I1/I2 are minimum lengths pending mounting heights. Shared tray stretches can also carry within-limit cables. These display guides are excluded from material counts and physical exports. All source geometry, IDF assignments and quantities are byte-for-byte unchanged; the optional length-correction drawing remains unadopted.


## Length labels on red routes

Each red P05 route now has a leader callout with its outlet/AP ID, total screening length in feet, and feet over the exact 90-m (295.2755905511811-ft) fixed-link threshold. Values are rounded to one decimal only for display; stored totals include the existing known verticals and 20-ft service slack. I1/I2 labels use ≥ because AP mounting heights remain TBD. Callouts can be clicked/tapped to inspect a run and toggled in the CAT6 menu. They remain legible during orbit/zoom and avoid overlapping labels and controls; crowded phone views hide excess labels, with a visible count and instructions to zoom/pan/select the desired run. All31 fit in the checked desktop review. Labels are display-only, included in Save image, and excluded from physical exports and quantities. Air/CAT6/proposal data hashes remain unchanged.
