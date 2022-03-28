### Hi there 👋
```php
<?php

namespace DoncovGleb;

class About extends Me
{
    private $name = 'Gleb';
    private $surname = 'Doncov';
    private $place_of_birth = 'Sochi'
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
**inotmustdie/inotmustdie** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
