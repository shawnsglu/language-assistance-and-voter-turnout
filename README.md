# language-assistance-and-voter-turnout
# State-Level Language Assistance and Voter Turnout

## Research Question:

Multiple factors can prevent American citizens from voting, including the costs associated with voter registration, limited accessibility of polling locations, low levels of political efficacy, and language barriers. In 1975, the Congress added Section 203 to the Voting Rights Act to protect the voting rights of language minorities. The law requires that any political subdivision (usually at the county-level) with at least 10,000 or 5 percent of the voters who belong to a single language minority has to include that language on its ballots. Since 2001, several states legislate their own voting right acts at the state-level, which go beyond the federal protections, to enhance voting rights protections for language minorities. Advocates argue that these policies provide language minorities the equal opportunity to vote and increase the voter turnout.

However, limited existing literature examines the effects of language assistance on voter turnout. Using a regression discontinuity design, Fraga (2016) found Section 203 of VRA can increase Latino and Asian voter turnout. In contrast, Mann, Michelson, and Davis (2020) examined whether bilingual language mobilization can increase voter turnout among Latino voters, and they found that the English-only mobilization was more effective than the bilingual one. Despite these contributions, existing research has largely overlooked whether state-level VRAs can further enhance voter participation. Compared to Section 203, state-level VRAs usually have a lower threshold for determining whether a political subdivision is covered by language assistance requirements. As a result, these laws potentially increase voter turnout rates in those political subdivisions whose share of Latino and Asian population are just below the federal coverage threshold, which causes a downward bias of Fraga’s (2016) findings. This project aims at filling this gap.

---

## Methods:

This project is divided into two phases. The first phase aims to provide a landscape of existing law protecting the voting rights of language minorities at both federal- and state- levels. The second phase will examine the effectiveness of these protections on voter turnout with a quantitative approach.

The first phase will systematically review government documents, especially focus on federal and state Voting Rights Acts, and related legislation. Ten states already have enacted state Voting Rights Acts, including Washington, Oregon, California, Colorado, Minnesota, Illinois, Virginia, New York, Maryland, and Connecticut. This project will create a spreadsheet that catalogs the key provisions of each law, especially provisions related to language assistance, for a systematic comparison across jurisdictions.

The second phase of the project is to evaluate the effect of language assistance requirements on voter turnout. Several research designs are considered:
A natural experiment research design by comparing voter turnout rates between the treatment, those who are covered by language assistance requirements and share borders with not-covered precincts, and the control, those who are not covered by language assistance requirements and share borders with covered precincts. This project expects the average values of variables potentially affecting voter turnout, such as demographic and socioeconomic variables, should be similar between the treatment and control groups since the geographical similarity.
A regression discontinuity design by comparing voter turnout between counties with language minority populations just above and just below language assistance requirements thresholds (Fraga, 2016). Similarly, the project expects the treatment group and the control group, on average, should have similar characteristics, which makes the research design as-if-random.
A difference-in-difference design which compares the change of voter turnout between political subdivisions covered by language assistance requirements and those not covered by such requirements.

The goal of this project is analyzing the treatment effect (language assistance requirements) on voter turnout. Potentially, the project can expand the scope by including other elections into the analysis.

Notes:
County-level electoral systems
Balance-check
Dependent variables

---

## Data:

This project will collect both federal and state VRAs documents and precinct-level voter turnout data. I will mainly use Google Sheets and Python to organize and analyze the data.

Each research design requires different datasets. For example, the natural experiment design and the regression discontinuity might need a nation-wide voter turnout data, such as the 2024 presidential election voter turnout at precinct-level. In contrast, the difference-in-differences design would require voter turnout data from at least one election before and one after the enactment of a state-level Voting Rights Act.
