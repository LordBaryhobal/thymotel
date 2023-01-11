# Thymotel

This is a school project involving [Thymios](https://www.thymio.org/), which are two-wheeled robots with infrared captors, buttons and more.

It is a collaboration between [@MatB3](https://github.com/MatB3) and [myself](https://github.com/LordBaryhobal).

Our project is a laser-cut wooden hotel for Thymios.

1. Thymio A scans a Lego barcode holding his id.
2. It then drives to the ramp following a black line.
3. It establishes infrared communication with Thymio B.
4. Thymio B selects an empty "room" and indicates to Thymio A that it can continue.
   - (If all the rooms are occupied, Thymio A is told so and turns red.)
5. Thymio A proceeds on the ramp and into the 2-dimensional "elevator".
6. A few seconds later, Thymio B moves the elevator to the appropriate room using strings wrapped around axles connected to its wheels.
7. Thanks to a system of pulleys and counterweight, the small motors are able to displace the whole elevator including Thymio A.
8. When it arrives to the selected room, Thymio A leaves the "cabin" and drives into the box.
9. Thymio B then returns the elevator to its starting position, ready to welcome new clients.

For more info on the realization of the project check the [report (french)](rapport/main.pdf) or alternatively download [projet_thymotel.zip](projet_thymotel.zip)