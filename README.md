# TestFramework

A subject-matter-independent framework for automatically running self-checking test sets against an application.

## Usage

This framwork must be combined with a subject-matter-specific "testbench" which specifies sequences of stimuli followed by observations.
The framework sequences the injection of stimuli and the following observations adjudicate application response.
An example of the use of such a testbench in conjunction with the framework can be found at https://github.com/johnrwolfe/CarPark.
