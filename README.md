<?php

use Illuminate\Support\Facades\Route;

Route::get('/', function () {
    return [
        'country' => 'Hungary',
        'working_on' => ['undefined'],
        'learning' => ['Node.js, Python, Linux'],
        'tools' => ['Nginx', 'Docker'],
        'discord' => [
            'tag' => 'OlevO',
            'server' => null,
        ],
    ];
});
