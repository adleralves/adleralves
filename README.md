```typescript
public class Adler {

    String name;
    String nationality;
    List<Technology> technologies;

    public Adler(String name, String nationality) {
        this.name = "Adler Alves";
        this.nationality = "Brazilian";
    }

    public void technologies() {
        technologies = new ArrayList<Technology>();
        
        Technology java = new Technology();
        java.setAbility("Spring");
        technologies.add(java);
        
        Technology javascript = new Technology();
        javascript.setAbility("Angular & React Native");
        technologies.add(java);
        
        Technology APIs = new Technology();
        APIs.setAbility("REST");
        technologies.add(APIs);
        
        Technology design = new Technology();
        design.setAbility("Bootstrap & Tailwind");
        technologies.add(design);
        
        Technology cloudcomputing = new Technology();
        cloudcomputing.setAbility("Azure & AWS");
        technologies.add(cloudcomputing);
        
    }
}
```
