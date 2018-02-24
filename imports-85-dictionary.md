# Data Dictionary

Database: 1985 Auto Imports Database  


### Sources and history

- Creator: Jeffrey C. Schlimmer  
- Date created: May 19, 1987  
- Sources:
    - 1985 Model Import Car and Truck Specifications from  Ward's Automotive Yearbook
    - Personal Auto Manuals from the Insurance Services Office
    - Insurance Collision Report from  the Insurance Institute for Highway Safety

### Variables

1. symboling: integers from -3 to 3 denoting risk levels (lower meaning less risky)
2. normalized_losses: real, number of losses from 65 to 256
3. make: character name of the make of the car
4. fuel_type: character, either diesel or gas
5. aspiration: character, type of engine either std or turbo
6. num_of_doors: character, either four or two
7. body_style: character
8. drive_wheels: character, either 4wd, fwd, or rwd
9. engine_location: character, either front or rear
10. wheel_base: real, in inches
11. length: real, in inches
12. width: real, in inches
13. height: real, in inches
14. curb_weight: integer, in pounds
15. engine_type: character
16. num_of_cylinders: character
17. engine_size: integer, in cubic inches
18. fuel_system: character
19. bore: real, in inches, diameter of engine cylinder
20. stroke: real, in inches, distance travelled by piston
21. compression_ratio: real, ratio of greatest to smallest capacity of compression chamber
22. horsepower: integer
23. peak_rpm: integer
24. city_mpg: integer
25. highway_mpg: integer
26. price: integer, in dollars

### Missing Values

- Denoted by "?"  
- In variables 2, 6, 19, 20, 22, 23, and 26