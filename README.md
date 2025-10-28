```PHP

final class PatrykNamyslak{
    public static string $name = "Patryk Namyslak";
    public static string $role = "Full stack Web Developer";
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
