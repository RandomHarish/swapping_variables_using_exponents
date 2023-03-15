class swapping
{
    public static void main(String args[])
    {
        double x=2;
        double y=1024;
        System.out.println("initially- x="+x+" y="+y);
        x=Math.pow(x,y);
        y=Math.round(Math.pow(x,1/y));
        x=Math.log(x) / Math.log(y);
        System.out.println("end result- x="+x+" y="+y);
}
    }
