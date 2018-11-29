<style>
body {
  font-family: Helvetica, arial, sans-serif;
  font-size: 14px;
  line-height: 1.6;
  padding-top: 10px;
  padding-bottom: 10px;
  background-color: white;
  padding: 30px; }

body > *:first-child {
  margin-top: 0 !important; }
body > *:last-child {
  margin-bottom: 0 !important; }

a {
  color: #4183C4; }
a.absent {
  color: #cc0000; }
a.anchor {
  display: block;
  padding-left: 30px;
  margin-left: -30px;
  cursor: pointer;
  position: absolute;
  top: 0;
  left: 0;
  bottom: 0; }

h1, h2, h3, h4, h5, h6 {
  margin: 20px 0 10px;
  padding: 0;
  font-weight: bold;
  -webkit-font-smoothing: antialiased;
  cursor: text;
  position: relative; }

h1:hover a.anchor, h2:hover a.anchor, h3:hover a.anchor, h4:hover a.anchor, h5:hover a.anchor, h6:hover a.anchor {
  background: url("../../images/modules/styleguide/para.png") no-repeat 10px center;
  text-decoration: none; }

h1 tt, h1 code {
  font-size: inherit; }

h2 tt, h2 code {
  font-size: inherit; }

h3 tt, h3 code {
  font-size: inherit; }

h4 tt, h4 code {
  font-size: inherit; }

h5 tt, h5 code {
  font-size: inherit; }

h6 tt, h6 code {
  font-size: inherit; }

h1 {
  font-size: 28px;
  color: black; }

h2 {
  font-size: 24px;
  border-bottom: 1px solid #cccccc;
  color: black; }

h3 {
  font-size: 18px; }

h4 {
  font-size: 16px; }

h5 {
  font-size: 14px; }

h6 {
  color: #777777;
  font-size: 14px; }

p, blockquote, ul, ol, dl, li, table, pre {
  margin: 15px 0; }

hr {
  background: transparent url("../../images/modules/pulls/dirty-shade.png") repeat-x 0 0;
  border: 0 none;
  color: #cccccc;
  height: 4px;
  padding: 0; }

body > h2:first-child {
  margin-top: 0;
  padding-top: 0; }
body > h1:first-child {
  margin-top: 0;
  padding-top: 0; }
  body > h1:first-child + h2 {
    margin-top: 0;
    padding-top: 0; }
body > h3:first-child, body > h4:first-child, body > h5:first-child, body > h6:first-child {
  margin-top: 0;
  padding-top: 0; }

a:first-child h1, a:first-child h2, a:first-child h3, a:first-child h4, a:first-child h5, a:first-child h6 {
  margin-top: 0;
  padding-top: 0; }

h1 p, h2 p, h3 p, h4 p, h5 p, h6 p {
  margin-top: 0; }

li p.first {
  display: inline-block; }

ul, ol {
  padding-left: 30px; }

ul :first-child, ol :first-child {
  margin-top: 0; }

ul :last-child, ol :last-child {
  margin-bottom: 0; }

dl {
  padding: 0; }
  dl dt {
    font-size: 14px;
    font-weight: bold;
    font-style: italic;
    padding: 0;
    margin: 15px 0 5px; }
    dl dt:first-child {
      padding: 0; }
    dl dt > :first-child {
      margin-top: 0; }
    dl dt > :last-child {
      margin-bottom: 0; }
  dl dd {
    margin: 0 0 15px;
    padding: 0 15px; }
    dl dd > :first-child {
      margin-top: 0; }
    dl dd > :last-child {
      margin-bottom: 0; }

blockquote {
  border-left: 4px solid #dddddd;
  padding: 0 15px;
  color: #777777; }
  blockquote > :first-child {
    margin-top: 0; }
  blockquote > :last-child {
    margin-bottom: 0; }

table {
  padding: 0; }
  table tr {
    border-top: 1px solid #cccccc;
    background-color: white;
    margin: 0;
    padding: 0; }
    table tr:nth-child(2n) {
      background-color: #f8f8f8; }
    table tr th {
      font-weight: bold;
      border: 1px solid #cccccc;
      text-align: left;
      margin: 0;
      padding: 6px 13px; }
    table tr td {
      border: 1px solid #cccccc;
      text-align: left;
      margin: 0;
      padding: 6px 13px; }
    table tr th :first-child, table tr td :first-child {
      margin-top: 0; }
    table tr th :last-child, table tr td :last-child {
      margin-bottom: 0; }

img {
  max-width: 100%; }

span.frame {
  display: block;
  overflow: hidden; }
  span.frame > span {
    border: 1px solid #dddddd;
    display: block;
    float: left;
    overflow: hidden;
    margin: 13px 0 0;
    padding: 7px;
    width: auto; }
  span.frame span img {
    display: block;
    float: left; }
  span.frame span span {
    clear: both;
    color: #333333;
    display: block;
    padding: 5px 0 0; }
span.align-center {
  display: block;
  overflow: hidden;
  clear: both; }
  span.align-center > span {
    display: block;
    overflow: hidden;
    margin: 13px auto 0;
    text-align: center; }
  span.align-center span img {
    margin: 0 auto;
    text-align: center; }
span.align-right {
  display: block;
  overflow: hidden;
  clear: both; }
  span.align-right > span {
    display: block;
    overflow: hidden;
    margin: 13px 0 0;
    text-align: right; }
  span.align-right span img {
    margin: 0;
    text-align: right; }
span.float-left {
  display: block;
  margin-right: 13px;
  overflow: hidden;
  float: left; }
  span.float-left span {
    margin: 13px 0 0; }
span.float-right {
  display: block;
  margin-left: 13px;
  overflow: hidden;
  float: right; }
  span.float-right > span {
    display: block;
    overflow: hidden;
    margin: 13px auto 0;
    text-align: right; }

code, tt {
  margin: 0 2px;
  padding: 0 5px;
  white-space: nowrap;
  border: 1px solid #eaeaea;
  background-color: #f8f8f8;
  border-radius: 3px; }

pre code {
  margin: 0;
  padding: 0;
  white-space: pre;
  border: none;
  background: transparent; }

.highlight pre {
  background-color: #f8f8f8;
  border: 1px solid #cccccc;
  font-size: 13px;
  line-height: 19px;
  overflow: auto;
  padding: 6px 10px;
  border-radius: 3px; }

pre {
  background-color: #f8f8f8;
  border: 1px solid #cccccc;
  font-size: 13px;
  line-height: 19px;
  overflow: auto;
  padding: 6px 10px;
  border-radius: 3px; }
  pre code, pre tt {
    background-color: transparent;
    border: none; }
</style>

# Future by the Future
Workshop on the vision for the next decades in astrophysics with gravitational waves and other cosmic messengers

Nov. 30 - Dec. 1, 2018, Columbia University

## Schedule

### Friday
| Time | Speaker | Title |
|-------------|-------------------------|-------------------------|
| 8:50-9:00 | Szabi and Zsuzsa Marka | _Opening statement_ |
| 9:00-9:20 | Brian Greene | _Welcome remark_  |
| 9:20-9:50 | Azadeh Keivani | Is multi-messenger astrophysics the best approach to study sources of high-energy neutrinos and ultra-high energy cosmic rays? |
| 9:50-10:20 | Josh Dillon | Opening the 21 cm Window on Our Cosmic Dawn |
| 10:20-10:50 | Jasmine Gill | From Dreams to Future Discoveries: Advancing Multi-Messenger Core-Collapse Supernova Science |
| 10:50-11:00 |  | _Coffee break_ |
| 11:00-11:30 | Dario Carbone | Identifying EM counterparts to NS-NS mergers: an Optimized Radio Follow-up Strategy |
| 11:30-12:00 | Ashley Villar | Analyzing Cosmic Messengers with More Data, New Tools & Unified Modeling |
| 12:00-12:30 | Jamie Rollins | TBD |
| 12:30-1:10 |  | _Panel discussion about the future_ |
| 1:10-1:50 |  | _Lunch (provided)_ |
| 1:50-2:20 | Michael Coughlin | Using EMCCDs for high-cadence observations of objects variable on short time-scales |
| 2:20-2:50 | Katerina Chatziioannou | Studying the neutron star equation of state with multi messenger observations |
| 2:50-3:20 | Imre Bartos | The Age of Abundance: How Frequent Discoveries will Transform Multimessenger Astrophysics |
| 3:20-3:30 |  | _Coffee break_ |
| 3:30-4:00 | Evan Hall | Cosmic Explorer and the Future of Ground-Based Gravitational-Wave Detection |
| 4:00-4:30 | Katelyn Breivik | The stellar graveyard: a multi-messenger, multi-band puzzle |
| 4:30-5:00 | Leo Singer | TBD |
| 5:00-5:30 | Anamaria Effler | TBD |
| 5:30-6:10 |  | _Panel discussion about the future_ |
| 6:10-7:00 |  | _Wine and cheese_ |

### Saturday
| Time | Speaker | Title |
|-------------|-------------------------|-------------------------|
| 9:00-9:30 | Shuo Zhang | High-energy X-ray View of the Central 10 pc of the Galaxy |
| 9:30-10:00 | Marcos Santander | The future of high-energy neutrino astrophysics |
| 10:00-10:30 | Hsin-Yu Chen | The bright and loud future of gravitational-wave multi-messenger astrophysics and cosmology |
| 10:30-10:50 |  | _Coffee break_ |
| 10:50-11:20 | Carl Johan Haster | The future of Gravitational Wave inference - problems to solve over the next few years |
| 11:20-11:50 | Marcelle Soares Santos | Precision cosmology with standard sirens and traditional probes in DES and LSST DESC |
| 11:50-12:20 | Ali Kheirandish | Multimessenger observations and the path to uncovering cosmic ray sources: strategies for identifying flaring, obscured, and efficient sources |
| 12:20-1:00 |  | _Panel discussion about the future_ |
| 1:00-1:40 |  | _Lunch_ |
| 1:40-2:10 | Phil Cowperthwaite | Chasing EM Counterparts with Next-Generation Facilities |
| 2:10-2:40 | Evan Gotz | Searching for continuous gravitational waves with advanced detectors and beyond |
| 2:40-3:10 | Ke Fang | High-energy Astroparticle Counterparts to Neutron Star Mergers |
| 3:10-3:40 | Peter Veres | Role of Gamma-ray Bursts in the Future of Multimessenger Astrophysics |
| 3:40-4:20 |  | _Panel discussion about the future_ |
| 4:20-4:30 | Zsuzsa Marka | _Closing remarks_ |

## Location
Columbia University, Pupin Hall
Center for Theoretical Physics, 8th Floor

Pupin Hall is at the north side of campus by 120th St.

You may enter the campus from 116th St. (#1 subway station) and walk north.
