# Emux Language

Emux is a embedadble scripting language.
## Table of Contents

- [Emux Language](#emux-language)
  - [Table of Contents](#table-of-contents)
  - [Introduction](#introduction)
    - [ Example](#example)
  - [Syntax](#syntax)

## Introduction

Emix is a embeddable scripting language.

###  Example

```go
PI = 3.14159265358979323846
func area(radius) {
    return PI * radius * radius
}

func playerUpdate() {
    if (inputManager.isKeyDown("space")) {
        print("Space is down")
    }
}

player = {
    name = "John",
    health = 100,
    isAlive = true,
    update = playerUpdate
}

func update(dt) {
    player.update()
}

```

## Syntax
