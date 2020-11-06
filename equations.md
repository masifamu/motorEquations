# Processor selection:
While selecting a processor for motoring applications, there is a parameter that plays vital role
and i.e the commutation frequency(how many times motor's hall sensors change their state in one second when the motor is running).
Within every commutation period processor has to be fast enough to process signals for six switches and three hall sensors.

fe = Nm*S/120

where, Nm=no of permanent magnets.

S=mechanical RPM of the running motor.

fe=commutation frequency.
       
# Magnetic field theory:
- A current carrying wire produces a magnetic field in the area around it.
- A time changing magnetic field induces a voltage in a coil of wire if it passes through that coil.->(used in transformer)
- A current carrying wire in the presence of magnetic field has a force induced on it.->(used in motor: BIL)
- A moving wire in presence of magnetic field has a voltage induced on it.->(used in generator: BLV)

# Back EMF:
let say a motor has outer radius Rro, stack length Lst, no of turns N, no of coils in series Nm and air gap flux density Bg is rotating at a speed of wm.
According to last faraday law as mentioned above, Back EMF is generated and given by the following formula,

Eb = B*L*V = (Bg)*(2*Nm*N*Lst)*(Rro*wm) = ke*wm............................(1)

where ke=back emf constant

# Energy conservation:
let say current drawn by the motor at speed of wm is i and the produced torque is T then
ouput mechanical power = Eb*i = T*wm .......................................(2)

# Torque:
Torque is given by using the equation 1 and 2.
T = BIL*R = (Bg)*(i)*(2*Nm*N*Lst)*Rro = Kt*i

