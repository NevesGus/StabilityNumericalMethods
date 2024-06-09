# StabilityNumericalMethods
The project involved implementing and analyzing the stability of five numerical methods for solving initial value problems (IVPs):

    Explicit Euler: A first-order method, simple but with a limited stability region.
    2nd and 4th Order Runge-Kutta: Single-step methods with higher accuracy and wider stability regions than Euler.
    2-Step Adams-Bashforth: An explicit multistep method that requires previous values for calculation.
    2-Step Adams-Moulton: An implicit method that needs an iterative process (predictor-corrector or Newton) to find the solution.

The stability of each method was evaluated numerically using a linear test problem:

u'(t) = λu(t), u(0) = 1, t ∈ [0, 10]

The analysis included:

    Stability Regions: Generating plots showing the absolute stability regions of each method in the complex plane.
    Comparison of Adams-Moulton: Comparing the stability regions of the Adams-Moulton method using predictor-corrector and Newton approaches.
    Behavior in Extreme Cases: Generating plots of numerical solutions for values of 'h' close to the stability limit, showing the behavior of the methods in critical situations.
    Order of Convergence: Estimating the temporal order of convergence of each method and comparing it with the expected theoretical order.

The report discusses the advantages and disadvantages of each method based on the results obtained, aiding in the choice of the most suitable method for different types of problems.
