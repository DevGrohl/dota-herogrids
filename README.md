# DOTA Herogrids
Simple repository to save, share and expose different herogrid layouts

## Contributions

You can access your own hero grids from:

`Steam\userdata\<STEAM-ID>\570\remote\cfg\hero_grid_config.json`

You can copy & paste any hero grid from within the "configs" tag and share a picture of the result, example:

![test-grid](https://raw.githubusercontent.com/DevGrohl/dota-herogrids/master/img/test-grid.png)

```
{
  "version": 3,
  "configs":
  [
    "config_name": "test-grid",
    "categories":
    [
      {
        "category_name": "Safe Lane",
        "x_position": 0.000000,
        "y_position": 0.000000,
        "width": 465.217407,
        "height": 91.304352,
        "hero_ids": [4,6,8,48,114,44,67,63]
      }
    ]
  ]
}
```
# Automation

While some hero grids require no updates over time like:

- D&D Alignment
- Classic Dota grid

Other ones can use automation to get updated periodically

- Dota Plus (by rank)
- Function grid

For this we can use a combination of sites like Dotabuff or opendota to evaluate what is meta at each rank, and further extend on this premise, for example:

- Which heroes are being played by X pro player (RTZ grid / Topson grid)
- Which heroes have the highest pick and win rate in X tournament (Dreamleague X grid)
