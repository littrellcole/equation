# equation
public class Position {
    public static void main(String[] args) {
        math();
    }
    public static void math(){
       positionx();
        volecityx();
        positiony();
        volecityy();

    }
    public static void positionx(){
        double x;
        double o;
        double i;
        double t;
        double a;
        //double radians; Math.sin(radians, radians = Math.toRadians(z);	x0 + v0xΔt + 1/2 ax(Δt)2

        t = 4.5;
        o = 0;
        i = 0;
        a = -5.2;

        x = o + i * t + .5 * a * t * t;

        System.out.println(x);
    }
    public static void volecityx(){
        //vx	 = 	v0x + axΔt
        double v;
        double x;
        double a;
        double t;

        v= 0;
        a= -5.2;
        t= 4.5;
        x= v+a*t;

        System.out.println(x);
    }
    public static void positiony(){
        double x;
        double o;
        double i;
        double t;
        double a;
        //double radians; Math.sin(radians, radians = Math.toRadians(z);	x0 + v0xΔt + 1/2 ax(Δt)2

        t = 4.5;
        o = 0;
        i = 6.4;
        a = 0;

        x = o + i * t + .5 * a * t * t;

        System.out.println(x);
    }
    public static void volecityy(){
        //vx	 = 	v0x + axΔt
        double v;
        double x;
        double a;
        double t;

        v= 6.4;
        a= 0;
        t= 4.5;
        x= v+a*t;

        System.out.println(x);
    }
}
