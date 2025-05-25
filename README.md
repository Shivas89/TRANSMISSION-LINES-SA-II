# TRANSMISSION-LINES-SA-II

# Operation Falcon Eye

Theme: Static Observation vs Dynamic Scanning

![image](https://github.com/user-attachments/assets/2b3eb6b0-aedf-4309-9ea9-9ada8885260e)

# Introduction
In modern defense and intelligence systems, satellite-based surveillance and communication are critical. Depending on the mission—whether constant regional monitoring or detailed global imaging—the choice between Geostationary Earth Orbit (GEO) and Low Earth Orbit (LEO) satellites becomes pivotal.

This report compares GEO and LEO satellites from a military intelligence perspective—under the codename Operation Falcon Eye—where situational awareness, response speed, and image clarity can define success on the battlefield.


# Comparison 
Parameter	GEO Satellites	LEO Satellites
Altitude	~35,786 km above the equator	~500–2,000 km
Orbital Period	24 hours (synchronous with Earth’s rotation)	90–120 minutes
Coverage Area	~1/3 of Earth's surface	Narrow swath; frequent revisits needed
Latency	High (~250–600 ms)	Low (~20–50 ms)
Signal Strength	Weaker due to distance	Stronger (closer to Earth)
Use Case	Continuous monitoring of fixed regions	Rapid scanning with high detail
Examples	INSAT, GOES, GSAT (Weather, broadcast)	KH-series, Starlink, Earth-observation constellations
Power Requirement	High (more transmission power)	Lower (shorter link distance)


 # GEO Satellite Characteristics:
Orbit matches Earth’s rotation → appears stationary from Earth.

Ideal for communication, weather monitoring, TV broadcasting.

Limited in capturing high-resolution images due to high altitude.

Beam divergence increases → lower spatial resolution.

![image](https://github.com/user-attachments/assets/c035d69a-fe75-4a3e-ac80-6c4038495f84)


# LEO Satellite Characteristics:
Much closer to Earth → orbits ~16 times per day.

Excellent for high-resolution Earth imaging, reconnaissance, spy operations.

Needs a constellation for continuous coverage.

Ideal for 3D terrain mapping, disaster monitoring, and missile tracking.

![image](https://github.com/user-attachments/assets/8dcb6323-0403-4044-a2df-4991a6a7bf76)

# 1. Orbital Mechanics
Kepler’s Third Law (Orbital Period)
𝑇
=
2
𝜋
𝑟
3
𝐺
𝑀
T=2π 
GM
r 
3
 
 
𝑇
T = orbital period (seconds)

𝑟
r = distance from Earth's center (meters)

𝐺
G = gravitational constant 
6.674
×
10
−
11
6.674×10 
−11
 

𝑀
M = mass of Earth 
5.972
×
10
24
 
kg
5.972×10 
24
 kg

# Application:
Determines satellite orbit time, e.g., a LEO satellite orbits Earth every ~90 minutes, ideal for frequent surveillance passes.
![image](https://github.com/user-attachments/assets/4ab4792e-9523-4188-941f-bbda87fc9801)

 # 2. Free Space Path Loss (FSPL)
FSPL (dB)
=
20
log
⁡
10
(
𝑑
)
+
20
log
⁡
10
(
𝑓
)
+
92.45
FSPL (dB)=20log 
10
​
 (d)+20log 
10
​
 (f)+92.45
𝑑
d = distance (km),

𝑓
f = frequency (GHz)

# Application:

Used to estimate signal strength at ground stations.

GEO satellites (35,786 km) suffer higher FSPL, requiring high-gain antennas.
![image](https://github.com/user-attachments/assets/1796d970-a9b0-4719-a06f-4b95d9a3e5b7)

# 3. Slant Range (Distance from Satellite to Ground Point)
𝑅
=
(
𝑅
𝐸
+
ℎ
)
2
−
𝑅
𝐸
2
cos
⁡
2
(
𝜃
)
−
𝑅
𝐸
sin
⁡
(
𝜃
)
R= 
(R 
E
​
 +h) 
2
 −R 
E
2
​
 cos 
2
 (θ)
​
 −R 
E
​
 sin(θ)
𝑅
𝐸
R 
E
​
 : Radius of Earth

ℎ
h: Satellite altitude

𝜃
θ: Elevation angle

#  Application:
Calculates distance to ground target for timing and imaging window, critical in missile early warning systems.
![image](https://github.com/user-attachments/assets/7ec744fd-df7a-478a-aa88-2d916191a965)

# 4. Ground Coverage Radius
For a satellite at altitude 
ℎ
h:

𝑟
=
𝑅
𝐸
⋅
cos
⁡
−
1
(
𝑅
𝐸
𝑅
𝐸
+
ℎ
)
r=R 
E
​
 ⋅cos 
−1
 ( 
R 
E
​
 +h
R 
E
​
 
​
 )
# Application:
Determines how much of Earth’s surface the satellite can "see" at one time—important for constellation design.
![image](https://github.com/user-attachments/assets/2cf0d926-f9a5-4d38-aae9-293f2f3e411a)

# 5. Resolution of Imaging System (GSD: Ground Sample Distance)
GSD
=
𝐻
⋅
𝑝
𝑓
GSD= 
f
H⋅p
​
 
𝐻
H: Satellite height above ground

𝑝
p: Pixel size of sensor

𝑓
f: Focal length of optical system

# Application:

Used in LEO spy satellites to estimate clarity of ground targets, e.g., reading license plates or identifying missile silos.
![image](https://github.com/user-attachments/assets/2d4e3b2d-8636-41dd-b082-9b53edec026b)













