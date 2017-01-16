# How to check and update line list

## What is process line list?

Process line list is a database that store all the information associated with each individual process line in a plant design. It is one of the most essential document required in engineering basic and detailed design phases. The list is constantly updated whenever changed were made and marked on Piping and Instrument Diagrams (PIDs). From the process line list, instrument department and piping department can quickly retrieved the information they need, and guarantee the ordering of instrument or pipelines accurate. Pipe line information is also crucial when facing 3D modeling challenges, as the elevation, length and pipe size/diameter will greatly affect the piping layout and space management planning. 

## What information can be retrieved from the list?


The line list should consist of two sections: **mechanical** and **process**. 

The mechanical section often only contains *line numbers, connections and tie-points* but sometimes includes the *pipe specification*; if the line list requires mating a 4-inch flange to a 6-inch one, it's mechanical's fault. 

The process portion covers *corrosion, safety and pressure relief.* Process parameters such as *operating/design temperature/pressure *and *testing pressure* are also included for other disciplines' reference. 


## Which column(s) to look at?

Refer to the following list for guideline while checking and updating the line list, [x] indicates the column code.

- [L]Size (NB): to check/update latest size of a pipe on PID

- [N]Fluid: check/update the latest fluid code of a pipe on PID

- [O]Pipe class: check/update the code from PID that indicates construction material of the process pipe

- [P]Line number: the last three-digit number indicated from PID of each process pipe line

- [Q]Insulation type: (optional) the last supplimentary code from process pipe line on PID

- [V]From: starting point of the pipeline, it can be another line (input 6-digit line number), an equipment/instrument/package (input corresponding tag) or a general location (e.g. GRADE or HEADER)

- [W]To: ending point of the pipeline, it can be another line (input 6-digit line number), an equipment/instrument/package (input corresponding tag) or a general location (e.g. GRADE or HEADER)

- [AF]Scope: put AGILITY/VDZ/MW

**After checking or updating one line, format the whole line as 'checked' (marked as good via preset formating).**


## Use of filter and auto completion

Filters are provided to filter out object of interest and batch input desired data. Please do not modifiy other column besides the ones provided in the above section as auto-completion will execute from the database. 

If you want to add new line, insert a new line and **fill (not copy)** the line following the exact content from nearby line, then modify the changes you wanna make.

## Version tracking and history

The document is shared and history of up to 30 days is enabled. Whenever a changed is made by others, colored markup will appear near to the modified cell. Only focus on the targeted drawing batches and do not modify other regions.

Any doubt, ask.

----
Updated by Stephen on 01/16/2017 9:13:53 AM 
