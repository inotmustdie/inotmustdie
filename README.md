### Hi there š
```php
<?php

namespace DoncovGleb;

class About extends Me
{
    private $name = 'Gleb';
    private $surname = 'Doncov';
    private $place_of_birth = 'Sochi';
    private $full_age = 24;
    private $work_exp = 3.4;

    public function getCurrentWorkplace() {
        return [
            'workplace' => [
                'company' => 'ZazuGroup',
                'position' => 'Web-developer'         
            ]
        ];
    }

    public function getDailyKnowledge() {
        return [
            Php::class,
            Laravel::class,
            MySQL::class,
            MongoDB::class,
            Vuejs::class,
            Javascript::class
        ];
    }

    public function getFutureGoal() {
        return 'To contribute to open source.';
    }

    public function getFullName() {
        return $this->name . ' ' . $this->surname;
    }
}
```
<!--
**inotmustdie/inotmustdie** is a āØ _special_ āØ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- š­ Iām currently working on ...
- š± Iām currently learning ...
- šÆ Iām looking to collaborate on ...
- š¤ Iām looking for help with ...
- š¬ Ask me about ...
- š« How to reach me: ...
- š Pronouns: ...
- ā” Fun fact: ...
-->
