```PHP

final class PatrykNamyslak{
    public static string $name = "Patryk Namyslak";
    public static string $role = "Full stack Web Developer";
    public static array $stack = [
        "Base for all" => ["Linux", "Apache", "MySQL", "PHP"],
        "Simple Websites" => ["HTML", "CSS", "HTMX"],
        "Full stack Apps" => ["Laravel", "Livewire", "Vite"],
        ];
    public static array $projects = ["Frontend Foundry", "Flag API", "Url Shortener"];

    public static function greeting(){
        echo "Hi there! I my name is " . self::$name . " and I am a " . self::$role;
    }
}

PatrykNamyslak::greeting();
```