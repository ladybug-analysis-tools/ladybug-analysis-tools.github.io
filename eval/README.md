
New Site Read Me ~ Draft
===

# http://ladybug-tools.github.io/eval/


_Some ideas - by Theo - put here until they have a proper place to go to_

# Ladybug Tools

## Issues
Significant changes at detail design stages are more expensive than changes at preliminary design stages.

Whenever geo-physical elements - such as Sun-control and weather - are significant contributors to a the design of building,
then awareness of these design-influencing issues early in the design process may reduce or prevent the costs at major changes at later stages.

In order for geo-pgysical input to be useful at early design stages, the insights must be generated quickly, cheaply and easily.

When people with considerable geo-physical talent are involved at early stages, then the tools must be able to give the experts the insights they seek.

When designers with less of a technical background are involved,
the tools should be easy to pick and able to produce reports with meaning and relevance to lay-peeps.

The Ladybug Tools set of apps is designed to help designers - both expert and novice - make better early stage design decision based on timely, accurate and inexpensive calculations.

## The Ladybug Tools

### Butterfly: Wind, Architectural Aerodynamics
	* https://github.com/ladybug-tools/butterfly
	* Butterfly is python library to create and execute OpenFOAM cases
	* [OpenFOAM]( https://en.wikipedia.org/wiki/OpenFOAM ) (for "Open source Field Operation And Manipulation") is a C++ toolbox for the development of customized numerical solvers, and pre-/post-processing utilities for the solution of continuum mechanics problems, including [computational fluid dynamics (CFD)]( https://en.wikipedia.org/wiki/Computational_fluid_dynamics )
	* Are we [OpenFOAM+]( http://openfoam.com/ ) or [OpenFOAM]( https://openfoam.org/ )?? Anf why?
	* Dynamo: Butterfly connects Dynamo to OpenFOAM for CFD simulation.

### Dragonfly
	* https://github.com/chriswmackey/Dragonfly
	* A plugin for climate data generation and manipulation
	* Dragonfly allows users to import several satellite image data sets into Rhino/Grasshopper and warp climate files based on either this satellite data, urban morphology parameters, or future climate change scenarios.
	* The Dragonfly project intends to make many large-scale climate variables accessible to the visual scripting interface of Grasshopper as well as the 3D visualization interface of Rhino.

### Honeybee
	* https://github.com/mostaphaRoudsari/honeybee
	* https://github.com/ladybug-tools/honeybee
	*  A free and open source Grasshopper3D plugin for building energy and daylighting simulation with connections to
		* EnergyPlus
		* Radiance
		* Daysim
		* OpenStudio
	* Dynamo: Honeybee connects Revit and DynamoBIM to Radiance and OpenStudio (EnergyPlus) for daylight and energy simulation.

### Ladybug:
	* https://github.com/mostaphaRoudsari/ladybug
	* https://github.com/ladybug-tools/ladybug

	* Core functionalities of Ladybug with no geometry library dependencies
	* A Grasshopper3D plugin for environmental analysis
	* imports standard EnergyPlus Weather files (.EPW) in Grasshopper and provides a variety of 2D and 3D designer-friendly interactive graphics to support the decision-making process during the initial stages of design.
	* The tool also provides further support for designers to test their initial design options for implications from radiation and sunlight-hours analyses results.
	* Dynamo: Ladybug is a plugin for weather data and environmental analysis [Updated for Dynamo 1.3.0].


## About

Ladybug Tools are primarily built using Python.  << which version?

Ladybug Tools are built using [visual programming languages (VPL)]( https://github.com/mostaphaRoudsari/ladybug )
