# Data dictionary
Name, unit and source are taken from the WDI series metadata. Type/definition check and **caveats are for you to write** after reading the metadata sheet.

| column | WDI code | indicator | unit | source | type | caveats (yours) |
|---|---|---|---|---|---|---|
| u5mr | SH.DYN.MORT | Mortality rate, under-5 | per 1,000 live births | UN IGME (UNICEF, WHO, World Bank, UN Population Division) | float | |
| fem_sec_enroll | SE.SEC.ENRR.FE | School enrollment, secondary, female | % gross | UNESCO Institute for Statistics | float | |
| gdp_pc_ppp | NY.GDP.PCAP.PP.KD | GDP per capita, PPP | constant 2021 international $ | ICP / World Bank / OECD / IMF | float | |
| health_exp_gdp | SH.XPD.CHEX.GD.ZS | Current health expenditure | % of GDP | WHO Global Health Expenditure Database | float | |
| fertility | SP.DYN.TFRT.IN | Fertility rate, total | births per woman | UN World Population Prospects | float | |
| sanitation | SH.STA.BASS.ZS | People using at least basic sanitation | % of population | WHO/UNICEF JMP | float | |
| water | SH.H2O.BASW.ZS | People using at least basic drinking water | % of population | WHO/UNICEF JMP | float | |
| electricity | EG.ELC.ACCS.ZS | Access to electricity | % of population | World Bank SDG7 electrification dataset | float | |
| measles_imm | SH.IMM.MEAS | Immunization, measles | % of children 12-23 months | WHO / UNICEF | float | |
| urban_pct | SP.URB.TOTL.IN.ZS | Urban population | % of total population | UN World Urbanization Prospects | float | |
| fem_literacy | SE.ADT.LITR.FE.ZS | Literacy rate, adult female | % of females 15+ | UNESCO Institute for Statistics | float | |
| skilled_birth | SH.STA.BRTC.ZS | Births attended by skilled health staff | % of total | UNICEF / DHS | float | |
| unemployment | SL.UEM.TOTL.ZS | Unemployment, total (modeled ILO estimate) | % of labor force | ILO modelled estimates | float | |
| gov_health_exp_gdp | SH.XPD.GHED.GD.ZS | Domestic general government health expenditure | % of GDP | WHO Global Health Expenditure Database | float | |
| Country Name / Country Code | | country | text | World Bank | str | |
| year | | year | int | | int | |
