# H1!

```java
//a cuteness arithmetic series
    public class DogTest {

        @Test
        public void testGetDogYears() {
            Dog d = new Dog("Max", 3);
            assertEquals(21, d.getDogYears());
        }

        @Test
        public void testGetters() {
            Dog d = new Dog("Bella", 5);
            assertEquals("Bella", d.getName());
            assertEquals(5, d.getAge());
        }

        @Test
        public void testFindOldestDog() {
            Dog[] dogs = {
                    new Dog("Rex", 4),
                    new Dog("Luna", 8),
                    new Dog("Charlie", 6)
            };
            Dog oldest = Dog.findOldestDog(dogs);
            assertEquals("Luna", oldest.getName());
            assertEquals(8, oldest.getAge());
        }
    }




});
```