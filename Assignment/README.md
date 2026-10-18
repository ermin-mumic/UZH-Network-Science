# Network Science HS26 – Assignment

Analysis of the enzyme structural graph in `dataset/edgelist.txt`.

## Files

- `assignment.ipynb` – executed notebook with all calculations and figures
- `report.pdf` – report
- `dataset/edgelist.txt` – supplied edge list
- `requirements.txt` – Python packages

## How to run

Tested with Python 3.9.6.

    python3 -m venv venv
    source venv/bin/activate          # Windows: venv\Scripts\activate
    pip install -r requirements.txt
    jupyter notebook assignment.ipynb

Then run all cells (Kernel → Restart & Run All). This takes about a minute.

## Notes

- The edge list lists every edge in both directions; it is loaded as a simple undirected graph
  (51 nodes, 110 edges).
- All random steps use a fixed seed (`SEED = 42`), so the results are reproducible.
