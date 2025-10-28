```PHP

final class PatrykNamyslak{
    public static string $name = "Patryk Namyslak";
    public static string $role = "Full-stack Web Developer";
    public static array $stack = [
        "Frontend" => ["Laravel", "Blade", "Tailwind", "Livewire", "Vite", "HTML", "CSS", "HTMX"],
        "Backend" => ["Linux", "Apache", "MySQL", "PHP"],
        ];
    public static array $projects = ["Frontend Foundry", "Flag API", "Url Shortener"];

    public static function greeting(){
        echo "Hi there! My name is " . self::$name . " and I am a " . self::$role;
    }
}

PatrykNamyslak::greeting();
```

```
worker@patryknamyslak.pl~$ php Patryk.class.php
> Hi there! My name is Patryk Namyslak and I am a Full-stack Web Developer
```
