# ParseClarityElectionDataForStateOfWestVirginia
Code conclusion - BIDEN BONUS = MINUS 0.12%, StdDev 1.92; TRUMP BONUS = PLUS 3.62%, StdDev 3.42

/*
 * ParseClarityElectionDataForStateOfWestVirginia.cs
 *
 * which code and results I will archive at:
 * https://github.com/IneffablePerformativity
 * https://github.com/IneffablePerformativity/ParseClarityElectionDataForStateOfWestVirginia
 * 
 * 
 * "To the extent possible under law, Ineffable Performativity has waived all copyright and related or neighboring rights to
 * The C# program ParseClarityElectionDataForStateOfWestVirginia.cs and resultant outputs.
 * This work is published from: United States."
 * 
 * This work is offered as per license: http://creativecommons.org/publicdomain/zero/1.0/
 * 
 * 
 * Goal: Parsing the JSON type of 2020 Election data for State of Virginia.
 *
 * I visited...
 * https://www.elections.virginia.gov/2020-election-results/
 * https://results.elections.virginia.gov/vaelections/2020%20November%20General/Site/Presidential.html
 * On President tab, click on JSON.
 * On Congress tab, click on JSON. -- I see both Senate and House in it.
 * Downloaded both 2020-11-30 7:30AM CT, renamed files:
 * "1, Virginia-Presidential.json"
 * "2. Virginia-Congress.json"
 * 
 * That was pretty shallow, about 11 POTUS vs. REPUS I can compare.
 * Here may be finer grained data albeit tougher to collect:
 * https://results.elections.virginia.gov/vaelections/2020%20November%20General/Site/Locality/Index.html
 * Yep, just like the summary file, but adds a LocalityName tag...
 * I manually click each locality, then click JSON, viewing file,
 * copy the LocalityName tag value, Save, paste as each filename.
 * This at 2020-11-30 730pm CT
 * 
 * 
 * 
 * to demonstrate any inverse republicanism::trump relationship
 * as was described for Milwaukee County Wisconsin in an article at:
 * https://www.thegatewaypundit.com/2020/11/caught-part-3-impossible-ballot-ratio-found-milwaukee-results-change-wisconsin-election-30000-votes-switched-president-trump-biden/
 * 
 * Or rather now, a systematic "BONUS TO BIDEN" and "THEFT FROM TRUMP"
 * by comparing RED and BLUE % for POTUS vs. SENUS and/or REPUS races.
 * 
 * 
 * possibleConclusionText BIDEN BONUS = MINUS 0.12%, StdDev 1.92; TRUMP BONUS = PLUS 3.62%, StdDev 3.42
 * finalConclusion = THE BLACK X'S MARK 7 BIGGEST SPOTS OF THEFT OVER 2% WORTH 11919 VOTES. SEE LOG FOR LOCALITY NAMES.
 * flipsideConclusion = FOR FAIRNESS, ANY WHITE X'S MARK 36 OPPOSITE BONUSES OVER 2% FAVORING TRUMP WORTH 19540 VOTES.
 * 
 * 
 * There is a series of similar programs building upon one another,
 * named similarly, with XML inputs, HTML inputs, PDF-as-TXT input,
 * and some ugly earlier versions, all to be found at GitHub, here:
 * https://github.com/IneffablePerformativity
 * 
 * 
 * Pre-2020-11-30 programs had some errors to fix. Behold a new day!
 * 
 * 
 * 
 * also note, I manually compress final image at tinypng.com
 */
