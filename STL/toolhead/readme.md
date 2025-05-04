## Design choices for height adjustable tool heads:

- The toolheads are assembled and wired completely before mounting them onto the gantry.
- Belts are installed and adjusted prior to mounting the toolheads.
- The EBB36 or other CAN boards are mounted to the stepper motor only and loose the 3rd support leg connecting it to the main body of the toolhead.  Certainly it's possible to redesign that support, but a simple support is not possible with the large collection of extruders we have available to us.  Remember to allow for height adjustments if you replace that lost support.
- I'm not sure I've followed the XOL ethos of absolute minimum weight and would welcome anyone's expertise in trimming weight.  I only ask it be reliably printable in ABS without custom supports.
- Electronics should be wired with an umbilical only and the use of CANbus is highly recommended.
