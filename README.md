# DigitalCobinationalLock


This Digital Combinational Lock demonstrates a secure access control system using digital electronics. The primary objective is to validate a 4-digit PIN entered by the user using logic gates, D flip-flops, and a magnitude comparator.

Key Features:
Input System: Users input a 4-digit PIN using switches, which is stored in D flip-flops acting as shift registers.
Verification Logic: A magnitude comparator validates the user-entered PIN against a pre-saved code.

Feedback System:
Correct PIN activates a green LED to indicate successful access.
Incorrect PIN triggers a red LED and buzzer for error indication.

Display: Three 7-segment displays show the entered PIN digits for user convenience.
Reset Option: A reset button allows users to clear inputs and retry.

Components Used:
Logic ICs, 7-segment displays, priority encoder, magnitude comparator, LEDs, and a breadboard.

Working Principle:
The system sequentially processes each digit of the entered PIN, compares it with the saved PIN, and provides immediate feedback. If all digits match, access is granted; otherwise, an error signal is triggered.
