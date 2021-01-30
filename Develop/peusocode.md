# Password Generator App


WHEN generate password button is clicked

PROMPT user for password length
INIT length := user input from prompt

user enters value from 8 to 128

if length is BETWEEN 8 and 128
    THEN 
        INIT useSpecial := CONFIRM special chars
        INIT useNums := CONFIRM numeric chars
        INIT useLower := CONFIRM confirm lower case chars
        INIT useUpper := CONFIRM uppercase chars

    
    IF useSpecial or useNums or useLower or useUpper
    THEN
        generate password containing the correct types and length 
    END IF
ELSE
    ALERT password length error message
END IF

