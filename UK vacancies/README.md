# UK vacancies
There are record numbers of vacancies advertised in the UK at the moment ([June 2022](https://www.ons.gov.uk/employmentandlabourmarket/peopleinwork/employmentandemployeetypes/bulletins/jobsandvacanciesintheuk/latest)).

How do the job ads match with available potential employees (vacancies by sector)?

**Data (in data folder):**
- [Overview](https://www.ons.gov.uk/employmentandlabourmarket/peopleinwork/employmentandemployeetypes/bulletins/jobsandvacanciesintheuk/latest)
- Seasonally adjusted quarterly vacancies [dataset](https://www.ons.gov.uk/file?uri=/employmentandlabourmarket/peoplenotinwork/unemployment/datasets/vacanciesbyindustryvacs02/current/vacs02jun2022.xls)
- Unemployment by previous industry sector quarterly [dataset](https://www.ons.gov.uk/file?uri=/employmentandlabourmarket/peoplenotinwork/unemployment/datasets/unemploymentbypreviousindustrialsectorunem03/current/unem03jun2022.xls)
- Seasonally adjusted total employment and unemployment quarterly [dataset](https://www.ons.gov.uk/file?uri=/employmentandlabourmarket/peopleinwork/employmentandemployeetypes/datasets/employmentunemploymentandeconomicinactivityforpeopleaged16andoverandagedfrom16to64seasonallyadjusteda02sa/current/a02sajun2022.xls)

**Issues & Assumptions:**
- Vacancies data misses industries A and T. So, we will be undercounting. However, agriculture won't have thousands of jobs available and I'm not too worried about this underestimating the numbers too much.
- The total of unemplyed by sector did not match the total unemployed number. Thus, I used the sector information and scaled it to the official total unemployment number by taking percentages of total and applying them to a new total.

