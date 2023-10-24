# 0x16 ALX SIMPLE SHELL TEST SUITE

## DESCRIPTION

- This is a set of testing scripts for all simple shell tasks except betty and memory checks with valgrind.
- This suite is tested on Ubuntu 20.04 WSL.

## FEATURES

- Runs a checker on your compiled code and displays `OK` if you have the expected output.
- Displays command to be executed before it starts.
- Displays number of `OK` outputs at the end and total number of commands run.
- Check only specific tasks instead of whole suite at once.

*DISCLAIMER: Currently cannot check for valgrind errors so you must do that manually. If you get OK and also no memory leaks then expect GREEN on the Intranet. If you get OK and you have memory errors you will get RED in the intranet.*

## HOW TO USE

#### copy & paste each highlighted command to your terminal and press `enter ↲` one after the other

1. `git clone https://github.com/CletsyMedia/alx-shell_test-suite.git` clone this repo into your simple_shell directory
2. `mv alx-shell_test-suite/simple_shell_project TEST_SUITE` - Move the simple_shell_project directory to your simple_shell directory, renaming as TEST_SUITE
3. `cd TEST_SUITE` - Navigate into the TEST_SUITE directory
4. `chmod +x checker.bash runchecker.bash` - make them executable
5. `mv runchecker.bash ../runchecker.bash` - move runchecker.bash to your simple_shell directory.
6. `cd ..` - Navigate back to simple_shell.
7. `rm -rf alx-shell_test-suite` - Remove the residue files.
8. `./runchecker.bash` - to run the whole suite from task 1 - 16 at once.

--- OPTIONS ---

`./runchecker.bash #`

replace # with a number from 1- 16 to only run checks from a specific task e.g. to check task 3 only, do `./runchecker.bash 3`
