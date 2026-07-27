# TI SR-56 Simulator

Simulates the Texas Instruments SR-56 programmable calculator (mostly.)

The Slide-Rule handheld utilized the TMC0501 scalable calculator architecture, featuring 10 memory registers and 100 program steps. It introduced features that later became standard in its successors, such as the t-register, which facilitated comparison tests and conditional branching based on the relationship between the t-register and the display register. Programming capabilities encompassed conditional execution, unconditional jumps (GOTO), and subroutines. With it's 40 keys it  included approximately 61 scientific functions, covering trigonometric, logarithmic, exponential, and statistical capabilities. 

<img width="481" height="705" alt="image" src="https://github.com/user-attachments/assets/016d7b3d-5b7c-44ba-ae56-bb4e653eee6d" />
<img width="483" height="368" alt="image" src="https://github.com/user-attachments/assets/3ffb5087-eb39-451e-adf2-55cd5da3d317" />

## BlackJack Demo
Before personal computers, this was my first experience programming.  

Eddie's BlackJack program written in 1977 at age 14 with the 100-step memory limit.  

## === INSTRUCTIONS ===

1. Open "https://edwize.github.io/TI-56-simulator/" in a browser.
2. "BlackJack77" is preloaded on startup. or scroll to bottom of Program Memory. 
3. Key "GTO 86 R/S" to Run/Stop program in memory. 
4. You're the BOSS. Click R/S again to get your first card.
5. Key "8055 R/S" to HIT, or just "R/S" for the dealer's turn and results displayed.
6. "R/S" for next hand.

### Notes

* There is a brief pause for the accumulating Dealer totals.
* "BooBoo" is a bust of either Boss or Dealer hand.
* "BB.DD" is final Boss.Dealer hand totals if not over 21.
* "RCL 4" will type "BOSS" with 2 keystrokes.
* "RCL 1" or "RCL 2" for Boss or Dealer scores.
* "0.xxx STO 0" to add random number salt.
* Scroll below calculator for Program Memory window.
* Prog Memory window has Turbo and Debug tools.
