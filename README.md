# Electric Cars Dashboard (Flask + Tableau)

This project provides a simple Flask-based web app that embeds a Tableau dashboard.

## How it works

- `app.py` runs a lightweight Flask server.
- `templates/index.html` is the landing page with a link to view the dashboard.
- `templates/dashboard.html` is where your Tableau embed code goes.

## Getting Started

1. Install dependencies:

```bash
python -m pip install -r requirements.txt
```

2. Run the app:

```bash
python app.py
```

3. Open the browser and visit:

```
http://localhost:5000
```

4. Edit `templates/dashboard.html` and paste your Tableau embed snippet into the `<div id="tableauViz">` block.

---

### Example Tableau embed snippet

```html
<iframe src="https://public.tableau.com/views/YourWorkbook/YourView?:embed=y&:showVizHome=no" width="100%" height="100%" frameborder="0"></iframe>
```

Replace the URL with the one provided by Tableau for your dashboard.
