## Example project on how to implement custom MTBDD leaves with the trolando/sylvan library
This project is a demonstration example on how to create a custom MTBDD leaves using the [Sylvan](https://github.com/trolando/sylvan/) library.
The implemented example leaf holds a single 2D point. To demostrate how to manipulate MTBDDs with custom leaves,
the example implements a simple operation taking a maximum of two points based on their size.

### Building
**Dependencies** - `git` + see [Sylvan](https://github.com/trolando/sylvan/), and [Lace](https://github.com/trolando/lace/).

To build the example binary run:
```bash
make
```
To simplify the building process, the default `make` target downloads and compiles both Sylvan and Lace (work-stealing framework on top of which Sylvan is built).
The resulting binary `example` is stored in root of the project.
```bash
./example
```
