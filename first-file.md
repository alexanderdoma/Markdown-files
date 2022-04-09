# Aqui escribire los codigos más importantes que uso en el día a día

## Códigos de java

```Java
//Multiplica el descuento que le demos con el precio original dandonos como resultado el descuento de este mismo
double GetDiscount(double discount, double priceOriginal){
    return priceOriginal * discount;
}
```

```Java
//Patrón de diseño - Singleton - sintáxis básica
private  class Singleton{
    private static Singleton instancia;

    private Singleton(){}

    public static Singleton getInstancia(){
        if(instancia == null){
            instancia = new Singleton();
        }
        return instancia;
    }  
}
```
