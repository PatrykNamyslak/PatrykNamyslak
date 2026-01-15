```PHP

abstract class PatrykNamyslak{
    public static string $name = "Patryk Namyslak";
    public static string $role = "PHP Web Developer";
    public static array $stack = [
        "Frontend" => [
            "Blade", 
            "TailwindCSS", 
            "Livewire", 
            "Vite", 
            "HTML", 
            "CSS", 
            "HTMX"
            ],
        "Backend" => [
            "PHP", 
            "Laravel", 
            "Redis"
            ],
        "Server" => [
            "Linux", 
            "Apache", 
            "MySQL"
            ],
        ];
    public static array $projects = [
        "Resume Builder", 
        "Form Builder", 
        "Frontend Foundry", 
        "Flag API", 
        "Url Shortener", 
        "Database Communication Interface"
        ];

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
# Projects
<a href="https://frontendfoundry.dev">Frontend Foundry</a>
