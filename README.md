## Wiatj na moim profilu 👋

### Tutaj masz mój opis w języku Java :
Main.java
```java
public class Main {
    public static void main (String[] args){
    
        Person person = new Person();
        
        person.setName("HubiRto");
        person.setJob("niezależnym programistą");
        person.setCodingLanguages("Java");

        System.out.println("Witaj, nazywam się " + person.getName());
        System.out.println("Aktualnie jestem " + person.getJob());
        System.out.println("Programuje w języku " + person.getCodingLanguages());
    }
}
```
Person.java
```java
public class Person {

    private String name;
    private String job;
    private String codingLanguages;

    public void setName(String name) {
        this.name = name;
    }
    
    public void setJob(String job) {
        this.job = job;
    }
    
    public void setCodingLanguages(String codingLanguages) {
        this.codingLanguages = codingLanguages;
    }
    
    public String getName() {
        return name;
    }
    
    public String getJob() {
        return job;
    }
    
    public String getCodingLanguages() {
        return codingLanguages;
    }
}
```
Wynik:
```txt
Cześć, nazywam się HubiRto
Aktualnie jestem niezależnym programistą
Programuje w języku Java
```
