# Hello everyone! <img src="https://raw.githubusercontent.com/MartinHeinz/MartinHeinz/master/wave.gif" width="30px" height="30px"> 😄 That's ***@[spokedu13](https://spokedu13.github.io/)***

## :seedling: Self-taught Programmer && a Lifelong Learner

I'm a :fr: French Web and Mobile developer, living in Marseille, France. Self-taught by nature, I like to develop complex web and mobile applications while learning new techniques each day. Passionate about technology and its value, I have a great desire to build a product that can solve people's problems at scale.

## :wrench: Technologies && Tools

- Front End

![](https://img.shields.io/badge/.-html-%23E34F26?style=for-the-badge&logo=html5) ![](https://img.shields.io/badge/.-css3-%231572B6?style=for-the-badge&logo=css3) ![](https://img.shields.io/badge/.-javascript-%23F7DF1E?style=for-the-badge&logo=javascript)

![](https://img.shields.io/badge/.-jQuery-%230769AD?style=for-the-badge&logo=jquery) ![](https://img.shields.io/badge/.-bootstrap-%237952B3?style=for-the-badge&logo=bootstrap) 

- Back End

![](https://img.shields.io/badge/.-Php-%23777BB4?style=for-the-badge&logo=php) ![](https://img.shields.io/badge/.-MySQL-%234479A1?style=for-the-badge&logo=mysql)

![](https://img.shields.io/badge/.-symfony-%23000000?style=for-the-badge&logo=symfony) 

- Mobile

![](https://img.shields.io/badge/.-swift-%23FA7343?style=for-the-badge&logo=swift)

## :nut_and_bolt: Others skills

- Versioning
- Testing
- Norming / Beautifying
- Writing of documentation and comments

## :eyes: Interests

- Web and Mobile Technologies 
- 2D and 3D Games on iOS and iPadOS
- Cybersecurity
- Photography
- Travelling

## :trophy: Projects

- [www.maconciergerieprivee-cassis.com](https://www.maconciergerieprivee-cassis.com)
- [www.anayaplongee.com](https://www.anayaplongee.com)
- [www.anayaconseil.com](https://www.anayaconseil.com)
- [www.sylvainsuppa.com](https://www.sylvainsuppa.com)
- [www.anthonybarrin.fr](https://www.anthonybarrin.fr)

## :mag: How to reach me ?

:globe_with_meridians: [www.anthonybarrin.fr](https://www.anthonybarrin.fr)

:mailbox: anthony.barrin@gmail.com

## Citations 

> - When you stop learning, you will stop going forward.
> - In Tech, it's not so much what we know that counts, it's what we are able to learn.
> - Knowledge have no limits.

## About Me in PHP code

```php
<?php

declare(strict_types=1);

namespace Developer\Spokedu13;

/**
 * This class allows me to introduce myself
 * @package Developer/Spokedu13
 * @version 1.0.0
 * @author Anthony Barrin <anthony.barrin@gmail.com>
 * @link https://www.anthonybarrin.fr
 */
#[AsHuman]
final class About extends Me implements DeveloperInterface
{
  public const USER = "Anthony Barrin";

  private string $pronouns = "He | His";
  private int $age = 32;
  private bool $isPassionateAboutCoding = true;
  private array $hobbies = [
    "Coding",
    "Studying",
    "Web and Mobile Technologies",
    "Cybersecurity"
  ];

  /**
  * This method gives my location.
  * @return string Return City and Country
  */
  public function getLocation(): string
  {
      return "Marseille, France";
  }

  /**
  * This method makes it possible to present my technical skills and my qualities.
  * @return array Return my skills
  */
  public function getSkills(): array
  {
      return ["hard-skills" => [
            Php::class,
            Javascript::class,
            Symfony::class
            ],
            "soft-skills" => [
            "Honest", "Patient", "Spirit of research", "Team Player", "Punctual"
            ]
       ];
  }

  public function getFutureGoal(): string
  {
      return 'Become a good developer and trainer.';
  }

  public function Ambitions(): void
  {
      becomeImmortal();
  }
}
```
