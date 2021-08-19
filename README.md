# incident-angle-of-sun-and-inclined-surface
This Python script calculates and plots incident angles of the Sun relative to inclined surfaces for a given period of time and given coordinates. 

following C.D. WHITEMAN and K.J. ALLWINE, Pacific Northwest Laboratory, Richland, WA 99352: 
Whiteman, C. D. and K. J. Allwine (1986). "Extraterrestrial solar radiation on inclined surfaces." Environmental Software 1(3): 164-169.

#-------------------------------------------------------
##  INPUTS: LONG =(-180 to 180 DEG), LAT=(-90 to 90 DEG),
#   AZ = slope azimuth angle (0 to 359), IN = slope in-
#   clination angle (0 to 90 DEG), SC = solar constant,
#   IHR = hour (0 to 23), MM = minute(00 to 59),
#   D = Julian Day
#-------------------------------------------------------
##  OUTPUTS:
#   OUT1 = Instantaneous radiation [W/m²]
#   OUT2 = Radiation on the slope [W/m²]
#   OUT3 = Sun's zenith angle [DEG]
#   OUT4 = Sun's azimuth angle [DEG]
#-------------------------------------------------------
