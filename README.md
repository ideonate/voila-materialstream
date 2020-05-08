# voila-materialstream

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ideonate/voila-materialstream/master?urlpath=voila)

Material design template for voila

This is derived completely from the [voila-material theme](https://github.com/voila-dashboards/voila-material) by the Voila team.

Changes:

- Hide the Voila logo (sorry! But clients will just immediately ask what the voila logo means. We need to find another way to raise awareness with non-tech people)

- Make the top nav bar narrower and animate while running (Borrowed from [Streamlit](https://streamlit.io/). Also sorry! But Streamlit has really raised the bar on style...)

## Installation

You can install it using pip:

```
pip install voila-materialstream
```

## Usage

```
voila my_notebook.ipynb --template=materialstream
```

Or for the dark theme:

```
voila my_notebook.ipynb --template=materialstream --theme=dark
```

### Light theme

These screenshots are from the original theme.

![screenshot](./material_tree.png)
![screenshot](./material_spinner.png)
![screenshot](./material_light.png)

### Dark theme

These screenshots are from the original theme.

![screenshot](./material_dark_spinner.png)
![screenshot](./material_dark.png)
