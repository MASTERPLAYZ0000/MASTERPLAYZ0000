<img style="height: auto; width: 100%;" src="https://github.com/MASTERPLAYZ0000/MASTERPLAYZ0000/blob/7891eea44cd2bc344e1c4bbf248e65c47d58aae0/images/header.jpg" />
<img align="center" style="height: auto; width: 100%;" src="https://github-profile-trophy.vercel.app/?username=MASTERPLAYZ0000&theme=tokyonight" />
```php
<?php

namespace MASTERPLAYZ0000;

use MASTERPLAYZ0000\languages\Php;
use MASTERPLAYZ0000\languages\Golang;
use MASTERPLAYZ0000\languages\JavaScript;
use MASTERPLAYZ0000\languages\CSharp;

use MASTERPLAYZ0000\ides\PhpStorm;
use MASTERPLAYZ0000\ides\GoLand;
use MASTERPLAYZ0000\ides\WebStorm;
use MASTERPLAYZ0000\ides\VisualStudio;

use MASTERPLAYZ0000\editors\VisualStudioCode;
use MASTERPLAYZ0000\editors\Notepad;
use MASTERPLAYZ0000\editors\Vim;

class About extends Myself {

  private $name = "MasterPlayz";
  
  private $discord = "MasterPlayz#8424";
  
  private $age = 17;
  
  public function getName() : string {
    return $this->name;
  }
  
  public function getDiscord() : string {
    return $this->discord;
   }
   
   public function getAge() : string {
    return $this->age;
   }
    
  public function getJob() : array {
    return [
      "company" => null,
      "position" => null,
    ];
  }
  
  public function getKnownLanguages() : array {
    return [
      Php::class,
      Golang::class,
      JavaScript::class,
      CSharp::class
    ];
  }
  
  public function getUsingIdes() : array {
    return [
      PhpStorm::class,
      GoLand::class,
      WebStorm::class,
      VisualStudio::class
    ];
  }
  
  public function getUsingEditors() : array {
    return [
      Notepad::class,
      VisualStudioCode::class,
      Vim::class,
      SublimeText::class
    ];
  }
}
?>
```
<img align="right" style="height: auto; width: 40%;" src="https://github-readme-stats.vercel.app/api?username=MASTERPLAYZ0000&show_icons=true&locale=en&theme=tokyonight" />
<img align="left" style="height: auto; width: 40%;" src="https://github-readme-streak-stats.herokuapp.com/?user=MASTERPLAYZ0000&theme=tokyonight" />
