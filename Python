import math

def alveolar_gas_equation(p_b, p_h2o, f_i, r_q):
    """
    Calculates the partial pressure of oxygen in the alveoli using the Alveolar Gas Equation.
    
    Arguments:
    - p_b: Barometric pressure (in mmHg)
    - p_h2o: Water vapor pressure (in mmHg)
    - f_i: Fractional concentration of inspired oxygen (between 0 and 1)
    - r_q: Respiratory quotient (between 0.7 and 1)
    
    Returns:
    - Partial pressure of oxygen in the alveoli (in mmHg)
    """
    p_o2 = ((p_b - p_h2o) * f_i) - (r_q * p_h2o)
    return p_o2

# Example usage:
barometric_pressure = 760 # mmHg
water_vapor_pressure = 47 # mmHg
fractional_concentration_oxygen = 0.21
respiratory_quotient = 0.8

partial_pressure_oxygen = alveolar_gas_equation(barometric_pressure, water_vapor_pressure, 
                                                fractional_concentration_oxygen, respiratory_quotient)

print("Partial pressure of oxygen in the alveoli:", partial_pressure_oxygen, "mmHg")
