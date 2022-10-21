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
### Cemitery
```
[out:json][timeout:120];
{{geocodeArea:brazil}}->.searchArea;
(
  node["landuse"="cemetery"](area.searchArea);
  node["amenity"="grave_yard"](area.searchArea);
  
);
out body;
>;
out skel qt;
```

### Parking
```
[out:json][timeout:120];
{{geocodeArea:brazil}}->.searchArea;
(
  node["amenity"="parking"](area.searchArea);
  node["amenity"="parking_space"](area.searchArea);
  
);
out body;
>;
out skel qt;
```

### Wood
```
[out:json][timeout:120];
{{geocodeArea:brazil}}->.searchArea;
(
  node["natural"="wood"](area.searchArea);
  
);
out body;
>;
out skel qt;
```
### Water
```
[out:json][timeout:120];
{{geocodeArea:brazil}}->.searchArea;
(
  node["natural"="water"](area.searchArea);
  
);
out body;
>;
out skel qt;
```

### Helipad
```
[out:json][timeout:120];
{{geocodeArea:brazil}}->.searchArea;
(
  node["aeroway"="helipad"](area.searchArea);
  
);
out body;
>;
out skel qt;
```
