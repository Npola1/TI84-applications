# TI-84 Applications

## What are the projects?

A collection of 16 TI-BASIC programs for TI-84 calculators. My objective was to automate maths calculations and explore calculator programming through utilities and text animations. The programs animations, degrees to radian conversion, hyperbolic trigonometric functions, cross products, polynomial multiplication, triangle calculations, and quadratic-formula support.

## What did I do to write the programs?

I translated mathematical formulas into TI-BASIC instructions using variables, input prompts, conditional branches, and displayed results. I also used text output and screen-clearing commands to create animations. The programs were exported as `.8xp` files with TI Connect CE.

## How do you run the programs?

1. Download this repository using **Code → Download ZIP** and extract it.
2. Install [TI Connect CE](https://education.ti.com/en/products/computer-software/ti-connect-ce-sw) and connect your TI-84 calculator by USB.
3. Open a `.8xp` file in the Program Editor, then choose **Actions → Send to Calculators** and send it to your calculator.
4. Press **PRGM**, select the program under **EXEC**, and press **ENTER** to select it, then **ENTER** again to run it. Follow the prompts and press **ENTER** when paused. Check the degree/radian mode before trigonometric calculations.

See TI's [transfer instructions](https://education.ti.com/en/customer-support/knowledge-base/sofware-apps/product-usage/11492) and [execution guide](https://education.ti.com/html/eguides/graphing/84PlusCE-T/NL/content/eg_84tprgm/m_entercommandline/m_exeprogram.HTML).

## How do the files work?

Each `.8xp` contains a separate tokenized TI-BASIC program that the calculator interprets directly. Matching `.txt` files let you read the same code on GitHub; use `.8xp` files for calculator transfers. Maths programs collect inputs, store variables, evaluate formulas, and display answers or intermediate values. `DISP`, `ZERO`, and `ZERO2` repeatedly display text patterns; `IMBORED` displays text art. Press **ON** to interrupt a running program and choose **Quit** if prompted. Programs can overwrite calculator variables; `VARRESET` assigns 1 to variables rather than deleting them.
