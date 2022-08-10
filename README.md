# POC

⦁	Subject of the work
The Customer commissions the Contractor to create the following work, Annexes I and II are integral parts of the services requested in this paragraph.. 
⦁	of a reconciliation software according to previously agreed functions (see Annexes I & II)

⦁	the software shall be written in python and shall be flexible (softcoding) ('no hardcode'). Prior to the implementation of the software, a documentation for the software architecture shall be prepared accordingly, which shall design what algorithms, programming languages, etc. will be used to solve the problem.

⦁	goal is to reconcile multiple files (Excel, CSV, Word, TXT, etc.) with identification and presentation of inconsistencies at the level of individual entry (invoice, payment, etc.)

⦁	Drag and drop function for source and destination file selection
⦁	Readout of headers, match rate analysis
⦁	Suggestions for matching parameters

⦁	On the basis of the reconciliation parameters defined by the user, the first reconciliation is performed, taking into account for the first time the re-relevant amount column (proposal to user, confirmed/defined by user).

⦁	Furthermore, the software shall enable the user to resolve differences by means of proposals based on match rates between the files. Matchrates now refer to the LINES in which the defined reconciliation parameter can be found. 
⦁	Within the matching clusters defined in point 4. unique parameters are searched for, which can be found and deduced with sufficient certainty in the other cluster. (like for example the invoice number [suggestion to user and confirmation by user]).
⦁	On the basis of these individual parameters a matching on ENTRY LEVEL between the two clusters is performed. ONLY this reconciliation at the individual entry level can allow the user to make informed decisions to resolve a difference.

⦁	To assist the user in the difference handling, the software shall explain and suggest solutions for differences due to data/entries not previously reconciled or found only in one cluster (based on arithmetic operators, match rates, etc. See Appendix I, S5.).
The user can then confirm or perform further computational operations manually.. 

⦁	Further, all clusters and voting results mentioned above shall be exportable (in Excel files, CSV files or as TXT file). These exports should also show inconsistencies (on sum level [export point 4] and on entry level [export point 5]).
