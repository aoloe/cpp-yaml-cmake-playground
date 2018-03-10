# yaml-cpp and Cmake Playground

Experimenting with Cmake and [yaml-cpp](https://github.com/jbeder/yaml-cpp) to create a `.yaml` file.

The compiled executable produces the file `test.yaml` that contains:

```yaml
Images:
  - test.jpg
  - alpha.jpg
```

Each branch contains different "solutions":

- `master`: a `main.cpp` file with the yaml related code commented out.
- `add-subdirectory`: `yaml-cpp` included through `add_subdirectory()`.

## Compile and run

- Download this repository.
- Go in the `src` directory and create a `build` directory.
- In the `build` directory, run `cmake .. && make`.
- Run `./playground/playground.  
  (The executable should run and do nothing.)
