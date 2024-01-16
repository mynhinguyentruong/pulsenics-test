# Pulsenics Assessment

## Goals

User is able to:

- Enter X and Y Coordinates.
- Select from dropdowns to choose either Linear, Quadratic or Cubic Curve.
- See the coordinates they've entered and the curves of best fit.
- See the equation of the curve of best fit.

## Assumptions made

- Why I chose Blazor: Blazor is built on top of ASP.NET Core, a mature and
  powerful server-side framework. This integration allows seamless communication
  between the client and server components of your application. I can can share
  code and logic between the client-side and server-side. This leads to
  increased code reuse and a more consistent development experience.

- X and Y Coordinates: I restricted user to only input numbers range between
  -100 and 100. For Quadratic Curve, at least 3 or more X-Y Coordinates must be
  provided in order to calculate the equation. For Cubic Curve, at least 5 or
  more X-Y Coordinates must be provided in order to calculate the equation.

## Libraries and Dependancies:

- Three additional libraries were used in the project:
  1. Mathnet: Perform mathematics and equation.
  2. Syncfusion: Display Curves and Coordinates.
  3. MathJaxBlazor: Display the equation formulas.
