# Artificial Intelligence for Robotics Assignments
## First Assignment

## Second Assignment

*Reference professor*: Fulvio Mastrogiovanni

*Language*: PDDL
*Planning engine*: [popf3-clp](https://github.com/popftif/popf-tif)

### Collaborators

| Name                  | ID       |
| --------------------- |:--------:|
| Nicholas Attolino     | S5656048 |
| Claudio Tomaiuolo     | S5630055 |
| Teodoro Lima          | S5452613 |

## Installation

You only need to install the required libraries:
```sh
sudo apt-get install cmake coinor-libclp-dev coinor-libcoinutils-dev coinor-libosi-dev coinor-libcbc-dev coinor-libcgl-dev doxygen bison flex
```

There is no need to compile the `popf3-clp` since it is already compiled in the root folder.

## Usage

To run the program is necessary to be into the folder of the assignment and to open a terminal window; after that just run this:
```sh
./popf3-clp -x ./visits_domain/dom1.pddl ./visits_domain/prob1.pddl ./visits_module/build/libVisits.so ./visits_domain/region
```

## Notice

You may have to add execution privileges to the following files:
```sh
sudo chmod +x popf3-clp
```
