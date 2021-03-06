# Finding Kernel in Group Decision-Making.


Licensed under [CC-BY-SA-4.0](https://github.com/nluczywo/Finding_Kernel_GDM/blob/master/LICENSE)

The data supports the work presented in the journal Mathematical Problems in Engineering of editorial Hindawi with the title *Finding Kernel in Group Decision-Making*.

**Authors:** Nadia Ayelen Luczywo <[nadia.luczywo@unc.edu.ar](mailto:nadia.luczywo@unc.edu.ar)>, 
José Luis Zanazzi <[jose.luis.zanazzi@unc.edu.ar](mailto:jose.luis.zanazzi@unc.edu.ar)>, and
Catalina Lucía Alberto <[catalina.alberto@unc.edu.ar](mailto:catalina.alberto@unc.edu.ar)> 

## Description of the Data.

For each subproblem, each participant makes an assessment that represents how many times is a preferred element when compared to the adjacent one.
The collected data is shown in the way expressed following:
- By row, each of the participants is listed.
- By column, the elements compared when analyzing the particular sub-problem are enumerated.

Seven evaluation criteria were are adopted, which include: operational modality (MO), cost (CO), provider experience (EXP),  vehicle fleet (FL), improvement of service (MS), hygiene and safety conditions (HS), and treatment and final disposal (TR).

A spreadsheet is presented for each subproblem and for each iteration. 
Thus, the sheets included in the dataset are:
- Spreadsheet `Wj1` shows the first iteration of the individual allocation to analyze the weight subproblem of the criteria.
- Spreadsheet `Wj2` shows the second  iteration of the individual allocation to analyze the weight subproblem of the criteria.
- Spreadsheet `MO1` shows the first iteration of the individual allocation to analyze the subproblem of analysis of the alternatives for the Operational Modality criterion.
- Spreadsheet `MO2` shows the second iteration of the individual allocation to analyze the subproblem of analysis of the alternatives for the Operational Modality criterion.
- Spreadsheet `CO1` shows the first iteration of the individual allocation to analyze the subproblem of analysis of the alternatives for the Cost criterion.
- Spreadsheet `CO2` shows the second iteration of the individual allocation to analyze the subproblem of analysis of the alternatives for the Cost criterion.
- Spreadsheet `EXP1` shows the first iteration of the individual allocation to analyze the subproblem of analysis of the alternatives for the Experience criterion.
- Spreadsheet `EXP2` shows the second iteration of the individual allocation to analyze the subproblem of analysis of the alternatives for the Experience criterion.
- Spreadsheet `FL1` shows the first iteration of the individual allocation to analyze the subproblem of analysis of the alternatives for the Vehicle fleet criterion.
- Spreadsheet `MS1` shows the first iteration of the individual allocation to analyze the subproblem of analysis of the alternatives for the Improvement of Service criterion.
- Spreadsheet `HS1` shows the first iteration of the individual allocation to analyze the subproblem of analysis of the alternatives for the Hygiene and safety conditions criterion.
- Spreadsheet `TR1` shows the first iteration of the individual allocation to analyze the subproblem of analysis of the alternatives for the Treatment and final disposal criterion.

In order to obtain the utilities per participant, it is necessary to make the product of each element with its adjacent one. 
For  example, from Spreadsheet `Wj1`: 
| Participant | Segundo encabezado | MO | CO | EXP | FL | MS | HS | MO |
| ------------- | ------------- |------------- |------------- |------------- |------------- |------------- |------------- |------------- |
|  1  | Times of preferences about the adjacent|  3  |  1.5  |   2  |  1.5  |  1.5  |  2  |  1  |
|  1  | Utilities for participant | 3 * 13.5  | 1.5 * 9  |  2 * 4.5  | 1.5 * 3  | 1.5 * 2  | 2 * 1 | 1  |
