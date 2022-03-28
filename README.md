### Hi there 👋

<?php

namespace DoncovGleb;

class About extends Me
{
    private $name = 'Gleb';
    private $surname = 'Doncov';
    private $age = 24;
    private $work_exp = 3.4;

    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'ZazuGroup',
                'position' => 'Web-developer'         
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            Php::class,
            Laravel::class,
            MySQL::class,
            MongoDB::class,
            Vuejs::class,
            Javascript::class
        ];
    }

    public function getFutureGoal(): string
    {
        return 'To contribute to open source.';
    }

    public function getRoundedAgeOfStartWorking(): int
    {
        return (int) round( $this->age - $this->work_exp );
    }
}

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
