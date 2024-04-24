# Electoral Systems of the Upper House in Latin America and its Reforms 

Welcome to the GitHub repository of the database "Electoral Systems of the Upper House in Latin America and its Reforms," maintained by members of the Political Reform Observatory in Latin America.

## Contents

- [Summary](#summary)
- [Description](#description)
- [Citation](#citation)

## Summary

The database contains information on reforms concerning the regulations governing the electoral systems of the upper house of the national legislative branches in 10 Latin American countries. This includes modifications to the principle of representation of the upper house, the applicable electoral formula, the applicable electoral formulas in case the principle of representation is mixed, number of members established by the upper house, number and size of electoral districts,voting structure, mandate extension, electoral threshold, and the possibility of reelection and recall. 

The regulations review spans from each country's democratic transition year based on the framework proposed by Alcántara, Páramo, Freidenberg, and Déniz (2006).

For countries with gradual political change processes, the beginning of the third wave of democracy 
in Latin America (Huntington, 1991) is used as the basis. 

Members of the Observatory of Political Reforms in Latin America collected and coded the information. The information collection managers are Flavia Freidenberg (Institute for Legal Research),  Karolina Monika Gilas (Faculty of Political and Social Sciences, UNAM),  and María José Lorenzo Montalvo (Faculty of Political and Social Sciences, UNAM). The information coding managers are Karolina Monika Gilas (Faculty of Political and Social Sciences, UNAM),  and María José Lorenzo Montalvo (Faculty of Political and Social Sciences, UNAM).

## Description

The directory `./Data/` contains the file `./Data/DD_SECA` where all relevant information regarding the database linked to the electoral systems of the Upper House in Latin America and its reforms is located. Specifically, the database consists of the following variables:

-   `country`: name of the country where the reform of the upper house of the legislative electoral regime in Latin America was implemented.

-   `cowcode`: country code according to the “Correlates of War”, coding available at  https://correlatesofwar.org/data-sets/cow-country-codes.

-   `country_code`: country code according to the three-letter ISO code: (e.g. ARG, MEX, SAL) available at http://utils.mucattu.com/iso_3166-1.html 

-   `cons_ctry_ref`: records the consecutive number of reforms of the upper house of the legislative branch in each Latin American country (e.g. Peru_1 Peru_2, Peru_3, Peru_4). 

-   `year`: calendar year corresponding to the reform of the upper house electoral regime in each Latin American country between 1949-2023.

-   `rep_prin`: indicates the principle of political representation governing the election of the national upper house members of the legislative branch in each country. Its values are: [1] Majority, [2]: Proportional,  [3]: Mixed. [4]: Majority with minority representation. 

-   `elec_form_01`: indicates the vote-to-seat conversion formula established in the electoral reform for the upper house of the national legislative power. Its values are: [1] Distribution figure, [2]: D’Hondt, [3] Electoral quotient or residue, [4]: Hare and largest remainder method, [5] Modified Hare, [6] Corrected Imperiali, [7]: Weighted factor, [8]: Webster, [9]: Hagenbanch-Bischoff, [10]: Integral Proportional System, [11]: Absolute majority,  [12] Relative majority, [99] N/A. 

-   `elec_form_02`: if mixed, it indicates the second electoral formula applicable for the allocation of seats. Its values are  [1] Distribution figure, [2]: D ́Hondt, [3] Electoral quotient or residue, [4]: Hare and largest remainder method, [5] Modified Hare, [6] Corrected Imperiali, [7]: Weighted factor, [8]: Webster, [9]: Hagenbanch-Bischoff, [10]: Integral Proportional System, [11]: Absolute majority,  [12] Relative majority, [99] N/A. 
 
-   `m_house`: indicates the number of seats established by the electoral reform for the upper house of the national legislative branch.

-   `elect_dist`: indicates the number of electoral districts electing representatives.  

-   `elect_dist_01`: indicates the size of the districts (into which the territory is divided) for the election of the upper house. Its values are: [1]: Single- member ; [2]: Binomial; [3]: Trinomial; [4]: Quadrinomial; [5]: Pentanomial; [6]: National; [7]: Special; [99]: Not applicable.

-   `elect_dist_02`: for more than one type of election it indicates the districts (size) into which the territory is divided for the election of the upper house under the third electoral formula.

-   `elect_dist_03`: for two or more applicable electoral formulas it indicates the districts (size) into which the territory is divided for the election of the upper house under the third electoral formula. Its values are [5]: Pentanomial and [99] Not applicable.

-   `vot_struct_01`: indicates the type of vote established by the electoral reform for the upper house of the national legislative branch. Its values are: [1]: Single-member candidacy, [2]: Closed and blocked list, [3]: Closed, non-blocked list, [4]: Closed non blocked list with double preferential voting, 5]: Closed non blocked list with optional preferential voting, [6]: Open list, [7]: Open list and preferential voting, [8]: Single list linked to presidential candidacy, [9]: Preferential voting, [10]: Double simultaneous voting, [11]: Optional double preferential voting, [12]: Voting for a candidate on party lists, [13]: Mixed.

-   `vot_struct_02`: for mixed structures, the second voting structure type established by the electoral reform of the upper house is indicated. Its values are: [1]: Single-member candidacy, [2]: Closed and blocked list, [3]: Closed, non-blocked list, [4]: Closed non blocked list with double preferential voting, 5]: Closed non blocked list with optional preferential voting, [6]: Open list, [7]: Open list and preferential voting, [8]: Single list linked to presidential candidacy, [9]: Preferential voting, [10]: Double simultaneous voting, [11]: Optional double preferential voting, [12]: Voting for a candidate on party lists, [13]: Mixed.

-   `mandate`: indicates the duration of the mandate of the upper house members in years.

-   `elect_threshold`: indicates the existence of an electoral threshold that political parties must meet to qualify for seats allocation in the lower house of the national legislative branch. Its values are: [0]: Not specified, [1]: Specified. 

-   `leg_reelec`: indicates how the electoral reform regulates the reelection of members in the upper house of the national legislative branch. Its values are: [1]: No reelection, [2]: No immediate reelection, [3]: Immediate reelection, [4]: Immediate and indefinite reelection, [5]: Immediate reelection for two terms. 

-   `legis_recall`: indicates whether the legislative recall is provided for members of the upper house of the national legislative branch. Its values are:  No [0]: the regulations do not provide legislative recall, Yes [1]: the regulations provide legislative recall.

## Citation

``` r
Freidenberg, Flavia. Dir., 2023, “Electoral Systems for the Upper House in Latin America and its Reforms”, Observatory of Political Reforms in Latin America (1978-2023). Mexico City: Institute for Legal Research (IIJ-UNAM) and Washington D.C.: Secretariat for Strengthening Democracy of the Organization of American States (SSD/OAS), V2. DOI:  https://doi.org/10.5281/zenodo.8263240
```