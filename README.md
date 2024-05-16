# Ray-tracing
A code to calculate losses through a simple system of lenses based on ray-tracing using simple geometrical optics.

The user is able to specify a lens setup, with target size, lens sizes, lens focal lengths, and spacing. The code will then trace rays through the system, and estimate how many rays make it to the output. It will indicate image planes and calculate magnification. You can also insert 'non-focussing' optics to the beam, which have no effect on ray propogation, but can be used to indicate whether objects like mirrors/filters placed at that position will be large enough.

Use the standard RayTracing script. RayTracing VISAR shows how you can replicate chunks of the code to simulate beamsplitters, by changing variable names. There are some other minor differences between the two, but none to the funamentals of the code.
