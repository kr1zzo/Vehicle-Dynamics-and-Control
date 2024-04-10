# Management of the longitudinal and lateral dynamics of the vehicle

### Course : [Vehicle Dynamics and Control](https://www.fer.unizg.hr/en/course/vdac)

## Project for Modeling and management of vehicle dynamics

In the first part of the project, estimators of vertical forces and estimators of longitudinal speed were created. From the response, it is possible to see how the estimated values obtained through the formulas and using the Kalman filter correspond to the real values that can be seen in Simulink. After the estimation, Cruise control was created, which consists of a PI regulator that regulates the speed that follows the reference value and an active turning system that enables the vehicle to turn and thereby avoid obstacles. Finally, Traction control was implemented, which successfully prevented the vehicle from skidding.

## Execution

In the `Simulink` run `MUDV_project.slx` file from `scripts` folder. The simulation will start and you will be able to see the results of the estimators, cruise control, active turning system, and traction control.

## Results

Resulst can be found in `Docuemntation/MUDV_projekt_izvjestaj.pdf` file.

## Credits

#### [&copy; Faculty of Electrical Engineering and Computing, University of Zagreb, 2022/2023](https://www.fer.unizg.hr/)

&NewLine;

Contributors names and contact info

Author|GitHub | e-mail
| :--- | :---: | :---:
Enio Krizman  | [@kr1zzo](https://github.com/kr1zzo) | enio.krizman@fer.hr

Academic title| Lecturer
| :--- | :---: 
Prof. Dr. Sc. | Šandor Ileš
Prof. Dr. Sc. | Jadranko Matuško
Prof. Dr. Sc. | Stjepan Bogdan