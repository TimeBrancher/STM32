ABOUT:
|> This project is a proof of concept, i coded to practice the use of SWD that i watch in a tutorial
HOW IT WORKS:
|> It make blink a led, every time that its turn on/off the state of the pin 7 is taked and stored in a variable, then the state and number of iteration are printed in the debugger console, also you can track the variable with SWD Data Trace TimeLine and see how the value constantly change between 0 and 1
WHAT I LEARN:
|> The existence of GPIO_ReadPin, the use and configuration of SWD, what is SWD and its relation with st-link, how to set the _write function to use ITN as exit for the string
FUN FACT:
|> I had to declare the variable state outside the main function because the processor despite of use volatile type, keep deleting the variable in the optimization step, the better solution that i find is to simply declare it outside.
Proof Of Concept:
|> https://www.youtube.com/shorts/_SO9AgT03_c
