# area-of-a-cylinder
from math import *
def surface_area(r,h):
    a_base = pi*(r**2)
    a_lateral = 2*pi*r*h
    a_total = 2*(a_base) + a_lateral
    
    print ("Surface area of cylinder is", a_total)
    
def volume(r,h):
    v = pi*(r**2)*h
    print ("Volume of cylinder is",v)
surface_area (18,24)
volume(18,24)
