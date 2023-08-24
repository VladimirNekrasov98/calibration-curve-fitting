# calibration-curve-fitting

## brief project description

This project is devoted to finding an approximate functional dependence to approximate the calibration curve of a dry air vacuum gauge. The calibration curve is a set of points defined in CSV format that represent the relationship between the pressure and the vacuum gauge output signal. The goal of the project is to find a function that best approximates these points with minimal error. For this purpose, the project uses various machine learning methods, such as regression and the method of group consideration of arguments, as well as a genetic regression algorithm from the gplearn library. The project allows you to compare the results of different methods and choose the most appropriate one for a particular case.

## data description

- U - voltage, V;
- P - pressure, Pa;
- dP/dU - first derivative, Pa/V;
- d2P/dU2 - second derivative, Pa/V^2.
