### Building Nodes
```
[out:json][timeout:400];
{{geocodeArea:brazil}}->.searchArea;
(
  node["building"](area.searchArea);
);
out body;
>;
out skel qt;
```

### Swimming_pool Nodes
```
[out:json][timeout:120];
{{geocodeArea:brazil}}->.searchArea;
(
  node["leisure"="swimming_pool"](area.searchArea);
);
out body;
>;
out skel qt;
```
### Parks Nodes
```
[out:json][timeout:120];
{{geocodeArea:brazil}}->.searchArea;
(
  node["leisure"="park"](area.searchArea);
);
out body;
>;
out skel qt;
```
### Pitch Nodes
```
[out:json][timeout:120];
{{geocodeArea:brazil}}->.searchArea;
(
  node["leisure"="pitch"](area.searchArea);
);
out body;
>;
out skel qt;
```
