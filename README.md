# Find lifts wear and tear
How much more will one lift wear out compared to the other.

In my builing we have 2 lifts with one button that calls the closest one.
Noticed that when both of them are on the same floor, the left one will arrive.
I guess there is some chip that prioritese the first lift in the list (the left one: [0, 1]).

As a result left one gets more wear and tear and e.g. already has more issues with doors.
So I wonder — how much more left one will be worn out over time?

Main issue to check: piciking the first lift in the list, if both are on the same floor.

Check [notebook](./lift.ipynb)

## TL;DR
Left one does ~2x more work:
```
Lift 4606717504: at 1, wear: 493435
Lift 4571213136: at 0, wear: 226432
```

## Run locally

```
git clone https://github.com/delopsu/lifts.git
cd lifts
pip install jupyter
jupyter notebook
```
Then select `lift.ipynb`
