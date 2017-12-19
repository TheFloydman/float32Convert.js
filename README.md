# baseConvert.js

float32Convert.js by Dan Floyd (Floydman). Convert between 32-bit floats and
decimal numbers. Based on example code created by Eric
(https://stackoverflow.com/a/10564792/9029177).

Usage: float32Convert(inputNumber, toFloat, otherBase)
- "inputNumber" is the number you want to convert. This can be in any base and
MUST be formatted as a String if it is not in Base 10. (MANDATORY)
- "toFloat" indicates which way to want to convert. "True" returns a String in
Base otherBase; "false" returns a decimal number. (MANDATORY)
- "otherBase" is the non-decimal base you are converting to/from. This is
probably 2 (binary) or 16 (hexadecimal), though it can be an integer from
2 - 36. (MANDATORY)
