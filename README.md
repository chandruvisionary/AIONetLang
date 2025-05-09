# AIONetLang

**AIONetLang** is a lightweight, human-readable, AI machine-to-machine communication language designed by **Chandru Visionary**. This project includes an interpreter built with Python for executing AIONetLang scripts.

---

## Features

- Variable declarations with `SET`
- Arithmetic operations (`+`, `-`, `*`, `/`)
- Console output using `SEND`
- User input with `RECEIVE`
- Conditional statements using `IF ... THEN / END IF`
- Clean, readable syntax

---

## Example AIONetLang Program

```plaintext
BEGIN
    SET num1 = 20
    RECEIVE num2 FROM "INPUT"
    SET sum = num1 + num2
    SEND "Sum: " + sum TO "DISPLAY"
    IF sum > 30 THEN
        SEND "The total is above 30!" TO "DISPLAY"
    END IF
END
