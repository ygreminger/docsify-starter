# Dreieck, Viereck

Source Code:

```java
package com.example;

public class Punkt {
    private double xKor;
    private double yKor;

    public Punkt(double x, double y){
        xKor = x;
        yKor = y;
    }

    public void addToX (int wert)
    {
        xKor += wert;
    }

    public void addToY (int wert)
    {
        yKor += wert;
    }

    public void setxKor(double xKor) {
        this.xKor = xKor;
    }

    public void setyKor(double yKor) {
        this.yKor = yKor;
    }

    public double getxKor() {
        return xKor;
    }

    public double getyKor() {
        return yKor;
    }

    public String getPunkt(){
        return xKor + "/" + yKor;
    }

}
```