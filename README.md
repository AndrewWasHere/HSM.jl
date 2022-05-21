# HSM.jl

[![docs-dev](https://img.shields.io/badge/docs-dev-blue.svg)](https://andrewwashere.github.io/HSM.jl/dev)
[![Tests](https://github.com/AndrewWasHere/HSM.jl/actions/workflows/tests.yml/badge.svg)](https://github.com/AndrewWasHere/HSM.jl/actions/workflows/tests.yml)

Hierarchical State Machine (HSM) library for complex, stateful, event-driven 
applications written in Julia.

HSM is based on Unified Modeling Language (UML) state machines (also called
state charts).

## Example

`test/test_temperature.jl` is a sample state machine demonstrating how to use
HSM.jl. To see a graphical representation of the thermometer state machine
described in the file's docstring, pass it through [PlantUML](https://plantuml.com).

Unlike `test_temperature.jl`, you will probably want to slap an event queue in 
front of your state machine.

## License

Copyright 2022, Andrew Lin. All rights reserved.

This library is licensed under the MIT License. See LICENSE.txt or
https://opensource.org/licenses/MIT.