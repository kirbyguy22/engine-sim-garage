# engine-sim-garage
 An unofficial repository for custom parts and engines for AngeTheGreat's Engine Simulator: https://github.com/ange-yaghi/engine-sim

## Installing an engine
1. Clone/download the repo and copy the `assets` folder from it into the `engine-sim` root folder.
2. Edit `engine-sim/assets/test.mr` and add `import` line(s) for the new engines:  
`import "kirbyguy22/engines/toyota_2jz_ge.mr"`
3. Change the engine in the `set_engine` function in `engine-sim/assets/test.mr`:  
```
set_engine(
        engine: toyota_2jz_ge()
    )
```
