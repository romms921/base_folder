
# Glafic Graph Plotter

This is a simple python package that automates making the basic position/flux error and ciritcal curve plots. 


## Authors

- [@rommuluslewis](https://github.com/romms921)


## License

[MIT](https://choosealicense.com/licenses/mit/)


## Installation

Install romms_glaficplots with pip

```bash
  pip install romms_glaficplots
```
    
## Usage/Examples

```python
import romms_glaficplots

filename_1 = 'obs_point.dat'
filename_2 = 'out_point.dat'
filename_3 = 'out_crit.dat'

obs_data, pred_data = error_plot(filename_1, filename_2)

obs_data, pred_data = critcurve_plot(filename_1, filename_3)
```

