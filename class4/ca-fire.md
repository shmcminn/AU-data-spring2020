# California Fire

#### By the Los Angeles Times

Story: https://www.latimes.com/projects/la-me-california-buildings-in-fire-zones/

Github repo: https://github.com/datadesk/california-fire-zone-analysis/tree/3ccb1ba815850d216769acbc97c0ebc4acbae67b

Jupyter notebook: https://github.com/datadesk/california-fire-zone-analysis/blob/3ccb1ba815850d216769acbc97c0ebc4acbae67b/notebook.ipynb


1. Open state file in Q
2. Import fire maps
3. Color fire maps
3. Import Ramona buildings as points (x, y geography)
4. Convert buildings as points `CRS 4326 - WGS 84`
5. Vector => Analysis => Count points in polygon
6. Inspect new layer polygon and truth check
7. Export new layer as CSV
8. Pivot CSV for number of points per category
9. Compare to total structures and calculate percentages