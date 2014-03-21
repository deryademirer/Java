public static void main(String[] args) {
    int secim;
    String cevap;

    circle c=new circle();

    Scanner input=new Scanner(System.in);
    do{

    System.out.println("Welcome to Circle/Square Tester. Please select an entry from menu:");
    System.out.println("1 - Modify a circle object");
    System.out.println("2 - Modify a square object");
    System.out.println("3 - Compare square and circle");
    System.out.println("4 - Exit");
    secim=input.nextInt();


    if(secim==1)
    {
        System.out.print("Enter a radius:");
        c.setRadius(input.nextDouble());
        System.out.println("Area="+c.getArea());
        System.out.println("Perimeter="+c.getPerimeter());
    }
    System.out.println("devam etmek istiyormusunuz?(E/H)");
    cevap=input.next();
    }
    while(cevap=="E" || cevap=="e");


}
}

import java.util.Scanner; public class square { Scanner input=new Scanner(System.in); double length; private double area; private double perimeter;

public square()
{
    length=0;
}
public double getLength()
{
    return length;
}
public void setLength(double length)
{
    this.length=length;
}
public double getArea()
{
    area=length*length;
    return area;
}
public double getPerimeter()
{
    perimeter=4*length;
    return perimeter;
}
}

import java.util.Scanner; public class circle {

    Scanner input=new Scanner(System.in);
    private double radius;
    double area;
    double perimeter;

    public circle()
    {
        radius=0;
    }
    public circle(double radius)
    {
        this.radius=radius;
    }
    public double getRadius()
    {
        return radius;
    }
    public void setRadius(double radius)
    {
        this.radius=radius;
    }
    public double getArea()
    {
        area=Math.PI*radius*radius;
        return area;
    }
    public double getPerimeter()
    {
        perimeter=2*Math.PI*radius;
        return perimeter;
    }
}
